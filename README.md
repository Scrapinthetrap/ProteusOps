# ProteusOps

ProteusOps is a governed service-business meta-infrastructure system.

It is not just a booking app and not just a storefront demo.  
Its purpose is to provide a governance-first operational substrate for service businesses using:

- owner and membership law
- subscription and plan capability law
- entitlement materialization
- operational lanes such as booking and storefront
- deterministic selftests and proof-oriented runner surfaces

---

## Canonical direction

ProteusOps follows a governed architecture where:

- governance is primary
- operations are explicit lanes
- public surfaces are projections/request boundaries
- plans define capabilities
- capabilities materialize into entitlements
- entitlements govern operational permission

Canonical chain:

Plans -> Capabilities -> Entitlements -> Operational permission

---

## Schema lane model

ProteusOps is transitioning toward the following canonical lane structure:

- `pods_core` — governance, tenancy, plans, capabilities, entitlements
- `pods_ops` — operational records such as booking, scheduling, staff, locations
- `pods_public` — public-facing views and request surfaces

This is a non-breaking architectural transition.

---

## Current project focus

Current Tier-0 focus includes:

- governed owner and membership model
- subscription and plan capability enforcement
- entitlement recompute path
- booking lane enforcement
- deterministic selftests
- authoritative Tier-0 runner consolidation

---

## Project status

ProteusOps is currently in a canonical architecture and Tier-0 proof phase.

Locked areas include:

- schema transition direction
- RPC lane classification
- runner consolidation direction
- capability law
- meta-infrastructure framing

Current emphasis is on proving the system cleanly and deterministically before expanding product scope.

---

## What ProteusOps is intended to become

ProteusOps is intended to become a reusable governed infrastructure layer for service businesses, where multiple operational lanes can exist under one commercial and governance model.

Examples of lanes include:

- booking
- storefront
- scheduling
- staff/location management
- future payment/package/waitlist surfaces
- future public request/discovery surfaces

---

## Deterministic discipline

ProteusOps follows a deterministic engineering discipline:

- UTF-8 no BOM
- LF line endings
- parse-gated PowerShell
- explicit runner surfaces
- append-only receipts
- known sane restore direction
- governance law before UI convenience

---

## Current authoritative execution surfaces

Authoritative selftest:

- `scripts/selftest_all.ps1`

Authoritative Tier-0 full-green runner:

- `scripts/_RUN_proteusops_tier0_full_green_v7.ps1`

---

## Near-term roadmap

- finalize Tier-0 proof surface
- formalize restore phases
- expand deterministic capability validation
- stabilize storefront/public lane under the same law model
- continue evolving ProteusOps as a true service-business meta-infrastructure substrate

---

## Status note

This repository is in active architecture-lock and proof-building phase. Public structure may remain intentionally minimal while deterministic foundations are being finalized.
