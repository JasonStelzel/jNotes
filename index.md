# Web3 notes

### Project will use:

Blockchain - Polygon (with optional RPC provider)</br>
Ethereum development environment - Hardhat</br>
Front end framework - Next.js & React<br>
Ethereum web client library - Ethers.js<br>
File storage - IPFS<br>
Indexing and querying - The Graph Protocol<br>

`npx create-next-app web3-blog`

`Success! Created web3-blog at /Users/jasonstelzel/src2/github/development/web3blogApp/web3-blog
Inside that directory, you can run several commands:

  npm run dev
    Starts the development server.

  npm run build
    Builds the app for production.

  npm start
    Runs the built app in production mode.

We suggest that you begin by typing:

  cd web3-blog
  npm run dev`
  
  `cd web3-blog`
  
`npm install ethers hardhat @nomiclabs/hardhat-waffle` </br>
`ethereum-waffle chai @nomiclabs/hardhat-ethers` </br>
`web3modal @walletconnect/web3-provider` </br>
`easymde react-markdown react-simplemde-editor` </br>
`ipfs-http-client @emotion/css @openzeppelin/contracts` </br>

hardhat - Ethereum development environment</br>
web3modal - An easy-to-use library that allows users to connect their wallets to your app</br>
react-markdown and simplemde - Markdown editor and markdown renderer for the CMS</br>
@emotion/css - A great CSS in JS library</br>
@openzeppelin/contracts - Open source implementations of useful smart contract standards and functionality</br>

`npx hardhat`

`? What do you want to do? Create a basic sample project`</br>
`? Hardhat project root: <Choose default path>`</br>

`npx hardhat test`

Downloading compiler 0.8.4
Compiled 4 Solidity files successfully


  Blog
Deploying Blog with name: My blog
    ✔ Should create a post (2558ms)
Deploying Blog with name: My blog
    ✔ Should edit a post (122ms)
Deploying Blog with name: My blog
    ✔ Should add update the name (69ms)


  3 passing (3s)


`npx hardhat node`

Accounts
========

WARNING: These accounts, and their private keys, are publicly known.
Any funds sent to them on Mainnet or any other live network WILL BE LOST.

Account #0: 0xf39fd6e51aad88f6f4ce6ab8827279cfffb92266 (10000 ETH)
Private Key: 0xac0974bec39a17e36ba4a6b4d238ff944bacb478cbed5efcae784d7bf4f2ff80

Account #1: 0x70997970c51812dc3a010c7d01b50e0d17dc79c8 (10000 ETH)
Private Key: 0x59c6995e998f97a5a0044966f0945389dc9e86dae88c7a8412f4603b6b78690d

Account #2: 0x3c44cdddb6a900fa2b585dd299e03d12fa4293bc (10000 ETH)
Private Key: 0x5de4111afa1a4b94908f83103eb1f1706367c2e68ca870fc3fb9a804cdab365a


Create a new file named .env.local in the root of your project and add the following configuration to start with:

ENVIRONMENT="local"</br>
NEXT_PUBLIC_ENVIRONMENT="local"</br>
(Use local, testnet, or mainnet)</br>
https://nextjs.org/docs/basic-features/environment-variables


`npm run dev`

---
