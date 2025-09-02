# Synapse Starter (React + Vite)

**Filecoin + Synapse SDK Starter that allows you to ship a production-ready Filecoin dApp in under 10 minutes.**

Create a wallet → top-up USDFC → set allowances → upload with CommP → pick a storage provider (Subgraph) → verify PDP → settle with Filecoin Pay. All exposed as clean React hooks and drop-in UI blocks.

## Why fund this

- **Removes Day-0 friction:** Native FEVM and Filecoin features don't work out of the box with standard EVM dev tooling and boilerplates.

- **Maximizes cohort velocity:** more WaveHack teams showing live storage + proofs + payments means better traction metrics for the program.

- **Reusable infra:** a starter people keep using after the hack published as a repo + npm packages—makes Filecoin Services the default storage choice for new dapps.

## UX flow (Proof Of Concept)

- Connect → create/inject wallet.

- Fund → testnet USDFC (balance & allowance cards).

- Approve → set safe allowance for the Warm Storage operator.

- Upload → drag-and-drop.

- Pick Provider → Subgraph list (latency, price, status).

- Settle → open or terminate rail: display validator decision & payout.

- Copy Code → every step has “Copy Hook” and “Copy Component” buttons.

## Scope & Deliverables

- Public repo with Vite + React + TS template
    - Ready-made UI blocks
    - React hooks
    
- Examples / Recipes
    - **Warm Storage MVP** — upload → PDP check → pay per retrieval.
    - Pay-per-document
    
- Docs site (in repo)

### Stack

- Frontend: React + Vite + TypeScript.

- SDK: Synapse SDK (storage, payments, subgraph).

- Chain: Filecoin (Calibnet for demos).

- Styling: Tailwind, shadcn.

## Deliverables & Timeline

- **Milestone 1:** Project scaffolding, wallet + USDFC hooks, allowance UI

- **Milestone 2:** Upload pipeline, provider Subgraph integration

- **Milestone 3:** PDP verify + Filecoin Pay settlement flows

- **Milestone 4:** Docs site, examples/recipes, release to npm
