# Quellen

Senior backend engineer with 5+ years in Rust and TypeScript. I've spent most of that time in the Solana ecosystem building the infrastructure that sits between raw chain data and something actually useful — indexers, pricing engines, data pipelines.

---

## Notable Projects

### [Veritas](https://github.com/quellen-sol/veritas)
Real-time token pricing engine for Solana. Derives prices across thousands of tokens using graph-based BFS over liquidity pools, oracle feeds, and many other types of AMMs. Exposes a web server with built-in observability — request tracing, pricing path inspection, and health endpoints — so you can actually see what the engine is doing and debug it when something looks off.

### [Solana Geyser Ingestooor](https://github.com/quellen-sol/ingestooor)
High-throughput Solana transaction ingestion pipeline built for sustained load. Raw on-chain data is essentially noise — this turns it into structured, queryable records by parsing swaps, lending, staking, and transfers across Jupiter, Raydium, Orca, Meteora, Kamino, MarginFi, and OpenBook, then writing to ClickHouse and Postgres. Designing for backpressure and recovery is most of the job here.

---

## Open To

Senior backend and infra roles. Crypto-native companies preferred.

📫 marquelle.nesbitt@gmail.com
