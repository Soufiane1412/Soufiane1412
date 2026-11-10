Hi there 👋

Backend-leaning engineer building web products end to end in Go and TypeScript on PostgreSQL. I care about systems that stay correct under concurrency: invariants, isolation levels, idempotent writes and bounded shutdowns.

## Tech stack

**Backend:** Go, Node.js, TypeScript, PostgreSQL
**Frontend:** React, Next.js, React Native
**Correctness:** isolation levels, transactional retries, concurrent worker pools, idempotency keys, invariant tests

## Featured

- [**pickup-session**](https://github.com/Soufiane1412/pickup-session): a self-initiated BlaBlaCar feature where the driver's live location is shared only during the pickup window. The session state machine and the Go/PostgreSQL store are done, with seven invariant tests green on both stores. React UI and live demo in progress.
- [**Sovereign Settlement Ledger**](https://github.com/Soufiane1412/sovereign-ledger-go): settlement engine in Go and PostgreSQL 16. Write skew reproduced under concurrent load and closed at Serializable isolation, double-entry bookkeeping with idempotency keys, bounded graceful drain on SIGTERM.

## Background

LaCapsule full-stack bootcamp: six TypeScript apps (React, Next.js, React Native, Node.js), led a team of four to a Demo Day MVP. Before that, a Master's in International Law.
