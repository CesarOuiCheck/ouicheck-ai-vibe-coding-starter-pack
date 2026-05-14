# 01 — Initial Setup
## Objective
Help builders create the minimum viable AI-native development environment required to build scalable AI-assisted applications.
This module is designed especially for:
- non-technical builders
- founders
- consultants
- workshop participants
- AI-native teams
- innovation units
The goal is not simply to install tools.
The goal is to create a development environment that:
- remains maintainable,
- avoids architectural chaos,
- supports AI orchestration,
- and can evolve into production-grade systems.
---
# Recommended Starter Stack
Example stack used throughout this repository:
```text
VS Code
+
OpenAI Codex
+
ChromaDB
+
OpenAI APIs

This stack is intentionally simple while remaining powerful enough to support:

* retrieval systems,
* AI workflows,
* orchestration layers,
* prompt systems,
* and scalable experimentation.

⸻

Core Components

1. IDE / Development Environment

Recommended:

* Visual Studio Code
* Cursor

Purpose:

* code editing
* AI-assisted development
* debugging
* Git integration
* extension ecosystem

⸻

2. AI Coding Layer

Recommended:

* OpenAI Codex
* Claude
* Cursor Agent

Purpose:

* code generation
* architecture reviews
* workflow decomposition
* debugging assistance
* documentation generation

Important:
AI coding systems should assist architecture — not replace architectural thinking.

⸻

3. AI Models & APIs

Recommended:

* OpenAI API

Optional:

* Anthropic API
* local models
* open-source inference APIs

Purpose:

* inference
* embeddings
* orchestration
* structured outputs
* retrieval pipelines

⸻

4. Vector Database / Retrieval Layer

Recommended:

* ChromaDB

Purpose:

* embeddings storage
* retrieval-augmented generation (RAG)
* knowledge management
* semantic search

Important:
Most retrieval systems fail because governance and reindexing strategies are missing.

⸻

5. Version Control

Recommended:

* GitHub

Purpose:

* versioning
* collaboration
* rollback
* deployment workflows
* documentation

⸻

Minimum Setup Checklist

Accounts

* GitHub
* OpenAI
* IDE installed

Installed Tools

* VS Code
* Git
* Python
* ChromaDB
* API clients

Environment

* API keys configured
* virtual environment configured
* .env protected
* repository initialized

⸻

First Principle

Do not start by coding features.

Start by:

1. understanding workflows,
2. defining architecture,
3. setting governance,
4. and creating operational visibility.

This repository exists to support that transition.

---
# 4. Commit
Commit message:
```text id="l5iz7j"
Add Initial Setup module
