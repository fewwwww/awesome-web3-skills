# ⚡ awesome-web3-skill

> A curated list of AI agent skills, MCP servers, and frameworks for Web3 — covering onchain execution, CeFi, on-chain data, security, and agent infrastructure.

Inspired by [awesome-uniswap-hooks](https://github.com/fewwwww/awesome-uniswap-hooks). PRs welcome.

---

## Table of Contents

- [🌟 Featured](#-featured)
- [Onchain Skills](#onchain-skills)
  - [DEX & Aggregators](#dex--aggregators)
  - [Bridges & Cross-chain](#bridges--cross-chain)
  - [MCP Servers & On-Chain Data](#mcp-servers--on-chain-data)
  - [Security & Risk](#security--risk)
- [CeFi Skills](#cefi-skills)
- [Agent Frameworks](#agent-frameworks)

---

## 🌟 Featured

### [OKX Onchain OS Skills](https://github.com/okx/onchainos-skills)
> AI-native onchain execution layer by OKX — wallet queries, token discovery, market data, DEX swaps, and transaction broadcasting across 60+ chains and 500+ DEXs, running on 1.2B daily API calls.

**Modules / Capabilities:**
- `Wallet` — balance queries, transaction history, multi-chain support
- `Market Data` — real-time prices, K-line charts, smart money signals, meme pump scanning, wallet PnL
- `Token Discovery` — metadata, market cap, rankings, liquidity pools, holder analysis, top traders
- `DEX Swap` — smart routing across 500+ DEXs, slippage optimization, token approvals
- `Transaction Broadcast` — sign and submit, gas estimation
- `Payments` — x402 pay-per-use protocol, zero-gas on X Layer

**Access:** AI Skills (natural language) · MCP · REST API  
**Works with:** OpenClaw, Claude Code, Cursor, Codex CLI

---

## Onchain Skills

### DEX & Aggregators

#### [Uniswap AI](https://github.com/Uniswap/uniswap-ai)
> Official Uniswap skills, plugins, and agents for building with Uniswap v4 in AI coding environments — swap, liquidity, hooks, and pool data tools for coding agents.

**Modules / Capabilities:**
- `Swap` — ERC-20 token swaps across Ethereum, Base, Arbitrum, and other EVM chains
- `Liquidity` — add/remove LP positions, concentrated liquidity (v3/v4)
- `Pool Data` — pool state, tick data, price ranges
- `Hooks` — custom hook interaction (v4)
- `Quote` — best route and price quote

**Access:** AI Skill (Claude Code, Cursor)

---

#### [Jupiter](https://station.jup.ag/docs/apis/swap-api)
> Solana's DEX aggregator — swap routing across Raydium, Orca, Phoenix, and dozens of other protocols.

**Modules / Capabilities:**
- `Quote` — price quotes with slippage control
- `Swap` — transaction construction and execution
- `Limit Orders` — on-chain limit order placement
- `DCA` — dollar-cost averaging strategy execution
- `Price API` — real-time price feeds for SPL tokens
- `Token List` — verified token registry

**Access:** REST API · integrated in Solana Agent Kit & ElizaOS

---

#### [Raydium](https://docs.raydium.io/raydium/traders/trade-api)
> Solana's leading AMM and CLMM DEX, the backbone of Solana DeFi liquidity.

**Modules / Capabilities:**
- `AMM Swap` — token swaps via standard AMM pools
- `CLMM` — concentrated liquidity market maker position management
- `Liquidity` — add/remove liquidity, pool creation
- `Launchpad` — token launch via Raydium pools

**Access:** REST API · integrated in Solana Agent Kit & ElizaOS

---

#### [1inch](https://docs.1inch.io/docs/aggregation-protocol/introduction)
> Leading EVM DEX aggregator and intent-based trading protocol, routing across 300+ liquidity sources on 13+ chains.

**Modules / Capabilities:**
- `Aggregation Protocol` — best-route swap routing
- `Fusion+` — intent-based cross-chain swaps with MEV protection
- `Limit Orders` — gasless limit and stop-loss orders
- `Portfolio` — multi-chain portfolio tracking
- `Price Oracle` — on-chain price feeds

**Access:** REST API · MCP (community)

---

#### [KyberSwap](https://docs.kyberswap.com/kyberswap-solutions/kyberswap-aggregator)
> Multi-chain DEX aggregator with optimal routing across 17 chains and 420+ liquidity sources.

**Modules / Capabilities:**
- `Aggregator Swap` — swap with split routing
- `Liquidity` — add/remove KyberSwap Elastic LP positions
- `Price Data` — token prices, pool data
- `Gas Optimization` — gas estimation and route optimization

**Access:** REST API

---

### Bridges & Cross-chain

#### [deBridge](https://github.com/debridge-finance/debridge-mcp)
> Cross-chain interoperability and liquidity transfer protocol with an official MCP server for AI agents.

**Modules / Capabilities:**
- `Cross-chain Swap` — optimal route discovery across major networks
- `Bridge` — non-custodial asset transfer between chains
- `Fee Estimation` — gas and bridge fee calculation
- `Order Tracking` — cross-chain transaction status

**Access:** MCP (official) · REST API

---

#### [Wormhole](https://docs.wormhole.com)
> Cross-chain messaging and asset bridging infrastructure connecting 30+ blockchains.

**Modules / Capabilities:**
- `Token Bridge` — wrapped asset transfers across chains
- `Cross-chain Messaging` — arbitrary message passing between protocols
- `NTT (Native Token Transfers)` — non-wrapped native token bridging
- `Route Query` — optimal bridge route and fee estimation

**Access:** MCP (community) · SDK · REST API

---

### MCP Servers & On-Chain Data

#### [CoinGecko MCP](https://docs.coingecko.com/docs/mcp-server)
> Official CoinGecko MCP server — comprehensive crypto market data across 200+ blockchains and 8M+ tokens.

**Modules / Capabilities:**
- `Price Data` — real-time and historical prices
- `Market Data` — market cap, volume, rankings, trending
- `Token Metadata` — project info, categories, platforms
- `DeFi Pools` — GeckoTerminal on-chain pool data
- `NFT Data` — collection stats, floor prices
- `Derivatives` — futures and options market data

**Access:** MCP (official) · REST API

---

#### [The Graph MCP](https://github.com/kukapay/thegraph-mcp)
> Decentralized indexing protocol — enables agents to query subgraphs via GraphQL across Ethereum, Solana, Arbitrum, and more.

**Modules / Capabilities:**
- `Subgraph Query` — custom GraphQL queries for any indexed protocol
- `Protocol Data` — DeFi stats (Uniswap, Aave, Compound, etc.)
- `Historical Data` — time-series blockchain event data
- `Subgraph Deployment` — publish custom indexing logic

**Access:** MCP (community) · GraphQL API

---

#### [Base (AgentKit)](https://github.com/coinbase/agentkit)
> Official Coinbase AgentKit — AI agent toolkit for building onchain apps on Base and other EVM-compatible networks.

**Modules / Capabilities:**
- `Wallet & Balance` — Base account queries, ETH/ERC-20 balances
- `Transaction` — send, simulate, and track transactions
- `Smart Contract` — deploy and interact with contracts
- `Onramp` — fiat-to-crypto via Coinbase

**Access:** MCP · SDK

---

### Security & Risk

#### [SlowMist MistTrack MCP](https://github.com/slowmist/MistTrackMCP)
> Official MistTrack MCP server for blockchain threat intelligence, address risk scoring, and multi-layer fund tracing.

**Modules / Capabilities:**
- `Address Labels` — exchange, mixer, scam, or known entity tags
- `Risk Score` — risk scoring for addresses and transaction hashes
- `Address Overview` — balance, transaction count, statistics
- `Counterparty Analysis` — inbound/outbound transaction counterparties
- `Fund Flow Tracing` — multi-layer recursive transaction graph analysis
- `Malicious Fund Detection` — USDT blacklist, stolen funds check
- `Chain Detection` — auto-detect blockchain from address

**Access:** MCP (official) · API key required  
**Works with:** Claude, Cursor

---

#### [HostDeFi](https://hostdefi.com)
> Free multi-chain token risk scanner and agent API — instant on-chain safety grades for token contracts across 7 EVM chains and Solana.

**Modules / Capabilities:**
- `Token Risk Grades` — instant safety score for any token contract
- `Authority Checks` — mint/freeze authority detection
- `Liquidity & Holders` — liquidity depth and holder-concentration analysis
- `Honeypot Detection` — buy/sell simulation checks
- `Chain Coverage` — Solana plus Ethereum, Base, Arbitrum, BSC, Polygon, Optimism, Avalanche

**Access:** MCP (hosted: https://hostdefi.com/api/v1/mcp) · REST API · x402 machine-payable API

---

## CeFi Skills

### [Binance Skills Hub](https://github.com/binance/binance-skills-hub)
> Open skills marketplace giving AI agents native access to Binance CEX — spot, futures, margin, asset management.

**Modules / Capabilities:**
- `Spot Trading` — order book, ticker, klines, order placement, cancellation
- `Futures (USD-M)` — market data, funding rates, open interest, leverage controls, algo orders
- `Margin Trading` — cross & isolated margin, borrow/repay, liquidation history
- `Asset Management` — balances, deposit/withdrawal history, dust conversion
- `Address Insight` — wallet holdings, asset valuations, 24h changes
- `Binance Alpha` — trending on-chain tokens, candlesticks (no API key required)
- `Trading Signals` — buy/sell signals based on market or smart money conditions
- `Contract Risk Detection` — security risk scoring for tokens

**Access:** AI Skills · REST API

---

### [Bybit MCP](https://github.com/dlwjdtn535/mcp-bybit-server)
> Community MCP server wrapping the Bybit API for market data, account management, and order execution.

**Modules / Capabilities:**
- `Market Data` — ticker, order book, recent trades
- `Account Management` — balance, open positions
- `Order Execution` — place, cancel, query orders (spot & derivatives)

**Access:** MCP (community)

---

### [BingX](https://bingx.com/en/developer/)
> BingX exchange API integration for AI agents, supporting spot and perpetual contract trading.

**Modules / Capabilities:**
- `Spot Trading` — market/limit orders, balance queries
- `Perpetuals` — contract trading, position management
- `Market Data` — price feeds, candlesticks

**Access:** REST API

---

### [Bitget](https://www.bitget.com/api-doc/common/intro)
> Bitget exchange and Bitget Wallet API supporting CEX trading alongside on-chain wallet operations.

**Modules / Capabilities:**
- `Spot & Futures Trading` — order management, account queries
- `Wallet Operations` — multi-chain asset queries, transfer
- `Market Data` — tickers, depth, klines

**Access:** REST API

---

### [Gate.io](https://www.gate.io/docs/developers/apiv4/)
> Gate.io exchange API covering spot, margin, futures, and options with broad asset coverage.

**Modules / Capabilities:**
- `Spot / Margin / Futures / Options` — full order lifecycle
- `Market Data` — real-time feeds, candlesticks
- `Account` — balance, history, sub-account management

**Access:** REST API

---

## Agent Frameworks

### [ElizaOS](https://github.com/elizaOS/eliza)
> The open-source Web3-native AI agent OS — TypeScript-based, multi-agent, with 90+ plugins and native on-chain execution across Solana, EVM, and more.

**Modules / Capabilities:**
- `EVM Plugin` — token transfers, swaps (LiFi), bridging, DAO governance on 30+ networks
- `Solana Plugin` — SOL/SPL transfers, Jupiter swaps, staking, portfolio tracking
- `Coinbase Plugin` — mass payouts, ERC-20/721/1155 contract deployment
- `Social Clients` — Discord, Telegram, Twitter/X, Farcaster
- `Memory System` — persistent cross-session agent memory (PostgreSQL)
- `Multi-agent Orchestration` — Worlds + Rooms, agent delegation
- `Model Agnostic` — GPT-4, Claude, Gemini, Llama, Grok

**Access:** Open-source (MIT) · npm · auto.fun (no-code)

---

### [Solana Agent Kit (SendAI)](https://github.com/sendaifun/solana-agent-kit)
> Open-source toolkit by SendAI connecting any AI agent to 60+ Solana protocol actions — LangChain/Vercel AI SDK compatible, with an official MCP server.

**Modules / Capabilities:**
- `plugin-token` — SPL token deploy, transfer, swap, bridge, rug check
- `plugin-nft` — Metaplex NFT mint, list, metadata management
- `plugin-defi` — staking, lending/borrowing (Lulo), spot and perp trading (Jupiter, Raydium)
- `plugin-misc` — price feeds, CoinGecko token info, domain registration (.sol)
- `plugin-blinks` — Solana Actions / Blinks interactions
- `Solana MCP` — MCP server exposing all kit actions

**Access:** Open-source (MIT) · npm · MCP  
**Works with:** LangChain, Vercel AI SDK, OpenAI function calling, Claude Code

---

## Contributing

PRs welcome! Please follow this format:
```
### [Project Name](link)
> One-line description.

**Modules / Capabilities:**
- `module` — what it does

**Access:** how agents connect
```

---

## License

MIT
