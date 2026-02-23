# Quellen

Senior backend engineer with 5+ years in Rust and TypeScript. Most of that time has been in the Solana ecosystem, building the services that turn raw on-chain data into something useful: pricing engines, indexers, data pipelines.

---

## Notable Projects

### [Veritas](https://github.com/quellen-sol/veritas)
Real-time token pricing engine for Solana. Derives prices across thousands of tokens using graph-based BFS over any market relationship between two tokens. Exposes a web server with built-in observability: request tracing, pricing path inspection, and health endpoints, making it straightforward to audit pricing decisions and diagnose issues in production.

### [Solana Geyser Ingestooor](https://github.com/quellen-sol/ingestooor)
High-throughput Solana transaction ingestion pipeline built for sustained load. Raw on-chain data is essentially noise; this turns it into structured, queryable records by parsing swaps, lending, staking, and transfers across any market, then writing to ClickHouse and Postgres. Designing for backpressure and recovery was key to making this perform at scale.

---

Open to: Senior Backend and/or Infra roles in Solana

📫 marquelle.nesbitt@gmail.com
