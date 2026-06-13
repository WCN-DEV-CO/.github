# WCN Development Co

Small, sharp, **zero-dependency** building blocks for resilient distributed systems —
plus a few open-core engines. Every repo is original, MIT-licensed, and tested.

## Resilience & concurrency toolkit
| Repo | What it does |
|---|---|
| **circuitring** | Circuit breaker — stop hammering a failing dependency |
| **retry-jitter** | Retry with exponential backoff + jitter |
| **token-bucket** | Token-bucket rate limiter |
| **dead-letter** | Dead-letter queue for un-processable messages |
| **idempotency-key** | Idempotency keys — make retried operations safe |
| **singleflight** | Collapse concurrent duplicate calls into one |
| **ttl-cache** | Thread-safe cache with per-entry TTL + LRU |
| **tierbroker** | Tiered work routing / admission control |
| **aoi-grid** | Area-of-interest spatial grid (game netcode) |
| **glbforge** | Pure-Python GLB (glTF binary) writer |

## Open-core engines
| Repo | What it does | Extend via |
|---|---|---|
| **wcn-flux** | Backpressure-aware dataflow runtime | Scheduler / Router seams |
| **wcn-statedb** | Versioned append-only state store (time-travel, replay) | SyncBackend seam |
| **wcn-mesh** | Typed actor runtime (supervision, at-least-once) | Supervisor / Resolver seams |

**Open the engine, bring your own brain.** Each engine ships solid defaults and clean
extension seams — plug in your own scheduling, routing, sync, or supervision policy
without forking.

*Zero dependencies. MIT. Built by WCN Development Co.*
