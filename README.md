# Synapse Starter (React + Vite)

## One-liner

We'll ship a production-quality starter kit that gets any team to a working dApp using Filecoin Services in **<10 minutes**: create wallet, top-up USDFC, approve allowances, upload with CommP, choose provider via Subgraph, verify PDP status, and settle via Filecoin Pay—all exposed as clean React hooks + UI blocks developers can lift into their product.

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

