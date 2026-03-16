# TREZO

The modular toolkit for building dapps with type-safe contract interactions, pluggable wallet kits, and high-performance Web3 state management. It provides a modular suite of tools that bridge the gap between low-level Web3 protocols and developer-centric interfaces.

## Core Packages

- [**trezo (CLI)**](https://www.npmjs.com/package/trezo): A command-line tool for quickly scaffolding and setting up Trezo project templates.
- [**@trezo/evm**](https://www.npmjs.com/package/@trezo/evm): A specialized, type-safe orchestration layer for EVM blockchain integration.
- **@trezo/starknet**: _coming soon_ ⛭
- **@trezo/solana**: _coming soon_ ⛭
- **@trezo/sui**: _coming soon_ ⛭

## Design Philosophy

- **Type Safety First**: Full ABI-to-TypeScript orchestration ensures compile-time safety for all contract interactions.
- **Modular & Extensible**: A pluggable architecture for wallet kits and blockchain adapters, allowing developers to extend the ecosystem without modifying core logic.
- **Optimized Performance**: Dynamic loading and minimal dependency footprints ensure fast initial load times and high runtime efficiency.
- **Zero Configuration**: Sensible defaults and managed internal dependencies allow developers to focus on building features rather than wrestling with Web3 tooling.

## Contributing

Trezo uses `pnpm` for optimized monorepo management.

We welcome contributions! Please refer to the specific package READMEs for contribution guidelines and technical specifications.
