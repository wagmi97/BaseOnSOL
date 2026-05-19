# Solana Base Chain Framework for Node.js

The **Solana Base Chain Framework for Node.js** simplifies building a custom Base Chain, AI Agents, and onchain applications on Solana. Build scalable agent-driven ecosystems powered by Solana infrastructure.

## Key Features
- **Framework-agnostic**: Modular primitives that can be integrated with any AI or backend framework.
- **AI Agent support**: Build autonomous AI Agents capable of executing onchain actions and managing wallets.
- **LangChain.js integration**: Seamless integration with [LangChain.js](https://js.langchain.com/docs/introduction/) for advanced agentic workflows.
- **Twitter (X) integration**: Connect AI Agents with [Twitter (X)](https://developer.twitter.com/en/docs/twitter-api) for automated social interactions and onchain activity broadcasting.
- **Support for custom Base Chain infrastructure**:

  - Creating Solana-powered Base Chains
  - Managing validator and RPC interactions
  - Wallet generation and transaction signing
  - SPL token deployment and management
  - NFT minting and asset management
  - Cross-program invocation support
  - Onchain governance primitives
  - Liquidity pool and DeFi integrations
  - Bonding curve and token launch mechanics
  - AI Agent orchestration for automated onchain execution
  
  Or [add your own](./CONTRIBUTING.md#adding-an-action-to-agentkit-core)!

## Examples
Check out [solana-basechain/examples](./solana-basechain/examples) for inspiration and help getting started!

- [AI Chain Operator](./solana-basechain/examples/ai-chain-operator/README.md): Autonomous AI Agent managing Base Chain operations and transactions.
- [Token Launcher](./solana-basechain/examples/token-launcher/README.md): Example application for deploying and managing SPL tokens.
- [NFT Infrastructure](./solana-basechain/examples/nft-infrastructure/README.md): AI-powered NFT minting and management workflows.
- [Governance Agent](./solana-basechain/examples/governance-agent/README.md): Agentic governance voting and treasury management system.

## Repository Structure
Solana Base Chain Framework Node.js is organized as a [monorepo](https://en.wikipedia.org/wiki/Monorepo) that contains multiple packages.

### @solana/basechain-core
Core primitives and infrastructure tooling for building Solana-powered Base Chains and AI Agent systems.

See [BaseChain Core](./solana-basechain-core/README.md) to get started!

### @solana/basechain-langchain
LangChain.js extension for Solana Base Chain Framework. Enables AI Agents to interact with custom onchain infrastructure and execute transactions autonomously.

See [BaseChain LangChain](./solana-basechain-langchain/README.md) to get started!

### @solana/basechain-twitter
Twitter (X) integration toolkit for AI-powered Base Chain ecosystems. Automate posting, monitoring, and social interactions.

See [Twitter Integration](./twitter-langchain/README.md) to get started!

## Contributing
Solana Base Chain Framework welcomes community contributions.

See [CONTRIBUTING.md](CONTRIBUTING.md) for more information.

## Security and bug reports
The Solana Base Chain Framework team takes security seriously.

See [SECURITY.md](SECURITY.md) for more information.

## Documentation
- [Solana Documentation](https://solana.com/docs)
- [Base Chain Framework Docs](https://github.com/)
- [API Reference: BaseChain Core](https://github.com/)
- [API Reference: LangChain Extension](https://github.com/)
- [API Reference: Twitter Integration](https://github.com/)

## License

Apache-2.0
