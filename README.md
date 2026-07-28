# CurveDB

A storage engine for vectors (embeddings), written in Rust from scratch.

## What It Is
A database that stores vectors on disk in a
fast and reliable way, with similarity search. 
A personal project to learn this aspect of the Rust language.

## Why Rust
Speed, memory safety, no garbage collector.

## Status
🚧 Under construction — Phase 0: setup complete.

## Roadmap
- [x] Phase 0 — Setup
- [ ] Phase 1 — In-memory storage + testing
- [ ] Phase 2 — Durability (write-ahead log + recovery)
- [ ] Phase 3 — To disk + benchmarks
- [ ] Phase 4 — Similarity search 