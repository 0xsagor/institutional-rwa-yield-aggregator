# Institutional RWA Yield Aggregator (2026)

This repository provides an expert-level implementation of a multi-strategy yield aggregator. It is specifically designed to bridge the gap between institutional finance and decentralized liquidity, focusing on the primary 2026 narrative: **Real-World Asset (RWA) Integration**.

### 2026 Market Context
* **Tokenized RWAs:** Treasury bills, commercial real estate, and private credit are now primary collateral types in DeFi.
* **Cross-Chain Maturity:** Seamless liquidity movement across Ethereum L2s, Solana, and institutional subnets.
* **Compliance First:** Integrated KYC/AML hooks for permissioned liquidity pools.

### Core Architecture
* **StrategyVault.sol:** Manages deposits and issues yield-bearing LP tokens.
* **RWAAdapter.sol:** Interfaces with off-chain legal wrappers to verify asset backing.
* **LiquidityRouter.ts:** Uses cross-chain messaging (LayerZero V2) to move funds to the highest-performing compliant pools.
