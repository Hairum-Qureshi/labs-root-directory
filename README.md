# Root Repo Containing All Labs

A collection of 7 focused full-stack engineering labs designed to explore the building blocks behind modern AI applications.

Each lab is built around a single engineering question, with an interactive React frontend and a NestJS backend. The goal is to understand the underlying concepts rather than simply following tutorials or relying on high-level abstractions.

## Labs
### Lab 01 — LLM Fundamentals
**Link:** https://github.com/Hairum-Qureshi/lab-01-llm-fundamentals

**Engineering Question:**
How does my backend communicate with an LLM?

**Description:**
An interactive LLM playground exploring basic LLM API communication, prompt handling, streaming responses, structured outputs, and API error handling.

**Focus:**
LLM APIs · Streaming · Structured Output · Prompting · API Integration

**Status:** Completed

---

### Lab 02 — Agent Tool Calling
**Link:** TBD

**Engineering Question:**
How can an LLM decide when my application should perform an action?

**Description:**
An interactive application exploring tool/function calling, tool execution, agent loops, argument validation, and handling tool failures.

**Focus:**
Agents · Tool Calling · Function Schemas · Agent Loops

**Status:** Planned

---

### Lab 03 — Redis Cache Explorer
**Link:** TBD

**Engineering Question:**
When should an application avoid querying its database repeatedly?

**Description:**
An interactive caching playground demonstrating cache hits and misses, TTLs, invalidation, stale data, and cache performance.

**Focus:**
Redis · Caching · TTL · Invalidation · PostgreSQL · Docker

**Status:** Planned

---

### Lab 04 — RAG Explorer
**Link:** TBD

**Engineering Question:**
How can an AI application retrieve relevant knowledge without sending an entire knowledge base to the LLM?

**Description:**
An interactive RAG system exploring document ingestion, chunking, embeddings, vector search, retrieval parameters, and source citations.

**Focus:**
RAG · Embeddings · Vector Search · pgvector · Retrieval

**Status:** Planned

---

### Lab 05 — Background Job Queue
**Link:** TBD

**Engineering Question:**
What happens when work takes too long to perform inside an HTTP request?

**Description:**
An interactive job-processing system exploring asynchronous work, Redis-backed queues, workers, retries, progress tracking, and failure handling.

**Focus:**
Redis · BullMQ · Background Jobs · Workers · Retries · Async Processing

**Status:** Planned

---

### Lab 06 — Agent + RAG
**Link:** TBD

**Engineering Question:**
How can an agent decide when it needs external knowledge?

**Description:**
A combined agent and retrieval system exploring intelligent tool selection, knowledge retrieval, multi-step reasoning workflows, and tool failures.

**Focus:**
Agents · RAG · Tool Calling · Retrieval · Agent Loops

**Status:** Planned

---

### Lab 07 — Production AI System
**Link:** TBD

**Engineering Question:**
What changes when an AI application needs to operate like a real production system?

**Description:**
A productionization lab combining concepts from the previous labs with containerization, deployment, observability, resilience, and system monitoring.

**Focus:**
Docker · AWS · Observability · Resilience · Deployment · System Design

**Status:** Planned

---

## Learning Progression
The labs are intentionally ordered so that each one builds on concepts introduced previously.

```text
LLM Fundamentals
       ↓
Agent Tool Calling
       ↓
Redis & Caching
       ↓
RAG & Vector Search
       ↓
Background Jobs
       ↓
Agent + RAG
       ↓
Production AI System
```

The goal is not to complete every lab before building a larger application. Each lab is designed to answer one engineering question independently while gradually building the knowledge needed for a larger AI-powered full-stack project.

## Tech

### Existing

* React
* TypeScript
* NestJS

### Exploring

* LLM APIs
* Server-Sent Events (SSE) (i.e. text streaming)
* Structured Outputs
* Agent Tool Calling
* PostgreSQL
* Redis
* pgvector
* BullMQ
* Docker
* AWS
* RAG
* AI Observability

## Philosophy

These are **engineering labs, not tutorial projects**.

Each lab should:

* Answer one clearly defined engineering question
* Have an interactive frontend
* Be small enough to finish
* Expose the underlying mechanics of the technology
* Include deliberate experiments and failure cases
* Document important tradeoffs and lessons learned
* Avoid unnecessary abstractions

The objective is to understand **why** these systems work, not just how to assemble them.
