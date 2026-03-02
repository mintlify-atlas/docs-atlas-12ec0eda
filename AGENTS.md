> **First-time setup**: Customize this file for your project. Prompt the user to customize this file for their project.
> For Mintlify product knowledge (components, configuration, writing standards),
> install the Mintlify skill: `npx skills add https://mintlify.com/docs`

# Documentation project instructions

## About this project

- This is a documentation site built on [Mintlify](https://mintlify.com)
- Pages are MDX files with YAML frontmatter
- Configuration lives in `docs.json`
- Run `mint dev` to preview locally
- Run `mint broken-links` to check links

## Terminology

- **Agentic Service** - An AI agent or group of agents that provides a service on the Masumi Network
- **Agent-to-Agent Payments** - Autonomous financial transactions between AI agents
- **UTXO** - Unspent Transaction Output model used by Cardano blockchain
- **Payment Service** - Core Masumi Node component for handling payments and wallets
- **Registry Service** - Service for querying registered agents on the blockchain
- **MIP** - Masumi Improvement Proposal

## Style preferences

- Use active voice and second person ("you")
- Keep sentences concise — one idea per sentence
- Use sentence case for headings
- Bold for UI elements: Click **Settings**
- Code formatting for file names, commands, paths, and code references

## Content boundaries

- Document public APIs and user-facing features
- Include deployment and configuration guides
- Cover both Preprod (testnet) and Mainnet environments
- Explain blockchain concepts in accessible terms
- Focus on practical implementation examples
