# ETL · REST API · SSO Foundations

## Purpose
This repository documents my hands-on work to build strong, production-safe foundations in:
- ETL (Extract, Transform, Load)
- REST APIs
- Single Sign-On (SSO)

The focus is on understanding how these systems behave in real-world conditions: failures, retries, scale, and trade-offs.  
This is not a theory or tutorial repository.

---

## Scope
This repository focuses on:
- Designing and building reliable ETL pipelines
- Building and consuming REST APIs with correct pagination, rate limiting, retries, and idempotency
- Implementing and debugging SSO using OAuth 2.0 and OpenID Connect
- Reasoning about failure modes, data correctness, and system boundaries

Out of scope:
- Big data frameworks (Spark, Kafka, etc.)
- Non-REST APIs beyond basic awareness (GraphQL, gRPC)
- UI or frontend concerns

---

## Repository Structure
- `setup/` – environment setup and verification
- `etl/` – ETL mini projects and capstones
- `apis/` – REST API mini projects and capstones
- `sso/` – SSO mini projects and capstones
- `system-capstone/` – end-to-end system combining SSO, APIs, and ETL

Each area contains:
- **Mini projects** focused on one concept at a time
- **Capstone projects** that combine multiple concepts and highlight trade-offs

---

## How to Use This Repository
- Start with mini projects to understand individual concepts in isolation
- Move to capstones to see how concepts interact in realistic systems
- Read the README, architecture notes, and failure scenarios in each project

This repository is designed to be **read and reasoned about**, not just executed.

---

## Quality Bar
For every project in this repository:
- Code must be runnable
- Failure scenarios must be explicitly documented
- Trade-offs and design decisions must be explained
- Re-running code should not corrupt state or data

If a concept cannot be explained clearly, it is treated as incomplete.

---

## Progress Tracking
Progress is tracked through:
- A day-by-day learning plan
- An external Excel tracker linked to this repository
- Clear, incremental Git commit history

This repository will evolve as understanding deepens and designs are refined.

