# James Crick

**Full-stack software engineer specialising in backend, cloud and event-driven systems.**

I build products end to end, with a commercial focus on backend, cloud and serverless systems. Outside work, I explore agent infrastructure, game engines, graphics tooling and audio software, with a particular interest in AI development workflows and long-term agent memory.

[LinkedIn](https://www.linkedin.com/in/james-crick-675a2516a/)

**AWS Certified Solutions Architect – Associate** · MSc Computer Science (Distinction), Queen Mary University of London

## Toolkit

<p>
  <a href="https://www.typescriptlang.org/"><img src="https://skillicons.dev/icons?i=ts" alt="TypeScript" /></a>
  <a href="https://developer.mozilla.org/docs/Web/JavaScript"><img src="https://skillicons.dev/icons?i=js" alt="JavaScript" /></a>
  <a href="https://www.python.org/"><img src="https://skillicons.dev/icons?i=python" alt="Python" /></a>
  <a href="https://nodejs.org/"><img src="https://skillicons.dev/icons?i=nodejs" alt="Node.js" /></a>
  <a href="https://aws.amazon.com/"><img src="https://skillicons.dev/icons?i=aws" alt="AWS" /></a>
  <a href="https://www.postgresql.org/"><img src="https://skillicons.dev/icons?i=postgres" alt="PostgreSQL" /></a>
  <a href="https://react.dev/"><img src="https://skillicons.dev/icons?i=react" alt="React" /></a>
  <a href="https://nextjs.org/"><img src="https://skillicons.dev/icons?i=nextjs" alt="Next.js" /></a>
  <a href="https://threejs.org/"><img src="https://skillicons.dev/icons?i=threejs" alt="Three.js" /></a>
  <a href="https://www.swift.org/"><img src="https://skillicons.dev/icons?i=swift" alt="Swift" /></a>
</p>

**Core:** TypeScript · JavaScript · Python  
**Backend & cloud:** Node.js · AWS · PostgreSQL · serverless · event-driven systems  
**Product & graphics:** React · Next.js · Three.js · Phaser · SwiftUI  
**AI tooling:** MCP · agentic systems · RAG · LangGraph · long-term memory

**Currently exploring:** Rust · Swift · Go

## Featured work

### [Adventure Game Builder](https://github.com/kudrekode/pirate-game-engine)

Browser-based 2D/3D adventure-game editor and runtime built with React, TypeScript, Three.js and Phaser. It brings authored characters, data-driven game systems and a shared editor/runtime architecture into one creative tool.

<p>
  <img src="assets/game-engine/main-editor-3d.png" alt="Adventure Game Builder 3D editor" width="49%" />
  <img src="assets/game-engine/in-game.png" alt="Adventure Game Builder runtime" width="49%" />
</p>

### [Frostbite Audio Plugin](https://github.com/kudrekode/frostbite-audio-plugin)

A Windows x64 VST3 effect built with C++20 and JUCE for live and held granular textures, ping-pong echo, nonlinear damage and stereo ambience. Its real-time DSP avoids callback allocation, locks and I/O; V2 preserves existing presets and state while adding new factory sounds, with automated DSP, UI and VST3-host verification.

<img src="assets/frostbite/editor-v2.png" alt="Frostbite V2 audio plugin editor" width="100%" />

### [Companies House Enrichment Pipeline](https://github.com/kudrekode/ComapniesHouse)

An incremental Companies House ingestion and enrichment system designed for operational reliability: durable state, watermarks, replay-safe writes, run locking, cached officer data and a Postgres-backed enrichment worklist.

<img src="assets/companies-house/companies-house-demo.png" alt="Companies House enrichment dashboard" width="100%" />

### [Agentic Memory Orchestrator](https://github.com/kudrekode/agentic-memory-orchestrator)

Local long-term memory infrastructure for coding agents. An MCP service where agents propose memories while a deterministic server validates, deduplicates and persists semantic, episodic, working-state and procedural memory—with optional Obsidian sync.

```mermaid
flowchart TD
    A["Coding agent"] -->|"MCP · proposed memories"| B["Agent Memory service\nvalidation · transformation · conflict handling"]
    B --> C[("SQLite\nsource of truth")]
    C -->|"generated, read-only view"| D["Obsidian vault\noptional sync"]
```

**Python · MCP · SQLite · Obsidian · 115 tests**

### [Cauldron & Chance](https://github.com/kudrekode/quacks-game)

A deterministic strategy-game engine with seeded randomness, hidden-information handling and an information-set Monte Carlo AI opponent. Built around reproducibility, worker isolation and a well-tested rules engine.

<img src="assets/quacks-game/gameplay_example.png" alt="Cauldron and Chance gameplay" width="100%" />

## Elsewhere

I’m also experimenting with mobile and systems tooling in [RetroFeed](https://github.com/kudrekode/retrofeedApp), a SwiftUI client backed by a Rust/Axum API.

_When I’m not building, I’m usually playing guitar._
