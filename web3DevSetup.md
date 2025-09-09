### 1) Install VScode

### 2) Configure VScode:
<ol type="a">
  <li >Install WSL2</li>
  <li>Install Ubuntu into WSL (git is already part of Ubuntu)</li>
  <li>Install extensions
    <ul>
      <li>Prettier</li>
      <li>Solidity (Juan Blanco) extension</li>
    </ul>
  </li>
</ol>

> Command line
### 3) Instal Node.js (nvm)

> Download and install nvm:
```
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.40.3/install.sh | bash
```

### 5) Install Foundry
```
curl -L https://foundry.paradigm.xyz | bash
```
  > restart terminal and run
```
foundryup
```

### 6) Install dependencies
> Install pnpm
```
npm install -g pnpm@latest-10
```

### 7) Project setup
> Next.js/React [Created by the Vercel team]; everything YES except ESLing
```
pnpm create next-app@latest
```
> Install RainbowKit (interactive wallet connect button; React library)
> wagmi and viem
```
pnpm add @rainbow-me/rainbowkit wagmi viem@2.x @tanstack/react-query
```
- Configure MetaMask (RPC url etc.)
- Get ProjectId from cloud.reown.com to have an access to the walletConnect (different wallet conectivity)

### Testing (End-to-End)
> Playwright
```
pnpm add -D @synthetixio/synpress
pnpm create playwright@latest
pnpm exec playwright test -ui
```
> Synpress
```
pnpm synpress
```
## The End

React uses tsx (react components) and it automatically takes care of TS to JS compilation. The following is no longer required.

> Initialize typescript (React uses TS natively)
```
pnpm add typescript
```
> Add viem (runs under the hood)
```
pnpm add viem
```
> Bundler for tsx to js compilation (React takes care of this)
```
pnpm add vite
```

