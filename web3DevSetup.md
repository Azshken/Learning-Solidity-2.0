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
  - viem.sh (import { } from "http://esm.sh/viem")
```
pnpm i viem [Don't need to install!]
```
