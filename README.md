# Zero to One Archive

**The public index of things I built to answer a question.**

I prototype quickly, but this repository is not a trophy shelf where every sketch pretends to be a company. It is the map: what each project explores, what is real today, and where the unfinished edges still are.

## Portfolio key

| Label | Meaning |
|---|---|
| **Deployed prototype** | A working implementation exists and has been connected to a live or test network. |
| **Runnable prototype** | The core experience can be run locally, but production hardening remains. |
| **Product specification** | The problem, architecture, and intended workflow are documented; implementation is incomplete. |
| **Archive** | Preserved for research or historical context. Not actively maintained. |
| **Upstream-derived** | A fork, mirror, or imported open-source codebase. Not represented as original work. |

## Flagship original builds

### [Smart Agent Registry](https://github.com/CallsofSteel/smart-agent-registry)
**Status: Deployed prototype**

Onchain identity and discovery infrastructure for autonomous agents. Agent records are bound to ERC-721 credentials and can include canonical handles, MCP endpoints, token-bound wallets, and delegated operators. The contract suite includes transfer-safe owner synchronization, validation rules, tests, and a Base Sepolia deployment.

`Solidity` `Foundry` `Base` `Agent Identity` `MCP`

### [SHIPLOAD](https://github.com/CallsofSteel/SHIPLOAD)
**Status: Runnable prototype**

A security and remediation command center for rapidly generated applications. It inspects public project manifests, identifies likely dependency and configuration risks, generates grounded findings, and organizes reports across a local project fleet.

`TypeScript` `React` `Gemini` `Application Security` `Developer Tools`

### [Quidpro](https://github.com/CallsofSteel/quidpro)
**Status: Runnable frontend prototype**

A problem-to-product marketplace where industry experts surface costly broken workflows and builders unlock structured specifications through wallet-connected agreements. The current public implementation demonstrates the product interface and smart-wallet flow; production contracts and settlement are not yet shipped.

`Next.js` `TypeScript` `Base` `Coinbase Smart Wallet` `Marketplace Design`

### [Charlie Work](https://github.com/CallsofSteel/Charlie-Work)
**Status: Product specification / incomplete public scaffold**

An evidence-first recovery agent for refunds, disputes, claims, escalation paths, and stuck financial problems. The intended system combines evidence capture, timelines, deadlines, drafted actions, and human approval gates.

`Agentic Workflows` `FinTech` `Recovery Operations` `TypeScript`

### [HalluciGuard API](https://github.com/CallsofSteel/halluciguard-api)
**Status: Product specification**

A proposed verification layer for extracting claims from model output, checking supporting evidence, detecting contradictions, tracking provenance, and routing uncertain findings to review.

`AI Reliability` `Evaluation` `Provenance` `API Design`

### [NutureAI](https://github.com/CallsofSteel/nutureai)
**Status: Concept-stage product specification**

A relationship-intelligence concept focused on remembering commitments, context, and meaningful follow-ups without turning human relationships into engagement metrics.

`Personal AI` `Relationship Intelligence` `Privacy`

## Experimental archive

### [Chin Up](https://github.com/CallsofSteel/Chin-up)
**Status: Archived placeholder**

An early idea marker preserved for continuity. It is not a released product and should not be evaluated as one.

## Upstream-derived repositories

These repositories are retained for study, experimentation, or adaptation. Their upstream authors and projects deserve the credit:

- [superpowers](https://github.com/CallsofSteel/superpowers), forked from [`obra/superpowers`](https://github.com/obra/superpowers)
- [skills](https://github.com/CallsofSteel/skills), derived from [`anthropics/skills`](https://github.com/anthropics/skills)
- [voicebox](https://github.com/CallsofSteel/voicebox), derived from [`jamiepine/voicebox`](https://github.com/jamiepine/voicebox)
- [ai-job-search](https://github.com/CallsofSteel/ai-job-search), derived from [`MadsLorentzen/ai-job-search`](https://github.com/MadsLorentzen/ai-job-search)
- [Public-APIs](https://github.com/CallsofSteel/Public-APIs), a curated API-list fork with upstream attribution in its README
- [sui-mev](https://github.com/CallsofSteel/sui-mev), an imported Sui MEV research codebase matching the upstream [`fuzzland/sui-mev`](https://github.com/fuzzland/sui-mev) tree
- [synora-sdk](https://github.com/CallsofSteel/synora-sdk), an imported SDK snapshot associated with the upstream Synora project

I do not count these repositories as original portfolio projects unless a future branch contains clearly documented, material work of my own.

## What ties the originals together

The surface areas vary, but the recurring questions are consistent:

- How should autonomous software prove identity and authority?
- How do we prevent generated software from outrunning security?
- How can evidence-heavy workflows become structured, reviewable systems?
- How do people who discover valuable problems participate in the value of solving them?
- How should AI communicate uncertainty instead of manufacturing confidence?

## Build principles

1. Start with expensive friction, not a fashionable model.
2. Separate what is observed from what is inferred.
3. Use real APIs, contracts, and evidence when a system claims something is true.
4. Keep humans in control where money, identity, safety, or legal rights are involved.
5. Label maturity honestly: concept, prototype, tested system, deployment, or archive.

## About the builder

I am Justin Jensen, a Phoenix-based founder-operator working across applied AI, agent infrastructure, financial workflows, markets, developer tools, and onchain systems.

Contact: [callsofsteel@gmail.com](mailto:callsofsteel@gmail.com)
