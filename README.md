# ETL · REST API · SSO Foundations

## Purpose
This repository documents my hands-on learning and implementation of strong foundations in:
- ETL (Extract, Transform, Load)
- REST APIs
- Single Sign-On (SSO)

The goal is to build production-safe understanding through mini projects and capstone projects, not just theoretical knowledge.

---

## What This Repository Covers
This repository focuses on:
- Designing and building reliable ETL pipelines
- Building and consuming REST APIs with proper pagination, retries, and idempotency
- Implementing and debugging SSO using OAuth 2.0 and OpenID Connect
- Understanding failure modes, trade-offs, and real-world constraints

Non-goals:
- Advanced big data frameworks (Spark, Kafka)
- Non-REST APIs beyond basic awareness

---

## Repository Structure
- `setup/` – environment setup and verification
- `etl/` – ETL mini projects and capstones
- `apis/` – REST API mini projects and capstones
- `sso/` – SSO mini projects and capstones
- `system-capstone/` – end-to-end system combining SSO, APIs, and ETL

Each area contains:
- Mini projects focused on individual concepts
- Capstone projects that integrate multiple concepts

---

## How to Read This Repository
- Start with mini projects to understand individual concepts
- Move to capstones to see how concepts work together
- Read the README and failure notes in each project to understand design decisions

This repository is meant to be read, not just run.

---

## Quality Bar
For every project in this repository:
- Code must be runnable
- Failures must be documented
- Trade-offs must be explained
- Re-running code should not corrupt state

If a concept cannot be explained clearly, it is considered incomplete.

---

## Progress Tracking
Progress is tracked using:
- A day-by-day learning plan
- An external Excel tracker linked to this repository
- Clear Git commit history per project

This repository will evolve incrementally as concepts are added and refined.

