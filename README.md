<div align="center">

<pre>
┌──────────────────────────────────────────────────────────────┐
│ Kyle McCleary                                               │
│ Graduate AI Researcher @ LSU                                │
│ agent runtimes · retrieval systems · research tooling       │
└──────────────────────────────────────────────────────────────┘
</pre>

</div>

I build evidence-backed systems for agents, retrieval, and research.

The recurring pattern across most of my work is simple:

> make advanced systems easier to reason about by making their artifacts, traces, contracts, and evaluations explicit

That shows up in a few different forms:

- coding-agent runtimes with replay, harnessing, and multi-client surfaces
- retrieval and ingestion infrastructure for self-hosted AI systems
- streaming interfaces and runtime-facing developer tooling
- mechanism-level reproductions of recent papers

## Selected work

### Systems

- [`breadboard`](https://github.com/kmccleary3301/breadboard)  
  Programmable harness calculus for coding agents: replay, dossiers, runtime contracts, and one engine truth surface.

- [`QueryLake`](https://github.com/kmccleary3301/QueryLake)  
  Self-hosted AI platform spanning ingestion, retrieval, SDKs, toolchains, and studio/runtime surfaces.

- [`stream-mdx`](https://github.com/kmccleary3301/stream-mdx)  
  Streaming-first MDX renderer for React with worker-first parsing, deterministic snapshots, and benchmark tooling.

- [`candlecrawl`](https://github.com/kmccleary3301/candlecrawl)  
  Crawl, scrape, map, search, and extraction infrastructure for research-heavy systems.

- [`gpu_rl`](https://github.com/kmccleary3301/gpu_rl)  
  Artifact-first substrate for training and evaluating LLM-powered GPU code agents.

### Research

- [`nested_learning`](https://github.com/kmccleary3301/nested_learning)  
  Open reproduction of Google's Nested Learning / HOPE architecture.

- [`memory_caching`](https://github.com/kmccleary3301/memory_caching)  
  Runtime package and reproduction scaffold for Memory Caching.

- [`drift_models`](https://github.com/kmccleary3301/drift_models)  
  Installable reproduction of *Generative Modeling via Drifting*.

## What I optimize for

- explicit claim boundaries
- replayable systems
- benchmark contracts
- public artifacts over vague demos
- tooling that holds up under inspection
