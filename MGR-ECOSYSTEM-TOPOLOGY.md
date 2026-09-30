# MGR Ecosystem Topology — Canonical Shared-System Map

## Plain-English roles
MGR-API-MCP = front door / switchboard for assistant, API, MCP, Task and Job traffic.
Brain / Center of Intelligence = dispatcher/manager, initially implemented as a subsystem of MGR-API-MCP.
MGR Creation OS = backstage factory/control plane for creation, assets, identity, continuity, provenance, rights, verification and production routing.
MGR Create Loco = visual/web reconstruction and repair product that consumes Creation OS capabilities.
MGR Agents = business workforce/automation product that consumes Brain/API-MCP and Creation OS.
TIME, iKickItz, MGR Elite, Capital, HU and future apps = product consumers with their own domain logic and UI.

## Repo rule
Repository count does not equal product count or domain count.
Keep product repos separate when their deployment/release/lifecycle differs. Unify with versioned contracts, SDK/API/MCP, shared IDs/schemas and compatibility tests.

## Ownership rule
There is one canonical owner for each shared capability. App repos may keep adapters/reference implementations during migration but must not grow competing canonical copies.

## Brain rule
Do not create a standalone Brain repo yet. Extract only after stable contracts, multi-product consumption and independent deployment/scaling make it simpler.

## Creation OS vs Create Loco
Do not merge today.
Creation OS is the factory engine.
Create Loco is a specific shop/product using that engine.

## Domain rule
Internal shared services do not need public websites. Public products may keep distinct domains while calling private shared services. API/MCP may share one API domain or subpaths. Exact domain names remain a brand/deployment decision.

