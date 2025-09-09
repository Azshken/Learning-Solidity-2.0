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

React uses tsx (react components) and it automatically takes care of ts to js compilation
> initialize typescript
```
pnpm add typescript
```
> add viem
```
pnpm add viem [Don't need to install!]
```
> Bundler for tsx to js compilation
```
pnpm add vite
```

