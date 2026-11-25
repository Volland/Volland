# Hey, I'm Volodymyr 👋

**23+ years building software — from COBOL and Smalltalk to Rust, Agentic Memory, and Sovereign AI**

I work on **agentic memory architectures**, **world models for AI agents**, and **secure/sovereign agents** — all grounded in embedded graph databases and edge-first, privacy-first principles.


---

### 🧠 Current Focus

- **Agentic Memory** — Multi-layered memory architectures (episodic, semantic, procedural) built on knowledge graphs. Cognitive extraction-consolidation pipelines. Memory that supports causal reasoning, not just retrieval
- **World Models for AI Agents** — Structured representations of the environment an agent reasons about to make decisions
- **Secure & Sovereign Agents** — Self-sovereign identity (DIDs, KERI, Verifiable Credentials), agent-owned credentials, trust without centralized authority
- **Edge AI & Embedded Graphs** — Local-first, privacy-first. Graph databases that ship as a single file and run in-process. No server, no network hop, no data leaving the device

### 🐞 Projects

- **[oxilite](https://github.com/Volland/oxilite)** — Oxigraph-compatible RDF database and SPARQL 1.1 engine that runs on plain SQLite instead of RocksDB, including Cloudflare D1 — same data model, same SPARQL semantics, same Rust API, with a compiled SPARQL→SQL planner, RDFS/OWL reasoning, SHACL/ShEx validation, and openCypher over the same data. Dual MIT/Apache-2.0 — [oxilitedb.com](https://oxilitedb.com) · [crates.io](https://crates.io/crates/oxilite) · [source on GitHub](https://github.com/Volland/oxilite)
- **[oxilite studio](https://github.com/Volland/oxilite-studio)** — VS Code development studio for oxilite: live SPARQL, Datalog and Cypher with completion and go-to-definition, RDFS/OWL reasoning with proof explanations, SHACL/ShEx validation in the Problems panel, a store explorer, notebooks, and an MCP server for agents. Dual MIT/Apache-2.0 — [source on GitHub](https://github.com/Volland/oxilite-studio)
- **[Factum](https://www.factum-orm.com/)** — Object-Role Modeling (ORM 2) as a VS Code extension. Draw a conceptual schema, read it back as plain-language sentences a domain expert can confirm, and map it to relational (SQL) or property graph (LadybugDB) schemas. Ships an MCP server (`factum-mcp`) and a CLI (`validate`, `verbalize`, `diff`, `drift`, `derive`) so coding agents read the conceptual model instead of guessing it from column names. MIT licensed — [source on GitHub](https://github.com/Volland/factum-orm)
- **[LPG Modeler](https://www.lpg-modeler.com/)** — VS Code extension for labeled property graph schemas. Author one YAML model on a canvas (with proper inheritance vs. mixins) and generate LadybugDB DDL, Neo4j constraints, SHACL shapes, and an OWL ontology from it — with everything a target can't enforce reported as a diagnostic instead of silently dropped. Checkable in CI. MIT licensed — [source on GitHub](https://github.com/Volland/lpg-modeler)
- **[Causal Canvas](https://www.casualcanvas.org/)** — Visual editor for causal models (DAGs, ADMGs, PAGs, causal loop diagrams) backed by a JSON-native format (CausalJSON) and a CLI. Includes a causal linter that catches collider adjustment, invalid instruments, and unidentifiable latents, plus reproducible SVG/PDF figure generation for CI. Fully local, no telemetry. Apache-2.0 — [source on GitHub](https://github.com/Volland/causal-canvas)
- **[Hybrid Graph RAG (Rust)](https://github.com/Volland/ladybug-rag-rs)** — Four retrieval modes in one query: vector search + graph traversal + PageRank + community detection. +109% on multi-hop questions vs vector-only RAG
- **[Hybrid Graph RAG (Python)](https://github.com/Volland/ladybug-rag)** — Reference implementation of Hybrid GraphRAG with LadybugDB
- **[tiramemsu](https://github.com/Volland/tiramemsu)** — Bitemporal statement-graph store on redb and SQLite: statements carry transaction and valid time, with vectors and reasoning on board, for agent memory that knows when a fact was true and when it was recorded. Apache-2.0 — [tiramemsu.com](https://tiramemsu.com)
- **[LeanRDF](https://github.com/Volland/rdf-lean)** — Native RDF 1.1 model and entailment semantics in Lean 4, with Elpi search and a verified certificate checker. Apache-2.0
- **[lean-elpi](https://github.com/Volland/lean-elpi)** — λProlog (Elpi) inside Lean 4: write tactics, commands and proof search as logic programs, share types with Lean both ways, and get kernel-checked proofs. Apache-2.0
- **[typedb-lean](https://github.com/Volland/typedb-lean)** — TypeDB 3 client for Lean 4: compile-time checked transactions, typed TypeQL, batched decoding, a lightweight ORM and migrations. Apache-2.0
- **[agent.lean](https://github.com/Volland/agent.lean)** — Tiny, verifiable agent library in Lean 4 that compiles to C: LLM agents with tools and provable policies for embedded Linux, iOS and Android. Apache-2.0
- **[Typed Graph](https://github.com/Volland/typedgraph)** — Obsidian plugin for a typed, signed, labeled property graph: openCypher queries, edge properties, LadybugDB mirror, vector search, GraphRAG and an MCP server. MIT licensed — [typedgraph.org](https://typedgraph.org)

### 📚 Books

I write the *Age AI* book series on [Leanpub](https://leanpub.com/u/vpavlyshyn):

| | |
|---|---|
| 🌍 [World Models for AI Agents](https://leanpub.com/agenticworldmodels) | 🐞 [LadybugDB for Edge Agent AI Memory](https://leanpub.com/ladybugdb) |
| 🦆 [GraphDuck: DuckDB for Embedded AI Agents and Graphs](https://leanpub.com/graphduck) | 🔗 [Beyond Context Graphs: Agentic Memory, Cognitive Processes, and Promise Graphs](https://leanpub.com/beyondcontextgraphs) |
| ⏳ [Semantic Space Time for AI Agent Ready Graphs](https://leanpub.com/sst-4-agenticai) | 🕰️ [Temporal Aware AI Memory](https://leanpub.com/time-aware-ai-memory) |
| 📱 [Edge AI: Pocket Knowledge Graphs on User Device](https://leanpub.com/edgeai-pocket-knowledgegraphs-on-user-device) | 🧠 [AI Agents Memory Empowered by Knowledge Graphs](https://leanpub.com/ai-agents-memory) |
| 🔐 [Sovereign AI Agents](https://leanpub.com/sovereign-ai-agents) *(in progress)* | 🧮 [Dependent Types & Logic for AI Agent Ready Knowledge Graphs](https://leanpub.com/dependenttypesdttlogicholforaiagentreadyknowledgegraphs) |
| 🗡️ [Cypher 103 with LadybugDB](https://leanpub.com/cypher103withladybugdb) | 🔮 [Metagraph for AI Agents](https://leanpub.com/metagraphforaiagents) |
| 💾 [TypeDB for Edge AI Agents](https://leanpub.com/typedbforedgeaiagents) | 🤔 [Philosophical Wednesdays with AI Powered Architect](https://leanpub.com/philosophical-wednesdays-with-ai-powered-architect) |
| 📐 [Fact-Based Agents](https://leanpub.com/fact-basedagents) — why coding agents reconstruct your domain from schemas and code, and what an ORM 2 conceptual schema gives them instead | |

🇺🇦 I also write a Ukrainian children's book series: [Макс, Цугі і світло, яке чутно](https://leanpub.com/max-tsugi-and-old-radio)

### 🛠️ Tech Stack

**Primary:** Rust, TypeScript, React, JavaScript, Lean 4  
**JVM:** Kotlin, Scala, Java, Clojure  
**Systems & Crypto:** Rust, Zig, C  
**Formative:** Smalltalk (Pharo, Cuis, Self), COBOL — these shaped how I think about objects, agents, and message-passing

### 📝 Writing & Content

- [Substack — Sovereign Agentic AI](https://volodymyrpavlyshyn.substack.com/) — deep dives on agentic memory, world models, LadybugDB, Hybrid RAG
- [Medium](https://medium.com/@volodymyrpavlyshyn) — technical articles
- [YouTube](https://www.youtube.com/c/VolodymyrPavlyshyn) — video content

### 🌐 Find Me
[🌐 https://www.pavlyshyn.me](https://www.pavlyshyn.me)


[![LinkedIn](https://img.shields.io/badge/LinkedIn-pavlyshyn-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/pavlyshyn/)
[![YouTube](https://img.shields.io/badge/YouTube-Volodymyr_Pavlyshyn-red?style=flat&logo=youtube)](https://www.youtube.com/c/VolodymyrPavlyshyn)
[![Substack](https://img.shields.io/badge/Substack-Sovereign_Agentic_AI-orange?style=flat&logo=substack)](https://volodymyrpavlyshyn.substack.com/)
[![Medium](https://img.shields.io/badge/Medium-@volodymyrpavlyshyn-black?style=flat&logo=medium)](https://medium.com/@volodymyrpavlyshyn)
[![Mastodon](https://img.shields.io/badge/Mastodon-@vpavlyshyn-purple?style=flat&logo=mastodon)](https://fosstodon.org/deck/@vpavlyshyn)
[![MakerTube](https://img.shields.io/badge/MakerTube-SSI_Tea_Talks-green?style=flat)](https://makertube.net/c/ssiteatalks/videos)

**Nostr:** `npub1u6qhg5ucu3xza4nlz94q90y720tr6l09avnq8y3yfp5qrv9v8sus3tnd7t`

---

*The next generation of AI will not simply compute. It will remember.*
