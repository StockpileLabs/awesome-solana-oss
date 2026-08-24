# 🚀 Awesome Solana Open Source

[![Awesome](https://i.imgur.com/fZVEgpL.png)](https://github.com/sindresorhus/awesome)

A curated list of open-source Solana repositories.

This list is for:

- Discovering code to learn from
- Finding ecosystem projects to contribute to
- Getting a gauge of the Solana open-source ecosystem

See [CONTRIBUTING.md](CONTRIBUTING.md) before suggesting an addition.

## Contents

- [Clients](#clients)
- [SVM Tooling](#svm-tooling)
- [Infrastructure](#infrastructure)
- [DeFi](#defi)
- [On-Chain Primitives](#on-chain-primitives)
- [Data](#data)
- [Wallets](#wallets)
- [Web Tooling](#web-tooling)
- [Cryptography](#cryptography)
- [Security & Reverse Engineering](#security--reverse-engineering)
- [Governance](#governance)
- [Miscellaneous](#miscellaneous)

## Clients

Current and upcoming clients for Solana.

| Name | Description |
| --- | --- |
| [Agave](https://github.com/anza-xyz/agave) | Canonical fork of the original Solana Labs validator client |
| [Firedancer](https://github.com/firedancer-io/firedancer) | High performance validator implementation in C |
| [Jito Solana](https://github.com/jito-foundation/jito-solana) | MEV-enabled Agave fork |
| [Mithril](https://github.com/Overclock-Validator/mithril) | Validator / full node client implementation in Go |
| [Sig](https://github.com/Syndica/sig) | Validator implementation in Zig |
| [Salsa](https://github.com/harmonic/salsa) | Harmonic's Agave-forked validator client |
| [Samba](https://github.com/harmonic/samba) | Harmonic's Firedancer-forked validator client |

## SVM Tooling

Tooling for building, testing, and benchmarking Solana programs.

| Name | Description |
| --- | --- |
| [Anchor](https://github.com/coral-xyz/anchor) | Development framework for building secure Solana programs |
| [Mollusk](https://github.com/buffalojoec/mollusk) | A lightweight test harness for Solana programs |
| [LiteSVM](https://github.com/LiteSVM/litesvm) | A fast and lightweight library for testing Solana programs |
| [Pinocchio](https://github.com/anza-xyz/pinocchio) | Create Solana programs with no external dependencies attached |
| [Quasar](https://github.com/blueshift-gg/quasar) | Blazing fast Solana program framework |
| [Caravel](https://github.com/joeymeere/caravel) | C library for building Solana programs |
| [svm-unit-test](https://github.com/blueshift-gg/svm-unit-test) | Simple test macro setup for SVM program unit testing |
| [sbpf](https://github.com/blueshift-gg/sbpf) | Bootstrap, build and deploy sBPF assembly programs with ease |
| [sbpf-linker](https://github.com/blueshift-gg/sbpf-linker) | An upstream BPF linker for SBPF V0 programs |
| [Seashell](https://github.com/soundsonacid/seashell) | Reproducible SVM testing with mainnet state |
| [solana-verifiable-build](https://github.com/solana-foundation/solana-verifiable-build) | CLI tool for deterministically building and verifying executable against on-chain programs or buffer accounts |

## Infrastructure

RPCs, indexers, geyser plugins, and other deployable infrastructure pieces.

| Name | Description |
| --- | --- |
| [Yellowstone gRPC](https://github.com/rpcpool) | Triton's Dragon's Mouth Yellowstone gRPC service for high-performance Solana streaming |
| [Metis Binary](https://github.com/jup-ag/metis-binary) | Self-hostable Jupiter Metis Swap API |
| [TxTx](https://github.com/solana-foundation/txtx) | Terraform for web3 |

## DeFi

Decentralized finance protocols.

| Name | Description |
| --- | --- |
| [Whirlpools](https://github.com/orca-so/whirlpools) | Open source concentrated liquidity AMM contract on Solana |
| [Raydium CLMM](https://github.com/raydium-io/raydium-clmm) | Open-Source Concentrated Liquidity Market Maker |
| [Kamino Lend](https://github.com/Kamino-Finance/klend) | An open source software, for a lending protocol smart contract for the Solana blockchain |
| [Raydium AMM v4](https://github.com/raydium-io/raydium-amm) | Permissionless constant product AMM |
| [Raydium CPMM](https://github.com/raydium-io/raydium-cp-swap) | Revamped constant product AMM - no Openbook ID requirement, Token22 support |
| [Meteora DAMM v2](https://github.com/MeteoraAg/damm-v2) | Dynamic Automated Market Maker V2 |
| [Meteora DBC](https://github.com/MeteoraAg/dynamic-bonding-curve) | Dynamic Bonding Curve Program |
| [Manifest](https://github.com/Bonasa-Tech/manifest) | Spot CLOB |
| [MetaDAO](https://github.com/metaDAOproject/programs) | Programs for unruggable capital formation and market-driven governance |

## On-Chain Primitives

Useful non-DeFi on-chain primitives.

| Name | Description |
| --- | --- |
| [Squads v4](https://github.com/Squads-Protocol/v4) | Multisig / smart account primitive |
| [Lighthouse](https://github.com/Jac0xb/lighthouse) | Assertion instructions to enhance transaction security |
| [Vector](https://github.com/blueshift-gg/vector) | Offline Solana transaction signing without durable nonces |
| [Doppler](https://github.com/blueshift-gg/doppler) | The fastest oracle on Solana |
| [Subscriptions](https://github.com/solana-foundation/subscriptions) | Primitive for third party assets delegations |
| [sbpf-asm-timeout](https://github.com/deanmlittle/sbpf-asm-timeout-account) | Slot-height based cancel instruction |
| [sbpf-asm-abort](https://github.com/deanmlittle/sbpf-asm-abort) | Single transaction program shutdown |

## Data

Tooling for parsing, organizing, viewing, and analyzing Solana data.

| Name | Description |
| --- | --- |
| [Explorer](https://github.com/solana-foundation/explorer) | Explorer for Solana clusters |
| [Xray](https://github.com/helius-labs/xray) | A human-readable Solana transaction explorer powered by Helius |
| [Carbon](https://github.com/sevenlabs-hq/carbon) | Indexing framework |
| [Yellowstone Vixen](https://github.com/rpcpool/yellowstone-vixen) | Program parsing toolkit |

## Wallets

Wallets for desktop and major browsers.

| Name | Description |
| --- | --- |
| [Samui](https://github.com/samui-build/samui-wallet) | Wallet and toolbox for Solana builders |
| [Salmon](https://github.com/Salmon-HQ/salmon-wallet-frontend) | Community-owned wallet built for Solana |

## Web Tooling

Tooling for building Solana integrations into web-based applications.

| Name | Description |
| --- | --- |
| [Kit](https://github.com/anza-xyz/kit) | Solana JavaScript SDK |
| [Web3.js](https://github.com/blueshift-gg/solana-web3.js) | Updated version of Web3.js built on Kit |
| [Gill](https://github.com/gillsdk/gill) | Client library for interacting with Solana |
| [Wallet Adapter](https://github.com/anza-xyz/wallet-adapter) | TypeScript wallet adapters and components for Solana applications |

## Cryptography

Cryptographic primitives and verification libraries.

| Name | Description |
| --- | --- |
| [brine-ed25519](https://github.com/zfedoran/brine-ed25519) | Ed25519 signature verification for Solana programs |
| [solana-winternitz](https://github.com/deanmlittle/solana-winternitz) | Solana-centric implementation of the Winternitz One-Time Signature (WOTS) scheme |

## Security & Reverse Engineering

Program auditing, fuzzing, static analysis, and more.

| Name | Description |
| --- | --- |
| [Trident](https://github.com/Ackee-Blockchain/trident) | Rust-based framework for Solana program fuzzing |
| [qedsvm](https://github.com/QEDGen/qedsvm) | Execute and verify sBPF programs with a Lean 4 reference model |
| [sol-azy](https://github.com/FuzzingLabs/sol-azy) | Tooling for static analysis and reverse engineering sBPF programs |

## Governance

| Name | Description |
| --- | --- |
| [Solana Governance Proposals](https://github.com/solana-foundation/solana-governance-proposals) | Proposed and accepted governance initiatives for Solana |
| [Solana Improvement Documents](https://github.com/solana-foundation/solana-improvement-documents) | Proposed and accepted changes to the Solana protocol

## Miscellaneous

Projects that don't cleanly fit an above category.

| Name | Description |
| --- | --- |
| [Codama](https://github.com/codama-idl/codama) | Generate clients, CLIs, documentation and more from your Solana programs |
