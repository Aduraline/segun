# Segun

High performance Node.js framework built around allocation control and tail latency.

Most Node.js frameworks treat runtime cost as something to improve later. Segun starts from the opposite direction. The goal is to give engineers direct control over allocation behaviour and the tail latency that follows from it, without leaving Node.js.

If you have run Node.js in a latency-sensitive environment and watched p99 climb while CPU stayed flat, this project is for you.

## Design

Segun is being built around allocation control as a first-class concern. Object pooling, high-resolution timing, worker thread pipelines, and latency telemetry are the core primitives the framework is designed around.

## Principles

- **Allocation-aware by default.** Cost should be visible, not buried behind convenience.
- **Tail latency as a first-class goal.** Throughput matters. Spikes matter more.
- **Measured claims.** Every performance statement backed by reproducible benchmarks.
- **No unnecessary abstractions.** The efficient path should be the default path.

## Status

Segun is in early development. APIs are unstable and the framework is not ready for production use.

## License

MIT
