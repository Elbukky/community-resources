# 🧠 Monad Glossary

This glossary provides beginner-friendly definitions for key terms used throughout the Monad ecosystem and broader blockchain development. Designed to help new contributors, developers, and community members speak the same language.


### 🏗️ Core Blockchain Concepts

- **L1 (Layer 1)**: A base blockchain (like Monad, Ethereum, Bitcoin) that processes and validates transactions without relying on another chain.
- **EVM**: Ethereum Virtual Machine — the environment that runs smart contracts. Monad is EVM-compatible, so Ethereum apps can run on it with minimal changes.
- **Slot**: A unit of time used to measure when validators are selected to produce blocks.
- **Finality**: When a block is considered irreversible and cannot be altered or undone.
- **Gas**: A fee paid to perform operations (transactions or contract calls) on the blockchain. Gas is measured in units and priced in Monad’s native token.
- **Block**: A collection of transactions bundled together and permanently recorded on the blockchain.
- **State**: The current status of all accounts, balances, and smart contracts on the blockchain.


### ⚙️ Monad-Specific & Developer Terms

- **Parallel Execution**: Monad supports parallel transaction processing to increase throughput, unlike traditional blockchains that process sequentially.
- **Pipelining**: A design approach in Monad that allows overlapping stages of execution (like fetch, decode, execute) for improved performance.
- **RPC (Remote Procedure Call)**: A set of methods that developers use to interact with the Monad blockchain (e.g., checking balances, submitting transactions).
- **Bridge**: A protocol that lets you transfer tokens between Monad and other blockchains like Ethereum or Solana.
- **Node**: A server or computer running Monad software to validate transactions, store blockchain data, and relay information to others.
- **Testnet**: A sandbox version of the blockchain where developers can test code using fake tokens before deploying to mainnet.
- **Mainnet**: The real, live version of the blockchain — where real value is at stake.


### 🧱 Smart Contract Terms

- **Smart Contract**: Code stored on the blockchain that automatically executes actions when conditions are met.
- **Solidity**: The main programming language used to write smart contracts for EVM-compatible chains, including Monad.
- **Deployment**: The act of uploading a smart contract to the blockchain.
- **ABI (Application Binary Interface)**: A data format that defines how to interact with a smart contract — used by frontends and tools like ethers.js.
- **Gas Limit**: The maximum amount of gas a transaction is allowed to use.


### 🌐 Ecosystem & Governance

- **Monad**: A high-performance Layer 1 blockchain that is EVM-compatible and optimized for parallel, pipelined execution.
- **Monadbase**: The official documentation site for Monad — [https://docs.monad.xyz](https://docs.monad.xyz)
- **Monad Community Resources**: This repository! A public space for helpful guides, tutorials, tools, and community-driven knowledge.
- **Airdrop**: A way of distributing tokens (usually for free) to early adopters, users, or contributors of a blockchain or dApp.


### 🔒 Security & Protocol Terms

- **Consensus**: The mechanism by which all nodes agree on the state of the blockchain.
- **Validator**: A node that confirms and proposes new blocks. Validators are rewarded for honest behavior and penalized for misbehavior.
- **Slashing**: A penalty given to validators who behave dishonestly (like double-signing blocks).
- **Private Key**: A secret code that gives full access to a blockchain wallet — never share it.
- **Public Key / Address**: Your public blockchain identity. Others use this to send you tokens or interact with your contracts.


### 📌 Contribute

Got a new term to add?  
Fork this repo, edit this file, and submit a pull request. Let's make Monad easier for everyone to understand. 🙌
