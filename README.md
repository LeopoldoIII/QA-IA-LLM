# AI Quality, Evaluation & Agentic Automation Engineering
## The Complete Dual-Track Roadmap & Mastery Blueprint

> A hands-on, battle-tested learning curriculum, architecture guide, and portfolio blueprint designed to position you at the cutting edge of AI engineering:
> 1. **Track A: AI QA & Evaluation Engineer** (Evaluating non-deterministic systems, LLM evals, RAG, Playwright, LLM-as-a-Judge, LangSmith).
> 2. **Track B: AI Automation & Agentic Engineer** (Building production systems, LangGraph, Tool Use/Function Calling, MCP Servers, Webhooks, Integrations).

---

## 📑 Table of Contents
1. [Target Profiles & Strategic Positioning](#1-target-profiles--strategic-positioning)
2. [Skill Matrix: The Dual-Track Advantage](#2-skill-matrix-the-dual-track-advantage)
3. [Mastery Roadmap: 7-Phase Curriculum](#3-mastery-roadmap-7-phase-curriculum)
   - [Phase 1: Modern Test Automation & Mobile Testing](#phase-1-modern-test-automation--mobile-testing-weeks-1-3)
   - [Phase 2: LLM Fundamentals & Non-Deterministic Testing Core](#phase-2-llm-fundamentals--non-deterministic-testing-core-weeks-4-5)
   - [Phase 3: RAG Architecture & Vector Search Testing](#phase-3-rag-architecture--vector-search-testing-weeks-6-7)
   - [Phase 4: Agentic Systems, LangGraph & Tool Calling](#phase-4-agentic-systems-langgraph--tool-calling-weeks-8-10)
   - [Phase 5: Model Context Protocol (MCP) & Workflow Integrations](#phase-5-model-context-protocol-mcp--workflow-integrations-weeks-11-12)
   - [Phase 6: Eval Engineering, Observability & CI/CD Pipelines](#phase-6-eval-engineering-observability--cicd-pipelines-weeks-13-14)
   - [Phase 7: Portfolio Capstone, Rebranding & Interview Mastery](#phase-7-portfolio-capstone-rebranding--interview-mastery-weeks-15-16)
4. [Hands-On Portfolio Projects (Proof of Competence)](#4-hands-on-portfolio-projects-proof-of-competence)
5. [Validation Tools & Testing Playground Arsenal](#5-validation-tools--testing-playground-arsenal)
6. [Interview Playbook & Profile Selling Guide](#6-interview-playbook--profile-selling-guide)
7. [Tech Stack Reference & Command Cheat Sheet](#7-tech-stack-reference--command-cheat-sheet)

---

## 1. Target Profiles & Strategic Positioning

### The Two High-Demand AI Roles

```
               ┌────────────────────────────────────────────────────────┐
               │        THE DUAL-TRACK AI ENGINEER SUPERPOWER           │
               └────────────────────────────────────────────────────────┘
                                           │
                  ┌────────────────────────┴────────────────────────┐
                  ▼                                                 ▼
      [TRACK A: AI EVALUATOR]                           [TRACK B: AI BUILDER]
   AI QA & Evaluation Engineer                      AI Automation Engineer
   ───────────────────────────                      ──────────────────────
   • Measure quality & regressions                  • Build production agentic workflows
   • Quantify non-determinism                       • LangGraph, LangChain, State Machines
   • RAG Triad & Hallucination Evals                • Anthropic & OpenAI Tool Calling
   • Playwright E2E & Mobile validation             • MCP Server Integrations
   • Promptfoo, DeepEval, LangSmith                 • Webhooks, Figma, Google Workspace, CMS
```

### The Synergy
- **Traditional QA fails with AI** because treating an LLM as a "black box" makes it impossible to design nuanced evaluation rubrics or debug prompt drift.
- **AI Builders struggle in production** because agents take unpredictable actions, hallucinate, loop infinitely, or fail silently without structured evals and observability.
- **Your Edge**: Knowing how to **build** agents (LangGraph, MCP, Tool Calling) makes you an elite **Evaluator**; knowing how to **evaluate** makes your automated workflows resilient, enterprise-ready, and production-grade.

---

## 2. Skill Matrix: The Dual-Track Advantage

| Domain | Traditional QA Baseline | Track A: AI QA & Eval Engineer | Track B: AI Automation Engineer |
| :--- | :--- | :--- | :--- |
| **Automation Core** | Selenium, Cypress, Postman | **Playwright** (Web & Mobile emulation), API testing | **Python / Node.js** async workflows, REST APIs, Webhooks |
| **Model Interaction** | Basic manual prompting | Prompt regression testing, matrix evaluations | **Function Calling, Tool Use, JSON Schema, Streaming (SSE)** |
| **System Architecture** | Microservices, REST/GraphQL | **RAG evaluation (Context, Faithfulness, Relevance)** | **LangGraph StateGraphs, Memory, ReAct loops, Subgraphs** |
| **Ecosystem Protocols** | HTTP, gRPC, WebSocket | API assertions, contract testing | **MCP (Model Context Protocol) Servers & Clients** |
| **Quality Verification** | Binary pass/fail assertions | **LLM-as-a-Judge, Promptfoo, DeepEval, Golden Datasets** | Integration testing, fallback policies, human-in-the-loop gates |
| **Observability** | Datadog, Sentry, CloudWatch | **LangSmith, Arize Phoenix, Braintrust** | Tracing multi-step agent graphs, token costs, latency profiling |
| **SaaS Integrations** | Testing UI screens | E2E validation across multiple frontends | Connecting **WordPress, Figma, Google Docs, CMS** via APIs |

---

## 3. Mastery Roadmap: 7-Phase Curriculum

```
[Phase 1: Playwright & Mobile] ──► [Phase 2: LLM Non-Determinism] ──► [Phase 3: RAG Testing]
                                                                              │
                                                                              ▼
[Phase 6: Evals & CI/CD] ◄── [Phase 5: MCP & Integrations] ◄── [Phase 4: LangGraph & Agents]
         │
         ▼
[Phase 7: Portfolio & Rebranding]
```

---

### Phase 1: Modern Test Automation & Mobile Testing (Weeks 1–3)
**Goal**: Build industrial-grade web & mobile automation using Playwright, establishing modern testing foundations.

#### Key Topics
- **Playwright Architecture & Best Practices**:
  - Locators, Auto-waiting, Assertions, Fixtures, Page Object Model (POM).
  - API request context (`request.newContext()`) for hybrid API + UI automation.
  - Multi-tab testing, authentication states (`storageState.json`), network mocking (`page.route`).
- **Mobile Testing**:
  - Device emulation in Playwright (`devices['iPhone 14 Pro']`, `devices['Pixel 7']`).
  - Mobile web vs. hybrid vs. native testing paradigms.
  - Simulating touch gestures, orientation changes, network throttling (Slow 3G, offline).
- **AI-Assisted QA Workflows**:
  - Prompting Claude / ChatGPT to generate Playwright test cases from user stories.
  - Synthesizing edge-case test matrices with LLMs.

#### Hands-On Projects & Validation
1. Build an automated Playwright suite testing responsive mobile viewports for a web application.
2. Implement mock-based testing validating UI fallback states during network timeouts and 500 errors.

---

### Phase 2: LLM Fundamentals & Non-Deterministic Testing Core (Weeks 4–5)
**Goal**: Master the mechanics of language models, why they fail, and how to test probabilistic outputs.

#### Key Topics
- **Core Mechanics**:
  - Tokens, context windows, sampling parameters (`temperature`, `top_p`, `frequency_penalty`).
  - Structured outputs using Pydantic and JSON Schema.
  - Causes of non-determinism: sampling noise, floating-point variance, provider backend updates.
- **AI Failure Mode Taxonomy**:
  - **Hallucinations**: Intrinsic vs. extrinsic factual inaccuracies.
  - **Instruction Drift**: Model ignoring negative constraints, formatting rules, or role limits.
  - **Groundedness Failures**: Introducing facts not present in provided context documents.
  - **Adversarial Edge Cases**: Direct prompt injection, indirect prompt injection (via external data), jailbreaks.
- **Testing Probabilistic Systems**:
  - Shifting from single-run binary assertions to confidence intervals and sample variance.
  - Building and curating **Golden Datasets** (Ground Truth JSONL files).

#### Hands-On Projects & Validation
1. Experiment with `temperature` variance: run 50 identical queries at `0.0`, `0.5`, and `1.0` and measure semantic divergence using embeddings.
2. Build an adversarial security test suite verifying that system prompts resist direct override attempts.

---

### Phase 3: RAG Architecture & Vector Search Testing (Weeks 6–7)
**Goal**: Learn how Retrieval-Augmented Generation works under the hood and how to audit every stage.

#### Key Topics
- **The Retrieval Pipeline**:
  - Text chunking strategies (fixed size, recursive, semantic chunking) and overlap.
  - Embedding models & vector databases (ChromaDB, Pinecone, Qdrant).
  - Measuring retrieval quality: **Hit Rate** and **Mean Reciprocal Rank (MRR)**.
- **The Generation Pipeline**:
  - Prompt synthesis with context chunks.
  - Context window contamination and truncation.
- **The RAG Triad**:
  1. *Context Relevance*: Did the retriever pull relevant snippets?
  2. *Faithfulness (Groundedness)*: Is the answer strictly derived from the retrieved snippets?
  3. *Answer Relevance*: Does the answer satisfy the user query?

#### Hands-On Projects & Validation
1. Build a local Python RAG pipeline using ChromaDB and LiteLLM/OpenAI.
2. Write automated tests that measure retrieval accuracy on a set of 30 tricky domain queries.

---

### Phase 4: Agentic Systems, LangGraph & Tool Calling (Weeks 8–10)
**Goal**: Build production agentic workflows with LangGraph and master Tool Use / Function Calling.

#### Key Topics
- **Tool Use & Function Calling**:
  - Defining JSON schema tool definitions for OpenAI and Anthropic SDKs.
  - Handling multi-turn tool calling loops (LLM requests tool -> system executes -> returns tool result -> LLM synthesizes).
  - Streaming responses with tool execution.
- **LangGraph Architecture**:
  - `StateGraph`, nodes, edges, and conditional edges (`should_continue`).
  - Cycles, loops, and termination conditions (preventing infinite agent loops).
  - Short-term & long-term memory (`MemorySaver` checkpointers).
  - Human-in-the-Loop (interrupting execution for human approval before critical actions).
- **Agent Testing & Edge Cases**:
  - Testing tool parameter errors (invalid inputs, missing keys).
  - Loop limit enforcement (recursion limits).
  - Simulating external API tool failures and validating graceful retries.

#### Hands-On Projects & Validation
1. Build a **LangGraph Customer Operations Agent** that can search order databases, calculate refunds, and draft responses.
2. Write automated tests validating that the agent correctly invokes tools only when necessary and handles simulated tool outages without crashing.

---

### Phase 5: Model Context Protocol (MCP) & Workflow Integrations (Weeks 11–12)
**Goal**: Master Anthropic's open standard (MCP), building servers and integrating external business workflows.

#### Key Topics
- **Model Context Protocol (MCP)**:
  - Architecture: MCP Hosts (Claude Desktop, IDEs), MCP Clients, MCP Servers.
  - Three Core Primitives:
    1. *Resources*: Exposing files, database rows, or documents like REST endpoints.
    2. *Tools*: Exposing executable functions (with schemas) for LLM invocation.
    3. *Prompts*: Exposing pre-configured prompt templates.
  - Transports: Stdio vs. SSE (Server-Sent Events).
- **Workflow Integrations**:
  - Connecting Python/Node.js agents to external APIs (Google Workspace, Figma REST API, WordPress REST API, CMS).
  - Designing webhook receivers that trigger agentic pipelines on business events.
  - Secret management, retry mechanisms, and rate-limiting.

#### Hands-On Projects & Validation
1. Build a **Custom MCP Server** in TypeScript or Python exposing access to a local SQLite database or CMS API.
2. Inspect and validate your MCP server using `@modelcontextprotocol/inspector`.
3. Connect the MCP server to Claude Desktop and verify autonomous tool execution.

---

### Phase 6: Eval Engineering, Observability & CI/CD Pipelines (Weeks 13–14)
**Goal**: Industrialize quality validation by implementing automated eval suites in CI/CD with full observability.

#### Key Topics
- **Evaluation Frameworks**:
  - **Promptfoo**: Declarative YAML testing (`promptfooconfig.yaml`), assertions (`llm-rubric`, `contains`, `similar`, `factuality`), red-teaming.
  - **DeepEval / Ragas**: G-Eval framework, RAG Triad automated scoring, pytest integration.
  - **LLM-as-a-Judge**: Mitigating position bias, verbosity bias, and self-preference bias.
- **LLM Observability & Tracing**:
  - **LangSmith / Arize Phoenix**: Tracing nested agent chains, latency bottlenecks, token consumption.
  - Curation of failure traces from production into regression test suites.
- **CI/CD Regression Gates**:
  - Running Promptfoo / DeepEval inside GitHub Actions.
  - Blocking Pull Requests if hallucination score increases or rubric score drops below `0.85`.

#### Hands-On Projects & Validation
1. Instrument an agent with LangSmith or Phoenix, logging every tool call, latency, and token cost.
2. Create a GitHub Actions workflow that executes an eval suite on every commit, generating markdown summary PR comments.

---

### Phase 7: Portfolio Capstone, Rebranding & Interview Mastery (Weeks 15–16)
**Goal**: Package your open-source projects, rebrand your CV/LinkedIn for both tracks, and ace interviews.

#### Deliverables
1. Complete 3 showcase repositories with clear architecture diagrams, runnable tests, and CI/CD status badges.
2. Write a technical article or LinkedIn case study: *"How I Built and Tested an Autonomous Agent using LangGraph, MCP, and Promptfoo Evals"*.
3. Execute mock interviews using the questions in [Section 6](#6-interview-playbook--profile-selling-guide).

---

## 4. Hands-On Portfolio Projects (Proof of Competence)

These 5 portfolio projects provide concrete proof for both the **AI QA & Eval Engineer** and **AI Automation Engineer** roles:

### 🌟 Project 1: Automated RAG Eval Pipeline with DeepEval & CI/CD (Evaluator Track)
- **Goal**: Measure and eliminate hallucinations in a production-grade RAG pipeline.
- **Stack**: Python, DeepEval, ChromaDB, OpenAI/Claude API, Pytest, GitHub Actions.
- **Deliverables**:
  - 100+ sample Golden Dataset across domain edge cases.
  - Automated RAG Triad scores (*Contextual Relevancy*, *Faithfulness*, *Answer Relevancy*).
  - GitHub Actions gate blocking PR merges if quality drops below 85%.

### 🌟 Project 2: Multi-Agent Production Workflow with LangGraph & Tool Calling (Builder Track)
- **Goal**: Autonomous operations assistant connecting multiple business APIs with human approval.
- **Stack**: Python, LangGraph, Anthropic Claude 3.5 Sonnet, Pydantic, SQLite checkpointer.
- **Deliverables**:
  - `StateGraph` containing ReAct agent, tool node, and conditional routing.
  - Simulated integrations: Google Workspace email sender, order lookup API, refund processor.
  - Human-in-the-loop checkpoint requiring operator confirmation for actions over $50.

### 🌟 Project 3: Production Model Context Protocol (MCP) Server (Builder Track)
- **Goal**: Expose enterprise CMS & file assets to AI models via the open MCP standard.
- **Stack**: TypeScript / Python, `@modelcontextprotocol/sdk`, SQLite/Mock CMS.
- **Deliverables**:
  - Implements MCP Tools, Resources, and Prompts.
  - Fully tested using `@modelcontextprotocol/inspector`.
  - Connects seamlessly into Claude Desktop or custom LangGraph MCP clients.

### 🌟 Project 4: AI Agent E2E & Red-Teaming Test Suite with Playwright + Promptfoo (Evaluator Track)
- **Goal**: Test customer-facing AI chat widgets on both desktop and mobile viewports with adversarial attacks.
- **Stack**: Playwright (TypeScript), Promptfoo, Node.js.
- **Deliverables**:
  - E2E Playwright tests verifying UI rendering, streaming animations, and mobile layout.
  - Promptfoo matrix testing 50 prompt injection, jailbreak, and system extraction attacks.
  - Latency and token consumption regression reporting.

### 🌟 Project 5: Production Observability & Automated Regression Engine (Full-Stack Track)
- **Goal**: Automatically convert production edge-case failures into automated regression tests.
- **Stack**: LangSmith / Arize Phoenix, Python, Pytest.
- **Deliverables**:
  - Telemetry pipeline capturing user thumbs-down ratings or low-confidence traces.
  - Pipeline script exporting flagged traces directly into a Golden Dataset JSONL.
  - Prevents recurrence of known production bugs in future model releases.

---

## 5. Validation Tools & Testing Playground Arsenal

Use these tools to validate, inspect, and benchmark your agents and evaluations:

| Tool | Category | What It Does & How to Validate |
| :--- | :--- | :--- |
| **Promptfoo** | Evals & Security | Fast CLI tool to test prompts, LLM-as-a-Judge rubrics, and automated red-teaming. |
| **DeepEval** | Metric Framework | Unit testing framework for LLMs (Pytest-style) with RAG Triad, G-Eval, and Hallucination metrics. |
| **MCP Inspector** | Protocol Validation | Web UI (`npx @modelcontextprotocol/inspector`) to test MCP server tools, resources, and schemas. |
| **LangSmith** | Tracing & Observability | Inspects multi-node agent traces, token costs, latency bottlenecks, and dataset runs. |
| **Arize Phoenix** | Open-Source Tracing | Self-hosted observability for tracing agent steps, embeddings, and RAG retrieval evaluations. |
| **Anthropic Workbench** | Prompt Engineering | Test Claude system prompts, structured tool use schemas, and temperature variations. |
| **OpenAI Playground** | Tool Calling Playground | Test Assistant tool calling, JSON schema outputs, and multi-turn message states. |
| **Playwright Test Runner** | E2E & Mobile Automation | Validates frontends, streaming rendering, network mocks, and mobile device viewports. |
| **Prism / Mockoon** | API Mocking | Mock external REST APIs (WordPress, CMS, Google) with predictable responses for agent tests. |
| **ngrok** | Webhook Debugging | Expose local agent webhook listeners to receive live events from external services. |

---

## 6. Interview Playbook & Profile Selling Guide

### How to Rebrand Your Resume & LinkedIn

#### 1. Professional Title & Headline
- **Option 1 (Evaluator Focus)**: *AI QA & Evaluation Engineer | Test Automation (Playwright) & LLM Evals (RAG, Agents, Promptfoo)*
- **Option 2 (Builder Focus)**: *AI Automation Engineer | Agentic Workflows (LangGraph, MCP, Tool Calling) & LLM Systems*
- **Option 3 (Hybrid Leader)**: *AI Systems & Evaluation Engineer | LangGraph Agents, MCP Integrations & Automated Evals*

#### 2. Summary Statement
> *"Automation and Quality Engineer with 3+ years of experience building and evaluating production AI systems. Hands-on expertise building agentic workflows with LangGraph, tool use/function calling, and MCP servers, as well as architecting automated evaluation pipelines (Promptfoo, DeepEval, Playwright) to eliminate hallucinations, measure RAG quality, and prevent behavioral regressions in CI/CD."*

#### 3. Transforming Resume Bullet Points
| Before (Traditional) | After (AI Positioned) |
| :--- | :--- |
| "Created Playwright automation scripts for web applications." | "Architected automated E2E test suites with Playwright across desktop and mobile viewports, integrating LLM output evaluations to validate non-deterministic features in CI/CD." |
| "Built Python scripts to automate internal processes." | "Engineered agentic automation pipelines with LangGraph and Anthropic Tool Use, connecting CMS, Figma, and Google Workspace to automate 20+ hours of weekly manual operations." |
| "Performed manual API testing with Postman." | "Developed a custom Model Context Protocol (MCP) server exposing internal APIs and database tools to autonomous agent runtimes with strict JSON Schema validation." |
| "Logged and managed bugs in Jira." | "Defined AI failure taxonomies (hallucinations, instruction drift, grounding failures), curating a 200+ sample golden dataset that decreased regression rates by 35%." |

---

### Key Technical Interview Questions & Model Answers

#### Q1: "How do you test a non-deterministic LLM or Agent?"
> *"I use a layered validation strategy:
> 1. **Deterministic Layer**: Enforce schema structure (JSON schema, Pydantic), HTTP codes, latency ceilings, and token budgets.
> 2. **Semantic / Embedding Layer**: Compute cosine distance against expected semantic anchors.
> 3. **Model-Graded Evals (LLM-as-a-Judge)**: Run structured rubrics (DeepEval / Promptfoo) to assess criteria like faithfulness, answer relevance, and safety.
> 4. **Statistical Confidence**: Execute test batches across temperature settings to quantify variance and establish threshold confidence intervals."*

#### Q2: "What is an MCP Server and why does it matter?"
> *"The Model Context Protocol (MCP) is an open standard introduced by Anthropic that decouples LLMs from specific API integrations. Instead of hardcoding custom API wrappers for every LLM or client, an MCP server provides standardized **Resources** (data/files), **Tools** (functions the model can execute), and **Prompts**. This allows any compatible host—such as Claude Desktop, an IDE, or a custom agent—to securely discover and invoke tools with standard typing."*

#### Q3: "How does LangGraph differ from standard LangChain chains?"
> *"Standard LangChain chains are directed acyclic graphs (DAGs) designed for linear sequence execution. Real-world autonomous agents require **cyclical graphs, persistence, and state machines**. LangGraph introduces `StateGraph`, enabling agents to loop, self-correct after tool errors, maintain checkpoints across multi-turn sessions, and support **Human-in-the-Loop** interrupts before destructive actions."*

#### Q4: "How do you test and prevent infinite loops in AI agents?"
> *"First, configure strict execution recursion limits in the agent graph (e.g., `recursion_limit=15`). Second, write automated unit tests that simulate failing or ambiguous tool outputs to verify that the agent's conditional routing terminates gracefully with an explanatory message rather than re-querying indefinitely. Third, monitor cycles in production via LangSmith trace graphs."*

---

## 7. Tech Stack Reference & Command Cheat Sheet

### Quick Start Commands

#### 1. Setup Playwright (Web & Mobile Automation)
```bash
npm init playwright@latest
npx playwright test --project="Mobile Safari"
```

#### 2. Setup Promptfoo (Automated Evals & Red-Teaming)
```bash
npx promptfoo@latest init
npx promptfoo@latest eval
npx promptfoo@latest view
```

#### 3. Setup DeepEval (Python LLM Unit Testing)
```bash
pip install deepeval
deepeval test run test_rag_eval.py
```

#### 4. Inspect an MCP Server
```bash
npx @modelcontextprotocol/inspector npx -y @modelcontextprotocol/server-everything
```

#### 5. Setup LangGraph Environment
```bash
pip install langgraph langchain-anthropic langchain-openai
```

---

## 📅 Suggested Weekly Study Schedule

- **Weeks 1–3**: Playwright masterclass (POM, API testing, mobile emulation) + Claude prompt engineering for QA.
- **Weeks 4–5**: LLM mechanics, non-determinism, failure taxonomies, golden dataset curation.
- **Weeks 6–7**: RAG architectures, chunking, vector search, RAG Triad evals (DeepEval/Ragas).
- **Weeks 8–10**: LangGraph state machines, Anthropic/OpenAI Tool Calling, ReAct agent loops.
- **Weeks 11–12**: MCP servers, REST APIs, Webhook pipelines (Google Workspace, Figma, CMS).
- **Weeks 13–14**: Promptfoo regression testing, LangSmith/Phoenix observability, CI/CD GitHub Actions.
- **Weeks 15–16**: Capstone project polish, LinkedIn/CV rebranding, interview mock sessions.
