# 🦜🕸️ Awesome LangGraph & LangChain Ecosystem ![Awesome](https://awesome.re/badge.svg) ![Last Updated](https://img.shields.io/github/last-commit/von-development/awesome-LangGraph)

> The definitive index of frameworks, templates, and real-world projects for teams that want to **build, observe, evaluate, and deploy** stateful, tool-using AI agents with the LangChain + LangGraph stack.

Whether you’re prototyping your first workflow or operating production systems, this list maps the full lifecycle of agent development, from **building** with core libraries and integrations, to **observing** runs with platform tooling, **evaluating** quality and behavior, and **deploying** reliable agent applications.

**What you’ll find**
- Core frameworks: LangChain, LangGraph, Deep Agents, and LangSmith
- Resources for building, observing, evaluating, and deploying agent systems
- Integrations & MCP tooling across models, vector stores, loaders, and tools
- Official LangChain/LangGraph projects and prebuilt agent libraries
- Community projects grouped by use case (RAG, web automation, research, finance, etc.)
- Starter templates and learning resources to get productive fast


Contributions welcome—see the [Contributing Guide](CONTRIBUTING.md).

---

## Table of Contents

- [🦜🕸️ Awesome LangGraph \& LangChain Ecosystem  ](#️-awesome-langgraph--langchain-ecosystem--)
  - [Table of Contents](#table-of-contents)
  - [🌐 What is the LangChain/Graph Ecosystem](#-what-is-the-langchaingraph-ecosystem)
    - [Ecosystem Components:](#ecosystem-components)
  - [🦜 LangChain 🔗](#-langchain-)
    - [Core Components](#core-components)
    - [Advanced Usage](#advanced-usage)
    - [LangChain Documentation and llms.txt Files](#-langchain-documentation-and-llmstxt-files-️)
  - [🦜 LangGraph 🕸️](#-langgraph-️)
    - [LangGraph Documentation and llms.txt Files](#-langgraph-documentation-and-llmstxt-files-️)
  - [🧠 Deep Agents](#-deep-agents)
    - [Core Capabilities](#core-capabilities)
    - [Deep Agents SDK and CLI](#-deep-agents-sdk-and-cli-️)
    - [Deep Agents Documentation and llms.txt Files](#-deep-agents-documentation-and-llmstxt-files-️)
  - [🦜 LangSmith 🛠️](#-langsmith-️)
    - [LangSmith Documentation and llms.txt Files](#-langsmith-documentation-and-llmstxt-files-️)
  - [🧩 LangSmith Fleet](#-langsmith-fleet)
  - [🦜 LangChain Integrations \& Partners 🤝](#-langchain-integrations--partners-)
  - [🟢 Official LangGraph Projects 🦜](#-official-langgraph-projects-)
    - [🟩 Specialized Agent Libraries 🤖](#-specialized-agent-libraries-)
    - [🟩 Apps \& Agents 📱](#-apps--agents-)
    - [🟩 Development Tools 🛠️](#-development-tools-️)
- [🌟 Community Projects](#-community-projects)
  - [🧬 Bio \& Health](#-bio--health)
  - [🌐 Web Automation \& Scraping](#-web-automation--scraping)
  - [📊 Business Intelligence \& Market Research](#-business-intelligence--market-research)
  - [🖥️ Chat Interfaces \& GUIs](#️-chat-interfaces--guis)
  - [☁️ Cloud \& DevOps](#️-cloud--devops)
  - [🤖 Coding/Dev Agents](#-codingdev-agents)
  - [🛎️ Customer Ops](#️-customer-ops)
  - [📊 Data Platforms](#-data-platforms)
  - [🧮 Data Science](#-data-science)
  - [🛠️ Developer Tools](#️-developer-tools)
  - [💰 Finance \& Fintech](#-finance--fintech)
  - [🎯 Marketing](#-marketing)
  - [🎥 Media \& Podcasts](#-media--podcasts)
  - [🤖 Robotics \& Embodied AI](#-robotics--embodied-ai)
  - [📚 RAG \& Document Processing](#-rag--document-processing)
  - [🔬 Research Agents](#-research-agents)
  - [🌍 Sustainability](#-sustainability)
  - [📋 Templates \& Starters](#-templates--starters)
  - [🏢 Workplace \& Productivity](#-workplace--productivity)
  - [📚 Learning Resources](#-learning-resources)
    - [Official — LangGraph Academy](#official--langgraph-academy)
    - [Community Courses](#community-courses)
  - [📖 Additional Resources](#-additional-resources)
  - [👥 Communities](#-communities)
  - [🤝 Contributing](#-contributing)
  - [🙏 Acknowledgments](#-acknowledgments)




<div align="center">

---

</div>

<div align="center">

## 🌐 What is the LangChain/Graph Ecosystem

</div>

The **LangChain/Graph Ecosystem** is a comprehensive suite of frameworks and platforms for building, deploying, and managing LLM-powered applications. While **LangGraph** can be used standalone, it integrates seamlessly with any LangChain product, giving developers a full suite of tools for building agents.

<div align="center">
  <img src="static/langchain_overview.png" width="500" alt="LangChain Ecosystem Overview">
  <p><sub>Source: <a href="https://python.langchain.com/docs/introduction/">LangChain Documentation</a></sub></p>
</div>

### Ecosystem Components:

**🔗 LangChain** - Provides integrations and composable components to streamline LLM application development. Contains agent abstractions built on top of LangGraph.

**🕸️ LangGraph** - The core framework for building stateful, multi-agent systems with complex workflows, collaboration, and memory management.

**🧠 Deep Agents** - An agent harness for building agents that can plan, decompose complex tasks, use subagents, manage large context with filesystem tools, and persist long-term memory.

**🛠️ LangSmith** - The platform layer for observing, evaluating, and deploying AI agents and LLM applications with tracing, prompt engineering, Agent Server deployment, sandboxes, and operational tooling.

**🧩 LangSmith Fleet** - A no-code platform for creating and managing AI agents from templates, connecting apps and accounts, automating routine work, and keeping humans in control with approvals and oversight.

**🤝 LangChain Integrations & Partners** - Third-party integrations and provider packages that extend LangChain's capabilities across the AI ecosystem. These integration packages provide standardized interfaces to work with popular AI services, databases, and tools.



---

<div align="center">

## 🦜 LangChain 🔗

</div> 


**LangChain** is the foundational framework for building applications with Large Language Models (LLMs). It provides standardized interfaces, reusable components, and extensive integrations that enable developers to create sophisticated AI applications through composable building blocks.



<details>
<summary><strong>▫️ Core Components and Usage ▫️</strong></summary>

**Essential building blocks and advanced capabilities for LangChain applications** - from fundamental components to sophisticated AI features.

### Core Components
*Essential building blocks for LangChain applications*

| Component | Description |
|-----------|-------------|
| **🤖 [Agents](https://docs.langchain.com/oss/python/langchain/agents)** | Decision-making systems that use LLMs to determine which actions to take |
| **🧠 [Models](https://docs.langchain.com/oss/python/langchain/models)** | Unified interfaces for LLMs and embedding models across providers |
| **💬 [Messages](https://docs.langchain.com/oss/python/langchain/messages)** | Structured communication format between components |
| **🛠️ [Tools](https://docs.langchain.com/oss/python/langchain/tools)** | External function calls and integrations for agents |
| **🧭 [Short-term Memory](https://docs.langchain.com/oss/python/langchain/short-term-memory)** | Working memory for maintaining conversation context |
| **⚡ [Streaming](https://docs.langchain.com/oss/python/langchain/streaming)** | Real-time response processing for partial results |

### Advanced Usage
*Advanced capabilities and techniques for sophisticated AI applications*

| Feature | Description |
|---------|-------------|
| **🧠 [Long-term Memory](https://docs.langchain.com/oss/python/langchain/long-term-memory)** | Persistent memory that survives across sessions |
| **🛡️ [Guardrails](https://docs.langchain.com/oss/python/langchain/guardrails)** | Safety checks and policy enforcement for agent inputs, outputs, and tool usage |
| **🎯 [Context Engineering](https://docs.langchain.com/oss/python/langchain/context-engineering)** | Techniques for optimizing prompts and context management |
| **📋 [Structured Output](https://docs.langchain.com/oss/python/langchain/structured-output)** | Generate responses in specific formats and schemas |
| **🔗 [Model Context Protocol](https://docs.langchain.com/oss/python/langchain/mcp)** | Standardized tool integration and context sharing |
| **👥 [Human-in-the-Loop](https://docs.langchain.com/oss/python/langchain/human-in-the-loop)** | Approval workflows and interrupt-based human oversight for sensitive agent actions |
| **🤝 [Multi-agent](https://docs.langchain.com/oss/python/langchain/multi-agent)** | Coordinated systems with multiple AI agents |
| **🔍 [Retrieval](https://docs.langchain.com/oss/python/langchain/retrieval)** | Advanced document retrieval and RAG patterns |
| **⚙️ [Runtime](https://docs.langchain.com/oss/python/langchain/runtime)** | Production deployment and runtime management |
| **🔧 [Middleware](https://docs.langchain.com/oss/python/langchain/middleware)** | Custom processing layers and request/response modification |

</details>

<details>
<summary><strong>▫️ LangChain Libraries ▫️</strong></summary>


| Package | Python | TypeScript | Description |
|---------|--------|------------|-------------|
| **LangChain** | [`langchain`](https://github.com/langchain-ai/langchain/tree/master/libs/langchain) | [`langchain`](https://github.com/langchain-ai/langchainjs/tree/main/langchain) | Main framework with chains, agents, retrieval methods, and cognitive architecture |
| **LangChain Core** | [`langchain-core`](https://github.com/langchain-ai/langchain/tree/master/libs/core) | [`@langchain/core`](https://github.com/langchain-ai/langchainjs/tree/main/libs/langchain-core) | Base abstractions and runtime for the entire ecosystem |
| **Community** | [`langchain-community`](https://github.com/langchain-ai/langchain/tree/master/libs/community) | [`@langchain/community`](https://github.com/langchain-ai/langchainjs/tree/main/libs/langchain-community) | Third-party integrations and community contributions |
| **MCP Adapters** | [`langchain-mcp-adapters`](https://github.com/langchain-ai/langchain-mcp-adapters) | - | Make Anthropic MCP tools compatible with agents |
| **Text Splitters** | [`langchain-text-splitters`](https://github.com/langchain-ai/langchain/tree/master/libs/text-splitters) | [`@langchain/textsplitters`](https://github.com/langchain-ai/langchainjs/tree/main/libs/langchain-textsplitters) | Document processing and text splitting utilities |
| **Experimental** | [`langchain-experimental`](https://github.com/langchain-ai/langchain/tree/master/libs/experimental) | [`@langchain/experimental`](https://github.com/langchain-ai/langchainjs/tree/main/libs/langchain-experimental) | Beta features and experimental components |
| **CLI Tools** | [`langchain-cli`](https://github.com/langchain-ai/langchain/tree/master/libs/cli) | - | Command line interface for project management |
| **Legacy** | [`langchain-legacy`](https://github.com/langchain-ai/langchain/tree/master/libs/legacy) | - | Legacy components from pre-v1.0 (Python only) |
</details>

<details>
<summary><strong>▫️ LangChain Documentation and llms.txt Files ▫️</strong></summary>

Access the official LangChain documentation across the current unified docs experience and legacy redirect URLs:

<div align="center">

| Docs | Python | JavaScript | Notes |
|------|--------|------------|-------|
| **Current Open Source Docs** | [Overview](https://docs.langchain.com/oss/python/langchain/overview) | [Overview](https://docs.langchain.com/oss/javascript/langchain/overview) | Current unified LangChain OSS docs on `docs.langchain.com` |
| **Legacy Redirects** | [Legacy Entry](https://python.langchain.com/docs/introduction/) | [Legacy Entry](https://js.langchain.com/docs/introduction/) | Older URLs that now redirect to the current overview docs |

</div>

**AI-accessible documentation format for LLMs and IDEs** - LangChain now exposes a unified `llms.txt` entrypoint on `docs.langchain.com` for programmatic access to the latest documentation across LangChain, LangGraph, LangSmith, and API references.

### Available Files

| Scope | llms.txt | llms-full.txt |
|-------|----------|---------------|
| **Unified LangChain Docs** | [docs.langchain.com/llms.txt](https://docs.langchain.com/llms.txt) | N/A |
| **Legacy Redirects** | [python.langchain.com/llms.txt](https://python.langchain.com/llms.txt), [js.langchain.com/llms.txt](https://js.langchain.com/llms.txt) | N/A |

### Format Differences
- **`llms.txt`** - Unified index file with links and summaries for the latest LangChain ecosystem docs
- **Legacy `llms.txt` URLs** - Older Python and JavaScript endpoints that currently redirect to the unified docs file

> **⚠️ Review Output**: Even with up-to-date documentation, current models may not always generate correct code. Always review generated code before production use.

</details>


<n></n>

---

<div align="center">

## 🦜 LangGraph 🕸️

</div> 

**LangGraph** is an open-source framework for building **AI agents and multi-agent systems** as graphs, and is a core part of the **LangChain Ecosystem**. It focuses on **agent orchestration**, enabling sophisticated AI applications that can maintain state, coordinate multiple agents, and handle complex reasoning processes through graph-based workflows.

<details>
<summary><strong>▫️ Core Features ▫️</strong></summary>

| Capability | Description | Key Features |
|------------|-------------|--------------|
| **💾 Persistence** | State persistence across executions and failures | Checkpointing, state recovery, session continuity |
| **🔄 Durable Execution** | Build agents that persist through failures and run for extended periods | Automatic resume, failure recovery, long-running workflows |
| **⚡ Streaming** | Real-time execution with partial results and live updates | Token streaming, progress tracking, responsive UX |
| **⏸️ [Interrupts](https://docs.langchain.com/oss/python/langgraph/interrupts)** | Pause graph execution for human input, review, and intervention | Approval checkpoints, state editing, resumable workflows |
| **⏰ Time Travel** | Navigate through agent execution history and states | State debugging, execution replay, historical analysis |
| **🧠 Add and Manage Memory** | Comprehensive memory management for stateful agents | Short-term working memory, long-term persistence, memory optimization |
| **📊 Subgraphs** | Nested graph structures for complex workflow composition | Modular workflows, reusable components, hierarchical execution |
| **🧪 [Testing](https://docs.langchain.com/oss/python/langgraph/test)** | Validate graph behavior with unit and partial-execution testing patterns | Node testing, partial execution, checkpointer-based test setup |
| **👀 [Observability](https://docs.langchain.com/oss/python/langgraph/observability)** | Trace and debug graph execution with LangSmith | Execution traces, state inspection, runtime monitoring |

</details>



<details>
<summary><strong> ▫️ LangGraph Libraries and SDKs ▫️</strong></summary>

| Package | Python | TypeScript | Description |
|---------|--------|------------|-------------|
| **LangGraph** | [`langgraph`](https://github.com/langchain-ai/langgraph) | [`@langchain/langgraph`](https://github.com/langchain-ai/langgraphjs) | Core graph-based agent orchestration framework |
| **LangGraph CLI** | [`langgraph-cli`](https://github.com/langchain-ai/langgraph/tree/main/libs/cli) | [`@langchain/langgraph-cli`](https://github.com/langchain-ai/langgraphjs/tree/main/libs/langgraph-cli) | Command line interface for LangGraph development and deployment |
| **LangGraph SDK** | [Python SDK](https://docs.langchain.com/langgraph-platform/sdk) | [JavaScript SDK](https://docs.langchain.com/langgraph-platform/sdk) | Official SDKs for interacting with **LangGraph Platform(Server)** and deployed applications |

</details>


<details>
<summary><strong> ▫️ LangGraph Documentation and llms.txt Files ▫️</strong></summary>

Access the official LangGraph documentation across the current unified open source docs:

<div align="center">

| Docs | Python | JavaScript | Notes |
|------|--------|------------|-------|
| **Current Open Source Docs** | [Overview](https://docs.langchain.com/oss/python/langgraph/overview) | [Overview](https://docs.langchain.com/oss/javascript/langgraph/overview) | Current LangGraph OSS docs on `docs.langchain.com` |
| **Quickstart** | [Quickstart](https://docs.langchain.com/oss/python/langgraph/quickstart) | [Quickstart](https://docs.langchain.com/oss/javascript/langgraph/quickstart) | Build a first LangGraph app with tools, memory, and streaming |


</div>

**AI-accessible documentation format for LLMs and IDEs** - LangGraph documentation is part of the unified `docs.langchain.com` docs experience, so the primary `llms.txt` entrypoint is shared across the broader ecosystem docs.

| Scope | llms.txt | llms-full.txt |
|-------|----------|---------------|
| **Unified LangChain Docs** | [docs.langchain.com/llms.txt](https://docs.langchain.com/llms.txt) | N/A |

</details>



<n></n>

---

<div align="center">

## 🧠 Deep Agents

</div>

**Deep Agents** is an open-source agent harness for building agents that can plan, delegate to subagents, manage context with filesystem tools, and persist long-term memory for complex, multi-step tasks.

<details>
<summary><strong>▫️ Core Capabilities ▫️</strong></summary>

| Capability | Description | Key Features |
|------------|-------------|--------------|
| **🗂️ [Planning & Task Decomposition](https://docs.langchain.com/oss/python/deepagents/overview)** | Break large tasks into manageable steps and track progress | Built-in todo system, adaptive planning, multi-step execution |
| **📁 [Context Management](https://docs.langchain.com/oss/python/deepagents/backends)** | Offload and manage large context through filesystem tools | Virtual filesystem, file read/write/edit tools, context compaction |
| **🧩 [Subagents](https://docs.langchain.com/oss/python/deepagents/subagents)** | Delegate work to specialized agents for context isolation | Built-in task delegation, specialized subtasks, cleaner main-agent context |
| **🧠 [Memory](https://docs.langchain.com/oss/python/deepagents/long-term-memory)** | Persist useful information across threads and sessions | Long-term memory, memory stores, cross-thread recall |
| **✋ [Human-in-the-Loop](https://docs.langchain.com/oss/python/deepagents/human-in-the-loop)** | Add approval checkpoints for sensitive operations | Approval controls, resumable execution, tool-level oversight |
| **🧪 [Sandboxes](https://docs.langchain.com/oss/python/deepagents/sandboxes)** | Execute code in isolated environments when needed | Sandbox backends, secure execution, remote runtime options |
| **⚡ [Streaming](https://docs.langchain.com/oss/python/deepagents/streaming)** | Stream intermediate output and agent progress in real time | Live progress updates, streamed responses, responsive UX |
| **🛠️ [Skills](https://docs.langchain.com/oss/python/deepagents/skills)** | Extend agents with reusable, task-specific expertise | Skill directories, progressive disclosure, custom instructions |

</details>

<details>
<summary><strong> ▫️ Deep Agents SDK and CLI ▫️</strong></summary>

| Package | Python | TypeScript | Description |
|---------|--------|------------|-------------|
| **Deep Agents SDK** | [`deepagents`](https://github.com/langchain-ai/deepagents) | [`deepagents`](https://github.com/langchain-ai/deepagents) | Standalone open-source library for building agents with planning, subagents, filesystem tools, and long-term memory |
| **Deep Agents CLI** | [CLI Docs](https://docs.langchain.com/oss/python/deepagents/cli/overview) | [CLI Docs](https://docs.langchain.com/oss/javascript/deepagents/cli/overview) | Open-source terminal coding agent built on the Deep Agents SDK |

</details>

<details>
<summary><strong> ▫️ Deep Agents Documentation and llms.txt Files ▫️</strong></summary>

Access the official Deep Agents documentation across the current unified open source docs:

<div align="center">

| Docs | Python | JavaScript | Notes |
|------|--------|------------|-------|
| **Current Open Source Docs** | [Overview](https://docs.langchain.com/oss/python/deepagents/overview) | [Overview](https://docs.langchain.com/oss/javascript/deepagents/overview) | Current Deep Agents OSS docs on `docs.langchain.com` |
| **Quickstart** | [Quickstart](https://docs.langchain.com/oss/python/deepagents/quickstart) | [Quickstart](https://docs.langchain.com/oss/javascript/deepagents/quickstart) | Build a first deep agent with tools, planning, and memory |
| **CLI** | [CLI Overview](https://docs.langchain.com/oss/python/deepagents/cli/overview) | [CLI Overview](https://docs.langchain.com/oss/javascript/deepagents/cli/overview) | Terminal coding agent built on the Deep Agents SDK |

</div>

**AI-accessible documentation format for LLMs and IDEs** - Deep Agents documentation is available through the same unified `docs.langchain.com` docs index used across the LangChain ecosystem.

| Scope | llms.txt | llms-full.txt |
|-------|----------|---------------|
| **Unified LangChain Docs** | [docs.langchain.com/llms.txt](https://docs.langchain.com/llms.txt) | N/A |

</details>



<n></n>

---

<div align="center">

## 🦜 LangSmith 🛠️

</div>

**LangSmith** is a framework-agnostic platform for building, debugging, evaluating, and deploying AI agents and LLM applications. It works with or without LangChain's open-source frameworks and brings observability, prompt engineering, deployment, and operational tooling into one workflow.




<details>
<summary><strong>🔹 Core Features 🔹</strong></summary>

| Feature | Description | Key Capabilities |
|---------|-------------|-----------------|
| **🚀 [Deployment](https://docs.langchain.com/langsmith/deployment)** | Deploy agents as production-ready Agent Servers | Managed deployment, scaling, agent runtime, production hosting |
| **📊 [Observability](https://docs.langchain.com/langsmith/observability)** | Gain visibility into each step your application takes to debug faster and improve reliability | Tracing, dashboards, alerts, insights, automations |
| **📈 [Evaluation](https://docs.langchain.com/langsmith/evaluation)** | Measure and track application quality over time | Offline experiments, online evaluators, LLM-as-judge, evaluator tooling |
| **✏️ [Prompt Engineering](https://docs.langchain.com/langsmith/prompt-engineering)** | Iterate on prompts with built-in versioning and collaboration | Prompt testing, versioning, collaboration, commit history |
| **🧪 [Studio](https://docs.langchain.com/langsmith/studio)** | Design, test, and refine applications end-to-end in a visual interface | Visual development, prompt iteration, debugging workflows |
| **🛡️ [Sandboxes](https://docs.langchain.com/langsmith/sandboxes)** | Run code and tools in isolated execution environments | Secure execution, sandbox SDK, controlled runtime environments |
| **🏢 Platform Setup** | Configure LangSmith for cloud, hybrid, or self-hosted usage | Admin controls, compliance, data governance, infrastructure options |

</details>

<details>
<summary><strong>🔹 LangSmith SDK 🔹</strong></summary>

| Package | Python | TypeScript | Description |
|---------|--------|------------|-------------|
| **LangSmith Client SDK** | [`langsmith`](https://github.com/langchain-ai/langsmith-sdk) | [`langsmith`](https://github.com/langchain-ai/langsmith-sdk) | Official SDK for LangSmith platform integration |

</details>

<details>
<summary><strong>🔹 LangSmith Documentation and llms.txt Files 🔹</strong></summary>

Access the official LangSmith platform documentation:

<div align="center">

| Docs Area | Documentation | Notes |
|-----------|---------------|-------|
| **Overview** | [LangSmith Docs](https://docs.langchain.com/langsmith/home) | Main entrypoint for the LangSmith platform |
| **Deployment** | [Deployment](https://docs.langchain.com/langsmith/deployment) | Deploy agents as Agent Servers in production |
| **Observability** | [Observability](https://docs.langchain.com/langsmith/observability) | Tracing, dashboards, alerts, and monitoring workflows |
| **Evaluation** | [Evaluation](https://docs.langchain.com/langsmith/evaluation) | Offline and online evaluation workflows for AI systems |
| **Prompt Engineering** | [Prompt Engineering](https://docs.langchain.com/langsmith/prompt-engineering) | Prompt iteration, testing, and versioning |
| **Studio** | [Studio](https://docs.langchain.com/langsmith/studio) | Visual interface for building and refining apps |
| **Sandboxes** | [Sandboxes](https://docs.langchain.com/langsmith/sandboxes) | Isolated execution environments for tools and code |
| **Agent Server** | [Agent Server](https://docs.langchain.com/langsmith/agent-server) | Runtime and API surface for deployed agents |

</div>

**AI-accessible documentation format for LLMs and IDEs** - LangSmith is also covered by the unified `docs.langchain.com` docs index for programmatic access.

| Scope | llms.txt | llms-full.txt |
|-------|----------|---------------|
| **Unified LangChain Docs** | [docs.langchain.com/llms.txt](https://docs.langchain.com/llms.txt) | N/A |

</details>

<n></n>

> [!TIP]
> **Get started with LangSmith for free!** Sign up at [langchain.com/langsmith](https://www.langchain.com/langsmith) and follow the [deployment quickstart](https://docs.langchain.com/langsmith/deployment-quickstart), [observability quickstart](https://docs.langchain.com/langsmith/observability-quickstart), or [evaluation quickstart](https://docs.langchain.com/langsmith/evaluation-quickstart) depending on where you want to start.

<n></n>

---

<div align="center">

## 🧩 LangSmith Fleet

</div>

**LangSmith Fleet** is a no-code workspace for building AI agents for real work. Start from a template or describe your goal in plain English, connect tools like Gmail, Google Calendar, Slack, Exa, Tavily, and remote MCP servers, and let the agent automate routine workflows while keeping humans in control.

<details>
<summary><strong>🔹 Core Features 🔹</strong></summary>

| Feature | Description | Key Capabilities |
|---------|-------------|-----------------|
| **🧱 [No-Code Agent Builder](https://docs.langchain.com/langsmith/fleet)** | Create and manage agents without writing code | Template-based setup, AI-assisted configuration, editable instructions |
| **🔌 [Connected Tools](https://docs.langchain.com/langsmith/fleet/tools)** | Bring context and actions into agents through app integrations | Gmail, Google Calendar, Slack, Tavily, Exa, remote MCP servers |
| **📡 [Channels](https://docs.langchain.com/langsmith/fleet/channels)** | Use agents where your team already works | Slack and Microsoft Teams integrations, in-channel workflows |
| **🗓️ [Schedules](https://docs.langchain.com/langsmith/fleet/schedules)** | Run recurring tasks automatically | Daily briefings, recurring reports, timed automations |
| **✅ [Access & Oversight](https://docs.langchain.com/langsmith/fleet/access-and-oversight)** | Keep humans in control for important operations | Approval flows, oversight controls, safer automation |
| **🛠️ [Skills](https://docs.langchain.com/langsmith/fleet/skills)** | Extend agents with reusable task-specific behavior | Specialized instructions, reusable workflows, scoped capabilities |

</details>

<details>
<summary><strong>🔹 LangSmith Fleet Documentation 🔹</strong></summary>

Access the official LangSmith Fleet documentation:

<div align="center">

| Docs Area | Documentation | Notes |
|-----------|---------------|-------|
| **Overview** | [LangSmith Fleet](https://docs.langchain.com/langsmith/fleet) | Main entrypoint for Fleet |
| **Quickstart** | [Quickstart](https://docs.langchain.com/langsmith/fleet/quickstart) | Build your first Fleet agent |
| **Essentials** | [Essentials](https://docs.langchain.com/langsmith/fleet/essentials) | Connections, automation, memory, and approvals |
| **Templates** | [Templates](https://docs.langchain.com/langsmith/fleet/templates) | Browse ready-made starter agents and customize them |
| **Tools** | [Tools](https://docs.langchain.com/langsmith/fleet/tools) | Connect apps and services to your agents |
| **Channels** | [Channels](https://docs.langchain.com/langsmith/fleet/channels) | Use Fleet in Slack and Teams workflows |
| **Schedules** | [Schedules](https://docs.langchain.com/langsmith/fleet/schedules) | Trigger recurring tasks and automations |

</div>
</details>

<details>
<summary><strong>🔹 Fleet Templates 🔹</strong></summary>

Fleet includes ready-made templates for practical workflows such as:

- Daily calendar brief
- Email assistant
- LinkedIn recruiter
- Social media AI monitor
- Competitor research

Browse the full template catalog here:

[LangSmith Fleet Templates](https://docs.langchain.com/langsmith/fleet/templates)

</details>

<n></n>


---

<div align="center">

## 🦜 LangChain Integrations & Partners 🤝

</div>

**Third-party integrations and provider packages** that extend LangChain's capabilities across the AI ecosystem. These integration packages provide standardized interfaces to work with popular AI services, databases, and tools.


<details>
<summary><strong>🔸 Chat Models 🔸</strong></summary>

**Language models that use message sequences as input/output for conversational AI.** Support tool calling, structured output, streaming, and multimodal inputs for building sophisticated chat applications.

- **Python**: [Browse providers](https://docs.langchain.com/oss/python/integrations/chat)
- **JavaScript**: [Browse providers](https://docs.langchain.com/oss/javascript/integrations/chat)

</details>

<details>
<summary><strong>🔸 Tools & Toolkits 🔸</strong></summary>

**Enable agents to interact with external systems.** Define input schemas for tool calling and executing actions. Support web search, database queries, file operations, browser control, and API integrations.

- **Python**: [Browse providers](https://docs.langchain.com/oss/python/integrations/tools)
- **JavaScript**: [Browse providers](https://docs.langchain.com/oss/javascript/integrations/tools)

</details>

<details>
<summary><strong>🔸 Middleware 🔸</strong></summary>

**Control and customize agent execution at every step.** Add logging, retries, guardrails, human approval, rate limiting, prompt transforms, and other execution-time behavior.

- **Python**: [Browse middleware](https://docs.langchain.com/oss/python/langchain/middleware/overview)
- **JavaScript**: [Browse middleware](https://docs.langchain.com/oss/javascript/langchain/middleware/overview)

</details>

<details>
<summary><strong>🔸 Sandboxes 🔸</strong></summary>

**Run agent-generated code in isolated execution environments.** Sandboxes provide safer boundaries for shell access, filesystem operations, and code execution.

- **Python**: [Browse providers](https://docs.langchain.com/oss/python/integrations/sandboxes)
- **JavaScript**: -

</details>

<details>
<summary><strong>🔸 Checkpointers 🔸</strong></summary>

**Persistence backends for LangGraph state.** Save and resume agent state across interactions using in-memory, SQL, Redis, MongoDB, cloud, and other checkpoint stores.

- **Python**: [Browse providers](https://docs.langchain.com/oss/python/integrations/checkpointers)
- **JavaScript**: -

</details>

<details>
<summary><strong>🔸 Retrievers 🔸</strong></summary>

**Advanced retrieval strategies that combine dense and sparse search methods.** Enable sophisticated document retrieval patterns including hybrid search, reranking, and context-aware retrieval for RAG applications.

- **Python**: [Browse providers](https://docs.langchain.com/oss/python/integrations/retrievers)
- **JavaScript**: [Browse providers](https://docs.langchain.com/oss/javascript/integrations/retrievers)

</details>

<details>
<summary><strong>🔸 Text Splitters 🔸</strong></summary>

**Break large documents into smaller, manageable chunks.** Maintain semantic coherence while fitting within model context windows. Essential for RAG pipelines and document processing workflows.

- **Python**: [Browse providers](https://docs.langchain.com/oss/python/integrations/splitters)
- **JavaScript**: [Browse providers](https://docs.langchain.com/oss/javascript/integrations/splitters)

</details>

<details>
<summary><strong>🔸 Embedding Models 🔸</strong></summary>

**Transform raw text into fixed-length vectors that capture semantic meaning.** Enable machines to compare and search text based on meaning rather than exact words. Essential for retrieval, semantic search, and ranking workflows.

- **Python**: [Browse providers](https://docs.langchain.com/oss/python/integrations/text_embedding)
- **JavaScript**: [Browse providers](https://docs.langchain.com/oss/javascript/integrations/text_embedding)

</details>

<details>
<summary><strong>🔸 Vector Stores 🔸</strong></summary>

**Databases optimized for storing and querying high-dimensional vectors using similarity metrics.** Used with embedding models to power semantic search, retrieval, and knowledge base applications.

- **Python**: [Browse providers](https://docs.langchain.com/oss/python/integrations/vectorstores)
- **JavaScript**: [Browse providers](https://docs.langchain.com/oss/javascript/integrations/vectorstores)

</details>

<details>
<summary><strong>🔸 Document Loaders 🔸</strong></summary>

**Integrations for ingesting data from files, websites, databases, APIs, and cloud systems.** Transform diverse sources into LangChain `Document` objects for downstream processing.

- **Python**: [Browse providers](https://docs.langchain.com/oss/python/integrations/document_loaders)
- **JavaScript**: [Browse providers](https://docs.langchain.com/oss/javascript/integrations/document_loaders)

</details>

<n></n>

---

<div align="center">

## 🟢 Official LangGraph Projects 🦜

</div>

*Examples of applications and tools built with the LangChain ecosystem, ranging from experimental projects to production-ready solutions that showcase different capabilities and use cases.*

<div align="center">

### 🟩 Specialized Agent Libraries 🤖

</div>

*Pre-built agent packages for specific use cases and interaction patterns:*

<details>
<summary>▪️ <strong>Computer Use Agent</strong> - Automate computer interactions and GUI tasks ▪️</summary>

**Advanced agent for automating computer interactions and GUI tasks.** Provides sophisticated screen interaction capabilities, click/type automation, and visual reasoning for complex desktop automation workflows.

| | |
|---|---|
| **Python** | [`langgraph-cua-py`](https://github.com/langchain-ai/langgraph-cua-py) |
| **TypeScript** | [`langgraph-cua`](https://github.com/langchain-ai/langgraphjs/tree/main/libs/langgraph-cua) |
| **GitHub Stars** | ![GitHub stars](https://img.shields.io/github/stars/langchain-ai/langgraph-cua-py?style=social) |
| **Last Commit** | ![GitHub last commit](https://img.shields.io/github/last-commit/langchain-ai/langgraph-cua-py) |

</details>

<details>
<summary>▪️ <strong>Swarm Agent</strong> - Coordinate multiple specialized agents ▪️</summary>

**Multi-agent coordination system for distributed task execution.** Enables dynamic task distribution and collective intelligence across multiple specialized agents working together on complex problems.

| | |
|---|---|
| **Python** | [`langgraph-swarm-py`](https://github.com/langchain-ai/langgraph-swarm-py) |
| **TypeScript** | [`langgraph-swarm`](https://github.com/langchain-ai/langgraphjs/tree/main/libs/langgraph-swarm) |
| **GitHub Stars** | ![GitHub stars](https://img.shields.io/github/stars/langchain-ai/langgraph-swarm-py?style=social) |
| **Last Commit** | ![GitHub last commit](https://img.shields.io/github/last-commit/langchain-ai/langgraph-swarm-py) |

</details>

<details>
<summary>▪️ <strong>Supervisor</strong> - Hierarchical multi-agent coordination ▪️</summary>

**Agent orchestration and workflow supervision system.** Provides advanced multi-agent coordination, task delegation, and workflow management for complex hierarchical agent architectures.

| | |
|---|---|
| **Python** | [`langgraph-supervisor-py`](https://github.com/langchain-ai/langgraph-supervisor-py) |
| **TypeScript** | [`langgraph-supervisor`](https://github.com/langchain-ai/langgraphjs/tree/main/libs/langgraph-supervisor) |
| **GitHub Stars** | ![GitHub stars](https://img.shields.io/github/stars/langchain-ai/langgraph-supervisor-py?style=social) |
| **Last Commit** | ![GitHub last commit](https://img.shields.io/github/last-commit/langchain-ai/langgraph-supervisor-py) |

</details>

<details>
<summary>▪️ <strong>MCP Adapters</strong> - Integrate Anthropic MCP tools with agents ▪️</summary>

**Model Context Protocol integration for LangChain agents.** Provides tool compatibility and protocol bridging to seamlessly integrate Anthropic MCP tools with agent workflows.

| | |
|---|---|
| **Python** | [`langchain-mcp-adapters`](https://github.com/langchain-ai/langchain-mcp-adapters) |
| **TypeScript** | -- |
| **GitHub Stars** | ![GitHub stars](https://img.shields.io/github/stars/langchain-ai/langchain-mcp-adapters?style=social) |
| **Last Commit** | ![GitHub last commit](https://img.shields.io/github/last-commit/langchain-ai/langchain-mcp-adapters) |

</details>

<details>
<summary>▪️ <strong>LangMem</strong> - Build agents with persistent learning capabilities ▪️</summary>

**Advanced memory management system for persistent agent learning.** Enables memory management, experience replay, and adaptation for agents that learn and improve over time.

| | |
|---|---|
| **Python** | [`langmem`](https://github.com/langchain-ai/langmem) |
| **TypeScript** | -- |
| **GitHub Stars** | ![GitHub stars](https://img.shields.io/github/stars/langchain-ai/langmem?style=social) |
| **Last Commit** | ![GitHub last commit](https://img.shields.io/github/last-commit/langchain-ai/langmem) |

</details>

<details>
<summary>▪️ <strong>CodeAct</strong> - Advanced code generation and execution ▪️</summary>

**Secure code generation and execution agent.** Provides advanced function calling, code analysis, and debugging capabilities in controlled environments for safe programming assistance.

| | |
|---|---|
| **Python** | [`langgraph-codeact`](https://github.com/langchain-ai/langgraph-codeact) |
| **TypeScript** | -- |
| **GitHub Stars** | ![GitHub stars](https://img.shields.io/github/stars/langchain-ai/langgraph-codeact?style=social) |
| **Last Commit** | ![GitHub last commit](https://img.shields.io/github/last-commit/langchain-ai/langgraph-codeact) |

</details>

<details>
<summary>▪️ <strong>Reflection</strong> - Self-improving agents with review capabilities ▪️</summary>

**Self-improving agent system with iterative feedback loops.** Enables self-critique, iterative improvement, and quality control through reflection and continuous learning mechanisms.

| | |
|---|---|
| **Python** | [`langgraph-reflection`](https://github.com/langchain-ai/langgraph-reflection) |
| **TypeScript** | -- |
| **GitHub Stars** | ![GitHub stars](https://img.shields.io/github/stars/langchain-ai/langgraph-reflection?style=social) |
| **Last Commit** | ![GitHub last commit](https://img.shields.io/github/last-commit/langchain-ai/langgraph-reflection) |

</details>

<details>
<summary>▪️ <strong>BigTool</strong> - Handle large-scale tool ecosystems ▪️</summary>

**Large-scale tool management and optimization system.** Provides advanced tool management and intelligent selection optimization for efficiently handling complex tool ecosystems.

| | |
|---|---|
| **Python** | [`langgraph-bigtool`](https://github.com/langchain-ai/langgraph-bigtool) |
| **TypeScript** | -- |
| **GitHub Stars** | ![GitHub stars](https://img.shields.io/github/stars/langchain-ai/langgraph-bigtool?style=social) |
| **Last Commit** | ![GitHub last commit](https://img.shields.io/github/last-commit/langchain-ai/langgraph-bigtool) |

</details>

<details>
<summary>▪️ <strong>Deep Agents</strong> - Complex, long-term planning and execution ▪️</summary>

**Advanced agents for complex, long-term planning and execution.** Features sophisticated planning tools, sub-agent orchestration, file system access, and detailed prompts for handling complex multi-step tasks.

| | |
|---|---|
| **Python** | [`deepagents`](https://github.com/langchain-ai/deepagents) |
| **TypeScript** | -- |
| **GitHub Stars** | ![GitHub stars](https://img.shields.io/github/stars/langchain-ai/deepagents?style=social) |
| **Last Commit** | ![GitHub last commit](https://img.shields.io/github/last-commit/langchain-ai/deepagents) |

</details>

<details>
<summary>▪️ <strong>Open Deep Research</strong> - Automated PhD-level research agent ▪️</summary>

**Configurable deep research agent for automated research tasks.** Performs comprehensive research across multiple sources with multi-model support, MCP compatibility, and evaluation benchmarks. Achieves performance comparable to popular research agents on Deep Research Bench leaderboard.

| | |
|---|---|
| **Python** | [`open_deep_research`](https://github.com/langchain-ai/open_deep_research) |
| **TypeScript** | -- |
| **GitHub Stars** | ![GitHub stars](https://img.shields.io/github/stars/langchain-ai/open_deep_research?style=social) |
| **Last Commit** | ![GitHub last commit](https://img.shields.io/github/last-commit/langchain-ai/open_deep_research) |

</details>


---

<div align="center">

### 🟩 Apps & Agents 📱

</div>

*Complete application examples showcasing different patterns and use cases:*

<details>
<summary>▪️ <strong>Open Agent Platform</strong> - No-code platform for building customizable agents ▪️</summary>

**No-code platform for building customizable agents with MCP tools integration.** Features LangConnect RAG support, multi-agent supervision capabilities, modern web interface, and pre-built agent templates for rapid development.

| | |
|---|---|
| **Repository** | [`open-agent-platform`](https://github.com/langchain-ai/open-agent-platform) |
| **GitHub Stars** | ![GitHub stars](https://img.shields.io/github/stars/langchain-ai/open-agent-platform?style=social) |
| **Last Commit** | ![GitHub last commit](https://img.shields.io/github/last-commit/langchain-ai/open-agent-platform) |

</details>

<details>
<summary>▪️ <strong>LangConnect</strong> - Managed RAG service with FastAPI integration ▪️</summary>

**Managed RAG service with FastAPI and PostgreSQL/pgvector integration.** Features document collection management, semantic search, and Docker deployment support for production-ready RAG applications.

| | |
|---|---|
| **Repository** | [`langconnect`](https://github.com/langchain-ai/langconnect) |
| **GitHub Stars** | ![GitHub stars](https://img.shields.io/github/stars/langchain-ai/langconnect?style=social) |
| **Last Commit** | ![GitHub last commit](https://img.shields.io/github/last-commit/langchain-ai/langconnect) |

</details>

<details>
<summary>▪️ <strong>ChatLangChain</strong> - Documentation assistant with RAG-based search ▪️</summary>

**Documentation assistant powered by RAG-based semantic search with intelligent query analysis.** Features automated content indexing, duplicate prevention, GenUI, and sophisticated document tracking system.

| | |
|---|---|
| **Repository** | [`chat-langchain`](https://github.com/langchain-ai/chat-langchain) |
| **GitHub Stars** | ![GitHub stars](https://img.shields.io/github/stars/langchain-ai/chat-langchain?style=social) |
| **Last Commit** | ![GitHub last commit](https://img.shields.io/github/last-commit/langchain-ai/chat-langchain) |

</details>
<details>
<summary>▪️ <strong>OpenGPTs</strong> - Open-source GPT alternative with 60+ LLM providers ▪️</summary>

**Open-source GPT alternative supporting 60+ LLM providers and tools.** Implements three cognitive architectures (Assistant, RAG, Chatbot) with PostgreSQL backend and flexible deployment options.

| | |
|---|---|
| **Repository** | [`opengpts`](https://github.com/langchain-ai/opengpts) |
| **GitHub Stars** | ![GitHub stars](https://img.shields.io/github/stars/langchain-ai/opengpts?style=social) |
| **Last Commit** | ![GitHub last commit](https://img.shields.io/github/last-commit/langchain-ai/opengpts) |

</details>

<details>
<summary>▪️ <strong>Executive AI Assistant</strong> - Smart email management with calendar integration ▪️</summary>

**Smart email management system with calendar integration.** Provides intelligent triage, automated response drafting, and meeting coordination through Gmail API with customizable workflows.

| | |
|---|---|
| **Repository** | [`executive-ai-assistant`](https://github.com/langchain-ai/executive-ai-assistant) |
| **GitHub Stars** | ![GitHub stars](https://img.shields.io/github/stars/langchain-ai/executive-ai-assistant?style=social) |
| **Last Commit** | ![GitHub last commit](https://img.shields.io/github/last-commit/langchain-ai/executive-ai-assistant) |

</details>

<details>
<summary>▪️ <strong>Agent Inbox</strong> - Centralized interface for AI agent interactions ▪️</summary>

**Centralized interface for AI agent interactions featuring real-time communication.** Includes interrupt handling and configurable response systems for both local and cloud deployments.

| | |
|---|---|
| **Repository** | [`agent-inbox`](https://github.com/langchain-ai/agent-inbox) |
| **GitHub Stars** | ![GitHub stars](https://img.shields.io/github/stars/langchain-ai/agent-inbox?style=social) |
| **Last Commit** | ![GitHub last commit](https://img.shields.io/github/last-commit/langchain-ai/agent-inbox) |

</details>

<details>
<summary>▪️ <strong>Python Fullstack</strong> - All-in-one chatbot template with modern UI ▪️</summary>

**All-in-one chatbot template combining React-style agents with modern UI.** Built with FastHTML components and Claude 3, featuring single-deployment architecture and extensible tools.

| | |
|---|---|
| **Repository** | [`langgraph-fullstack-python`](https://github.com/langchain-ai/langgraph-fullstack-python) |
| **GitHub Stars** | ![GitHub stars](https://img.shields.io/github/stars/langchain-ai/langgraph-fullstack-python?style=social) |
| **Last Commit** | ![GitHub last commit](https://img.shields.io/github/last-commit/langchain-ai/langgraph-fullstack-python) |

</details>

<details>
<summary>▪️ <strong>LangGraph UI Examples</strong> - Generative UI agents showcase ▪️</summary>

**Showcase of generative UI agents including stockbroker, trip planner, and email tools.** Demonstrates human-in-the-loop workflows with customizable components and tool integrations.

| | |
|---|---|
| **Repository** | [`langgraphjs-gen-ui-examples`](https://github.com/langchain-ai/langgraphjs-gen-ui-examples) |
| **GitHub Stars** | ![GitHub stars](https://img.shields.io/github/stars/langchain-ai/langgraphjs-gen-ui-examples?style=social) |
| **Last Commit** | ![GitHub last commit](https://img.shields.io/github/last-commit/langchain-ai/langgraphjs-gen-ui-examples) |

</details>

<details>
<summary>▪️ <strong>LangChain Next.js</strong> - Next.js starter template for LangChain.js ▪️</summary>

**Next.js starter template showcasing LangChain.js modules.** Includes streaming chat, structured output, multi-step agents, and RAG implementations with Vercel AI SDK integration.

| | |
|---|---|
| **Repository** | [`langchain-nextjs-template`](https://github.com/langchain-ai/langchain-nextjs-template) |
| **GitHub Stars** | ![GitHub stars](https://img.shields.io/github/stars/langchain-ai/langchain-nextjs-template?style=social) |
| **Last Commit** | ![GitHub last commit](https://img.shields.io/github/last-commit/langchain-ai/langchain-nextjs-template) |

</details>

<details>
<summary>▪️ <strong>Custom Auth</strong> - Supabase-powered authentication template ▪️</summary>

**Supabase-powered authentication template for LangGraph deployments.** Implements OAuth2 with Google, user management, and secure chatbot access with conversation thread isolation.

| | |
|---|---|
| **Repository** | [`custom-auth`](https://github.com/langchain-ai/custom-auth) |
| **GitHub Stars** | ![GitHub stars](https://img.shields.io/github/stars/langchain-ai/custom-auth?style=social) |
| **Last Commit** | ![GitHub last commit](https://img.shields.io/github/last-commit/langchain-ai/custom-auth) |

</details>

<details>
<summary>▪️ <strong>Multi-Modal Researcher</strong> - Research and podcast generation workflow ▪️</summary>

**Research and podcast generation workflow using LangGraph with Gemini 2.5 model family.** Features video understanding, Google search integration, and multi-speaker text-to-speech for creating comprehensive research reports and audio podcasts.

| | |
|---|---|
| **Repository** | [`multi-modal-researcher`](https://github.com/langchain-ai/multi-modal-researcher) |
| **GitHub Stars** | ![GitHub stars](https://img.shields.io/github/stars/langchain-ai/multi-modal-researcher?style=social) |
| **Last Commit** | ![GitHub last commit](https://img.shields.io/github/last-commit/langchain-ai/multi-modal-researcher) |

</details>

<details>
<summary>▪️ <strong>Deep Agents UI</strong> - Next.js interface for Deep Agents ▪️</summary>

**Next.js interface for Deep Agents with streaming support and LangGraph Platform integration.** Generic AI agents capable of handling tasks of varying complexity with customizable UI components.

| | |
|---|---|
| **Repository** | [`deep-agents-ui`](https://github.com/langchain-ai/deep-agents-ui) |
| **GitHub Stars** | ![GitHub stars](https://img.shields.io/github/stars/langchain-ai/deep-agents-ui?style=social) |
| **Last Commit** | ![GitHub last commit](https://img.shields.io/github/last-commit/langchain-ai/deep-agents-ui) |

</details>

<details>
<summary>▪️ <strong>Gen UI Computer Use</strong> - Generative UI web app for Computer Use Agents ▪️</summary>

**A Generative UI web app for interacting with Computer Use Agents (CUA).** Uses the `@langchain/langgraph-cua` prebuilt package and features a modern interface for computer automation and task management.

| | |
|---|---|
| **Repository** | [`gen-ui-computer-use`](https://github.com/bracesproul/gen-ui-computer-use) |
| **GitHub Stars** | ![GitHub stars](https://img.shields.io/github/stars/bracesproul/gen-ui-computer-use?style=social) |
| **Last Commit** | ![GitHub last commit](https://img.shields.io/github/last-commit/bracesproul/gen-ui-computer-use) |

</details>

<details>
<summary>▪️ <strong>Robo Blogger</strong> - Voice-to-content pipeline for structured blog posts ▪️</summary>

**Voice-to-content pipeline for converting spoken ideas into structured blog posts.** Features intelligent content organization, automated formatting, and seamless voice-to-text processing for content creation workflows.

| | |
|---|---|
| **Repository** | [`robo-blogger`](https://github.com/langchain-ai/robo-blogger) |
| **GitHub Stars** | ![GitHub stars](https://img.shields.io/github/stars/langchain-ai/robo-blogger?style=social) |
| **Last Commit** | ![GitHub last commit](https://img.shields.io/github/last-commit/langchain-ai/robo-blogger) |

</details>

<details>
<summary>▪️ <strong>Reply gAI</strong> - AI clone for X/Twitter profiles with memory ▪️</summary>

**AI clone for X/Twitter profiles with long-term memory and RAG capabilities.** Creates personalized social media interactions by learning from profile history and maintaining context across conversations.

| | |
|---|---|
| **Repository** | [`reply_gAI`](https://github.com/langchain-ai/reply_gAI) |
| **GitHub Stars** | ![GitHub stars](https://img.shields.io/github/stars/langchain-ai/reply_gAI?style=social) |
| **Last Commit** | ![GitHub last commit](https://img.shields.io/github/last-commit/langchain-ai/reply_gAI) |

</details>

<details>
<summary>▪️ <strong>Social Media Agent</strong> - Generates social media posts from URLs ▪️</summary>

**Generates Twitter & LinkedIn posts from URLs with optional human review.** Features content analysis, platform-specific formatting, and approval workflows for social media content creation.

| | |
|---|---|
| **Repository** | [`social-media-agent`](https://github.com/langchain-ai/social-media-agent) |
| **GitHub Stars** | ![GitHub stars](https://img.shields.io/github/stars/langchain-ai/social-media-agent?style=social) |
| **Last Commit** | ![GitHub last commit](https://img.shields.io/github/last-commit/langchain-ai/social-media-agent) |

</details>



<div align="center">

### 🟩 Development Tools 🛠️

</div>

*Development tools for building, visualizing, and deploying LangGraph applications:*

<details>
<summary>▪️ <strong>LangGraph Builder</strong> - Visual development with drag-and-drop graph design ▪️</summary>

**Visual development interface for creating LangGraph applications.** Features intuitive drag-and-drop graph design, automatic code generation for both Python and TypeScript, and real-time visualization of agent workflows.

| | |
|---|---|
| **Repository** | [`langgraph-builder`](https://github.com/langchain-ai/langgraph-builder) |
| **GitHub Stars** | ![GitHub stars](https://img.shields.io/github/stars/langchain-ai/langgraph-builder?style=social) |
| **Last Commit** | ![GitHub last commit](https://img.shields.io/github/last-commit/langchain-ai/langgraph-builder) |

</details>

<details>
<summary>▪️ <strong>LangGraph Generator</strong> - Code generation and project scaffolding ▪️</summary>

**Automated code generation tool for LangGraph projects.** Converts YAML configurations to working code, provides project scaffolding, and automates boilerplate creation for rapid development.

| | |
|---|---|
| **Repository** | [`langgraph-gen-py`](https://github.com/langchain-ai/langgraph-gen-py) |
| **GitHub Stars** | ![GitHub stars](https://img.shields.io/github/stars/langchain-ai/langgraph-gen-py?style=social) |
| **Last Commit** | ![GitHub last commit](https://img.shields.io/github/last-commit/langchain-ai/langgraph-gen-py) |

</details>

---


<div align="center">

# 🌟 Community Projects 

</div>

*Discover amazing open-source projects and innovative tools built by the community using the LangGraph ecosystem. These projects showcase real-world applications across diverse domains and use cases, demonstrating the versatility and power of LangGraph and LangChain frameworks.*

> **Want to add your project?** See our [Contributing Guide](CONTRIBUTING.md) for details on how to submit your LangGraph/LangChain project to this collection.

<div align="center">

## 🧬 Bio & Health

</div>

*Healthcare, medical diagnosis, genomic research, and scientific research agents*

| Project | Description | GitHub Stars |
|---------|-------------|--------------|
| [souvikmajumder26/Multi-Agent-Medical-Assistant](https://github.com/souvikmajumder26/Multi-Agent-Medical-Assistant) | AI-powered multi-agent system for medical diagnosis, research, and patient interaction, featuring LLMs, RAG, and human-in-the-loop validation | ![GitHub stars](https://img.shields.io/github/stars/souvikmajumder26/Multi-Agent-Medical-Assistant?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/souvikmajumder26/Multi-Agent-Medical-Assistant) |
| [ArcInstitute/SRAgent](https://github.com/ArcInstitute/SRAgent) | Multi-agent framework for automating genomic research and RNA sequencing workflows from scientific databases | ![GitHub stars](https://img.shields.io/github/stars/ArcInstitute/SRAgent?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/ArcInstitute/SRAgent) |

<div align="center">

## 🌐 Web Automation & Scraping

</div>

*Browser control, web task automation, and data extraction*

| Project | Description | GitHub Stars |
|---|---|---|
| [hrithikkoduri/WebRover](https://github.com/hrithikkoduri/WebRover) | Autonomous agent for automating web tasks and research | ![GitHub stars](https://img.shields.io/github/stars/hrithikkoduri/WebRover?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/hrithikkoduri/WebRover) |
| [esinecan/agentic-ai-browser](https://github.com/esinecan/agentic-ai-browser) | Web automation agent with behavioral caching, DOM fidelity, and success pattern recording | ![GitHub stars](https://img.shields.io/github/stars/esinecan/agentic-ai-browser?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/esinecan/agentic-ai-browser) |
| [browser-use/browser-use](https://github.com/browser-use/browser-use) | Library for AI agents to control websites and automate tasks | ![GitHub stars](https://img.shields.io/github/stars/browser-use/browser-use?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/browser-use/browser-use) |
| [stanford-mast/blast](https://github.com/stanford-mast/blast) | High-performance serving engine for browser-augmented LLM applications with auto-scaling and OpenAI-compatible API | ![GitHub stars](https://img.shields.io/github/stars/stanford-mast/blast?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/stanford-mast/blast) |
| [ScrapeGraphAI/scrapecraft](https://github.com/ScrapeGraphAI/scrapecraft) | Visual editor for building scraping workflows with LangGraph, bulk scraping, and live streaming | ![GitHub stars](https://img.shields.io/github/stars/ScrapeGraphAI/scrapecraft?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/ScrapeGraphAI/scrapecraft) |
| [nickhawn/news-agent](https://github.com/nickhawn/news-agent) | News crawler that personalizes daily summaries with Tavily and memory | ![GitHub stars](https://img.shields.io/github/stars/nickhawn/news-agent?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/nickhawn/news-agent) |

<div align="center">

## 📊 Business Intelligence & Market Research

</div>

*Business analysis, market research, and strategic intelligence tools*

| Project | Description | GitHub Stars |
|---|---|---|
| [oba2311/analyst_agent](https://github.com/oba2311/analyst_agent) | Marketing analysis agent with trend/sentiment analysis and report generation | ![GitHub stars](https://img.shields.io/github/stars/oba2311/analyst_agent?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/oba2311/analyst_agent) |
| [muratcankoylan/AI-Investigator](https://github.com/muratcankoylan/AI-Investigator) | Agent that discovers and analyzes enterprise AI case studies | ![GitHub stars](https://img.shields.io/github/stars/muratcankoylan/AI-Investigator?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/muratcankoylan/AI-Investigator) |


<div align="center">

## 🖥️ Chat Interfaces & GUIs

</div>

*Frontend applications, chat interfaces, and graphical user interfaces for AI agents*

| Project | Description | GitHub Stars |
|---|---|---|
| [GaiZhenbiao/ChuanhuChatGPT](https://github.com/GaiZhenbiao/ChuanhuChatGPT) | GUI for ChatGPT/LLMs with agent support, web search, and knowledge base features | ![GitHub stars](https://img.shields.io/github/stars/GaiZhenbiao/ChuanhuChatGPT?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/GaiZhenbiao/ChuanhuChatGPT) |
| [CopilotKit/open-multi-agent-canvas](https://github.com/CopilotKit/open-multi-agent-canvas) | Multi-agent chat interface with travel/research examples and MCP servers | ![GitHub stars](https://img.shields.io/github/stars/CopilotKit/open-multi-agent-canvas?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/CopilotKit/open-multi-agent-canvas) |
| [teddynote-lab/LangConnect-Client](https://github.com/teddynote-lab/LangConnect-Client) | Streamlit RAG client with document management, semantic/hybrid search, and MCP integration | ![GitHub stars](https://img.shields.io/github/stars/teddynote-lab/LangConnect-Client?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/teddynote-lab/LangConnect-Client) |

<div align="center">

## ☁️ Cloud & DevOps

</div>

*Cloud infrastructure management, deployment automation, and cloud resource management*

| Project | Description | GitHub Stars |
|---------|-------------|--------------|
| [eosho/ARMA](https://github.com/eosho/ARMA) | Azure Resource Management Assistant with multi-agent architecture for resource provisioning and ARM template validation | ![GitHub stars](https://img.shields.io/github/stars/eosho/ARMA?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/eosho/ARMA) |

<div align="center">

## 🤖 Coding/Dev Agents

</div>

*AI agents specifically designed for software development, code generation, and programming assistance*

| Project | Description | GitHub Stars |
|---------|-------------|--------------|
| [KodyKendall/LlamaBot](https://github.com/KodyKendall/LlamaBot) | Web development coding agent for creating HTML/CSS/JavaScript projects and business landing pages | ![GitHub stars](https://img.shields.io/github/stars/KodyKendall/LlamaBot?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/KodyKendall/LlamaBot) |
| [AbhinavTheDev/coding-agent](https://github.com/AbhinavTheDev/coding-agent) | Development tool that uses LangGraph agents to aid coding workflow with natural language | ![GitHub stars](https://img.shields.io/github/stars/AbhinavTheDev/coding-agent?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/AbhinavTheDev/coding-agent) |
| [langtalks/swe-agent](https://github.com/langtalks/swe-agent) | Software engineering multi-agent system with researcher and developer agents for automated code implementation | ![GitHub stars](https://img.shields.io/github/stars/langtalks/swe-agent?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/langtalks/swe-agent) |

<div align="center">

## 🛎️ Customer Ops

</div>

*Customer support, CRM systems, service management, and customer interaction automation*

| Project | Description | GitHub Stars |
|---|---|---|
| [kargarisaac/telegram_link_summarizer_agent](https://github.com/kargarisaac/telegram_link_summarizer_agent) | Telegram bot that summarizes shared links using LangGraph and multi-tool extraction | ![GitHub stars](https://img.shields.io/github/stars/kargarisaac/telegram_link_summarizer_agent?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/kargarisaac/telegram_link_summarizer_agent) |
| [gotohuman/gotohuman-langgraph-lead-example](https://github.com/gotohuman/gotohuman-langgraph-lead-example) | Sales email drafting with human-in-the-loop review | ![GitHub stars](https://img.shields.io/github/stars/gotohuman/gotohuman-langgraph-lead-example?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/gotohuman/gotohuman-langgraph-lead-example) |
| [multinear-demo/demo-bank-support-lc-py](https://github.com/multinear-demo/demo-bank-support-lc-py) | Banking support chatbot with RAG to reduce hallucinations | ![GitHub stars](https://img.shields.io/github/stars/multinear-demo/demo-bank-support-lc-py?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/multinear-demo/demo-bank-support-lc-py) |
| [tilotech/identity-rag-customer-insights-chatbot](https://github.com/tilotech/identity-rag-customer-insights-chatbot) | Customer insights chatbot that creates golden records for context-aware replies | ![GitHub stars](https://img.shields.io/github/stars/tilotech/identity-rag-customer-insights-chatbot?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/tilotech/identity-rag-customer-insights-chatbot) |
| [raminmohammadi/ai-agent-smart-assist](https://github.com/raminmohammadi/ai-agent-smart-assist) | Knowledge base + classification + Q&A for support teams (FAISS + RAG) | ![GitHub stars](https://img.shields.io/github/stars/raminmohammadi/ai-agent-smart-assist?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/raminmohammadi/ai-agent-smart-assist) |



<div align="center">

## 📊 Data Platforms  

</div>

*Data analysis, visualization, business intelligence, and data processing agents*

| Project | Description | GitHub Stars |
|---|---|---|
| [starpig1129/AI-Data-Analysis-MultiAgent](https://github.com/starpig1129/AI-Data-Analysis-MultiAgent) | Multi-agent data analysis with visualization and report generation | ![GitHub stars](https://img.shields.io/github/stars/starpig1129/AI-Data-Analysis-MultiAgent?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/starpig1129/AI-Data-Analysis-MultiAgent) |
| [project-ryoma/ryoma](https://github.com/project-ryoma/ryoma) | Data agent framework for analysis, engineering, and visualization with LangChain integration | ![GitHub stars](https://img.shields.io/github/stars/project-ryoma/ryoma?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/project-ryoma/ryoma) |

<div align="center">

## 🧮 Data Science 

</div>

*Machine learning, statistical analysis, and data science workflow automation*

| Project | Description | GitHub Stars |
|---------|-------------|--------------|
| [business-science/ai-data-science-team](https://github.com/business-science/ai-data-science-team) | AI-powered data science team for common tasks | ![GitHub stars](https://img.shields.io/github/stars/business-science/ai-data-science-team?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/business-science/ai-data-science-team) |
| [leockl/sklearn-diagnose](https://github.com/leockl/sklearn-diagnose) | AI-powered diagnostic tool for analyzing and debugging scikit-learn machine learning models | ![GitHub stars](https://img.shields.io/github/stars/leockl/sklearn-diagnose?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/leockl/sklearn-diagnose) |
| [RichardKaranuMbuti/ScienceBridge](https://github.com/RichardKaranuMbuti/ScienceBridge) | Scientific research accelerator that analyzes datasets, generates hypotheses, and validates them through code | ![GitHub stars](https://img.shields.io/github/stars/RichardKaranuMbuti/ScienceBridge?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/RichardKaranuMbuti/ScienceBridge) |


<div align="center">

## 🛠️ Developer Tools

</div>

*Development frameworks, toolkits, and development infrastructure*

| Project | Description | GitHub Stars |
|---|---|---|
| [akamai/patchdiff-ai](https://github.com/akamai/patchdiff-ai) | AI-powered patch diff analysis tool for automated code change review and security analysis | ![GitHub stars](https://img.shields.io/github/stars/akamai/patchdiff-ai?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/akamai/patchdiff-ai) |
| [sanjeed5/ai-conversation-simulator](https://github.com/sanjeed5/ai-conversation-simulator) | Simulated conversations to test assistants; LangSmith integration | ![GitHub stars](https://img.shields.io/github/stars/sanjeed5/ai-conversation-simulator?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/sanjeed5/ai-conversation-simulator) |
| [DiTo97/deepagents-backends](https://github.com/DiTo97/deepagents-backends) | Backend services and infrastructure for deploying and managing Deep Agents applications | ![GitHub stars](https://img.shields.io/github/stars/DiTo97/deepagents-backends?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/DiTo97/deepagents-backends) |
| [JoshuaC215/agent-service-toolkit](https://github.com/JoshuaC215/agent-service-toolkit) | Toolkit for deploying agents with FastAPI and Streamlit | ![GitHub stars](https://img.shields.io/github/stars/JoshuaC215/agent-service-toolkit?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/JoshuaC215/agent-service-toolkit) |
| [HyperbolicLabs/Hyperbolic-AgentKit](https://github.com/HyperbolicLabs/Hyperbolic-AgentKit) | Agent kit with blockchain/compute features | ![GitHub stars](https://img.shields.io/github/stars/HyperbolicLabs/Hyperbolic-AgentKit?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/HyperbolicLabs/Hyperbolic-AgentKit) |
| [googleapis/genai-toolbox](https://github.com/googleapis/genai-toolbox) | Infra for agent ↔ DB connectivity (security, observability, pooling) | ![GitHub stars](https://img.shields.io/github/stars/googleapis/genai-toolbox?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/googleapis/genai-toolbox) |
| [Darwin-lfl/langmanus](https://github.com/Darwin-lfl/langmanus) | Automation framework with web search, crawling, Python execution | ![GitHub stars](https://img.shields.io/github/stars/Darwin-lfl/langmanus?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/Darwin-lfl/langmanus) |
| [hinthornw/trustcall](https://github.com/hinthornw/trustcall) | Tenacious tool calling on LangGraph | ![GitHub stars](https://img.shields.io/github/stars/hinthornw/trustcall?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/hinthornw/trustcall) |
| [langasync/langasync](https://github.com/langasync/langasync) | Asynchronous utilities and extensions for LangChain enabling high-performance async workflows | ![GitHub stars](https://img.shields.io/github/stars/langasync/langasync?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/langasync/langasync) |
| [andrestorres123/delve](https://github.com/andrestorres123/delve) | Taxonomy generator for unstructured data | ![GitHub stars](https://img.shields.io/github/stars/andrestorres123/delve?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/andrestorres123/delve) |
| [Bessouat40/RAGLight](https://github.com/Bessouat40/RAGLight) | Modular RAG/Agentic RAG library for multiple providers | ![GitHub stars](https://img.shields.io/github/stars/Bessouat40/RAGLight?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/Bessouat40/RAGLight) |
| [teddynote-lab/langgraph-mcp-agents](https://github.com/teddynote-lab/langgraph-mcp-agents) | MCP integration toolkit for LangGraph agents | ![GitHub stars](https://img.shields.io/github/stars/teddynote-lab/langgraph-mcp-agents?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/teddynote-lab/langgraph-mcp-agents) |
| [cryxnet/deepmcpagent](https://github.com/cryxnet/deepmcpagent) | MCP-first agent framework (LangChain/LangGraph) over HTTP/SSE | ![GitHub stars](https://img.shields.io/github/stars/cryxnet/deepmcpagent?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/cryxnet/deepmcpagent) |
| [cubaseuser123/Cellwise-LanGraph-NoteBook-Agent](https://github.com/cubaseuser123/Cellwise-LanGraph-NoteBook-Agent) | LangGraph agent that auto-documents Jupyter notebooks in real-time as cells execute, via IPython hooks | ![GitHub stars](https://img.shields.io/github/stars/cubaseuser123/Cellwise-LanGraph-NoteBook-Agent?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/cubaseuser123/Cellwise-LanGraph-NoteBook-Agent) |
| [Azzedde/brainstormers](https://github.com/Azzedde/brainstormers) | Curated chains for structured brainstorming | ![GitHub stars](https://img.shields.io/github/stars/Azzedde/brainstormers?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/Azzedde/brainstormers) |
| [rsrini7/mermaid2gif](https://github.com/rsrini7/mermaid2gif) | Tool for converting Mermaid diagrams to animated GIFs with optional AI-powered diagram generation | ![GitHub stars](https://img.shields.io/github/stars/rsrini7/mermaid2gif?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/rsrini7/mermaid2gif) |
| [zamalali/langchain-code](https://github.com/zamalali/langchain-code) | Multi-LLM CLI tool with ReAct & Deep modes for code analysis, feature implementation, and bug fixing | ![GitHub stars](https://img.shields.io/github/stars/zamalali/langchain-code?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/zamalali/langchain-code) |
| [Mediaeater/swarm.at](https://github.com/Mediaeater/swarm-at-ledger) | Settlement protocol that hash-chains every LangGraph node execution into an immutable audit ledger with trust-tiered agent identities | ![GitHub stars](https://img.shields.io/github/stars/Mediaeater/swarm.at?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/Mediaeater/swarm.at) |
| [MOSS LangGraph](https://pypi.org/project/moss-langgraph/) | Cryptographic signing for LangGraph workflows. Add tamper-proof audit trails with ML-DSA-44 post-quantum signatures to node outputs and state transitions | [![PyPI](https://img.shields.io/pypi/v/moss-langgraph)](https://pypi.org/project/moss-langgraph/) |

<div align="center">

## 💰 Finance & Fintech

</div>

*Financial analysis, trading, banking, investment research, and business intelligence*

| Project | Description | GitHub Stars |
|---|---|---|
| [virattt/ai-hedge-fund](https://github.com/virattt/ai-hedge-fund) | Multi-agent trading system with LangChain | ![GitHub stars](https://img.shields.io/github/stars/virattt/ai-hedge-fund?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/virattt/ai-hedge-fund) |
| [sagar-n/deepagents](https://github.com/sagar-n/deepagents) | Stock research assistant with specialized analysis agents | ![GitHub stars](https://img.shields.io/github/stars/sagar-n/deepagents?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/sagar-n/deepagents) |
| [AKMessi/AI-IPO-Analyst](https://github.com/AKMessi/AI-IPO-Analyst) | IPO analysis agent with PDF parsing and market data enrichment | ![GitHub stars](https://img.shields.io/github/stars/AKMessi/AI-IPO-Analyst?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/AKMessi/AI-IPO-Analyst) |
| [johnsonhk88/AI-Bank-Statement-Document-Automation-By-LLM-And-Personal-Finanical-Analysis-Prediction](https://github.com/johnsonhk88/AI-Bank-Statement-Document-Automation-By-LLM-And-Personal-Finanical-Analysis-Prediction) | Bank statement parsing + personal finance analysis with multi-agent workflow | ![GitHub stars](https://img.shields.io/github/stars/johnsonhk88/AI-Bank-Statement-Document-Automation-By-LLM-And-Personal-Finanical-Analysis-Prediction?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/johnsonhk88/AI-Bank-Statement-Document-Automation-By-LLM-And-Personal-Finanical-Analysis-Prediction) |
| [OzorOwn/defi-mcp](https://github.com/OzorOwn/defi-mcp) | DeFi MCP server with 12 tools: real-time crypto prices, multi-chain wallet balances (9 chains), DEX quotes via Jupiter and Li.Fi, and token search across 275+ assets | ![GitHub stars](https://img.shields.io/github/stars/OzorOwn/defi-mcp?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/OzorOwn/defi-mcp) |

<div align="center">

## 🎯 Marketing

</div>

*Marketing analysis, content strategy, and promotional automation*

| Project | Description | GitHub Stars |
|---|---|---|
| [denser-org/denser-chat](https://github.com/denser-org/denser-chat) | Tool that breaks down content tasks and drafts long-form pieces | ![GitHub stars](https://img.shields.io/github/stars/denser-org/denser-chat?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/denser-org/denser-chat) |



## 🎥 Media & Podcasts

*Content creation, media processing, podcasts, multimedia generation, and voice processing*

| Project | Description | GitHub Stars |
|---|---|---|
| [souzatharsis/podcastfy](https://github.com/souzatharsis/podcastfy) | Turns multi-modal content into podcast-style dialogues | ![GitHub stars](https://img.shields.io/github/stars/souzatharsis/podcastfy?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/souzatharsis/podcastfy) |
| [wassim249/YT-Navigator](https://github.com/wassim249/YT-Navigator) | Navigate and search across YouTube channel content | ![GitHub stars](https://img.shields.io/github/stars/wassim249/YT-Navigator?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/wassim249/YT-Navigator) |
| [artnoage/Podcast](https://github.com/artnoage/Podcast) | Automated podcast pipeline from academic texts | ![GitHub stars](https://img.shields.io/github/stars/artnoage/Podcast?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/artnoage/Podcast) |
| [benjichat/voice_agent_base](https://github.com/benjichat/voice_agent_base) | Voice agent with STT/TTS and web search in a React UI | ![GitHub stars](https://img.shields.io/github/stars/benjichat/voice_agent_base?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/benjichat/voice_agent_base) |
| [von-development/voice-file-agent](https://github.com/von-development/voice-file-agent) | Voice-controlled file manager with LangGraph ReAct | ![GitHub stars](https://img.shields.io/github/stars/von-development/voice-file-agent?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/von-development/voice-file-agent) |


<div align="center">

## 🤖 Robotics & Embodied AI

</div>

*Robotics applications, embodied AI, and physical world interaction*

| Project | Description | GitHub Stars |
|---------|-------------|--------------|
| [RobotecAI/rai](https://github.com/RobotecAI/rai) | Flexible multi-agent framework for developing and deploying Embodied AI features in robotics with multi-modal interaction support | ![GitHub stars](https://img.shields.io/github/stars/RobotecAI/rai?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/RobotecAI/rai) |

<div align="center">

## 📚 RAG & Document Processing

</div>

*Retrieval-Augmented Generation, document chatbots, and knowledge base systems*

| Project | Description | GitHub Stars |
|---|---|---|
| [GiovanniPasq/agentic-rag-for-dummies](https://github.com/GiovanniPasq/agentic-rag-for-dummies) | A modular Agentic RAG built with LangGraph — learn Retrieval-Augmented Generation Agents in minutes | ![GitHub stars](https://img.shields.io/github/stars/GiovanniPasq/agentic-rag-for-dummies?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/GiovanniPasq/agentic-rag-for-dummies) |
| [Goodnight77/Just-RAG](https://github.com/Goodnight77/Just-RAG) | Agentic RAG with LangGraph + Qdrant | ![GitHub stars](https://img.shields.io/github/stars/Goodnight77/Just-RAG?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/Goodnight77/Just-RAG) |
| [IlyaRice/RAG-Challenge-2](https://github.com/IlyaRice/RAG-Challenge-2) | RAG with custom PDF parsing, parent retrieval, and reranking | ![GitHub stars](https://img.shields.io/github/stars/IlyaRice/RAG-Challenge-2?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/IlyaRice/RAG-Challenge-2) |
| [LexStack-AI/LexReviewer](https://github.com/LexStack-AI/LexReviewer) | LangGraph-powered legal PDF RAG service with hybrid vector+BM25 retrieval, streaming chat, and citation-aware answers with bounding-box references for highlighting. | ![GitHub stars](https://img.shields.io/github/stars/LexStack-AI/LexReviewer?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/LexStack-AI/LexReviewer) |
| [TAMustafa/Local_Chat_RAG](https://github.com/TAMustafa/Local_Chat_RAG) | Local RAG chat (Ollama) with sources and modern UI | ![GitHub stars](https://img.shields.io/github/stars/TAMustafa/Local_Chat_RAG?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/TAMustafa/Local_Chat_RAG) |
| [mayooear/ai-pdf-chatbot-langchain](https://github.com/mayooear/ai-pdf-chatbot-langchain) | PDF chatbot template with LangChain/LangGraph and vector storage | ![GitHub stars](https://img.shields.io/github/stars/mayooear/ai-pdf-chatbot-langchain?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/mayooear/ai-pdf-chatbot-langchain) |
| [bRAGAI/bRAG-langchain](https://github.com/bRAGAI/bRAG-langchain) | Tutorial series on RAG from basics to advanced | ![GitHub stars](https://img.shields.io/github/stars/bRAGAI/bRAG-langchain?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/bRAGAI/bRAG-langchain) |
| [catio-tech/graphqa](https://github.com/catio-tech/graphqa) | Natural language graph analysis framework for querying graphs without complex query languages | ![GitHub stars](https://img.shields.io/github/stars/catio-tech/graphqa?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/catio-tech/graphqa) |
| [zamalali/DeepGit](https://github.com/zamalali/DeepGit) | Agentic workflow for intelligent GitHub repo discovery with hybrid retrieval and re-ranking | ![GitHub stars](https://img.shields.io/github/stars/zamalali/DeepGit?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/zamalali/DeepGit) |


<div align="center">

## 🔬 Research Agents

</div>

*AI research assistants, academic tools, and automated research workflows*

| Project | Description | GitHub Stars |
|---|---|---|
| [bytedance/deer-flow](https://github.com/bytedance/deer-flow) | Deep research framework with search/crawl/Python tools | ![GitHub stars](https://img.shields.io/github/stars/bytedance/deer-flow?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/bytedance/deer-flow) |
| [duartecaldascardoso/article-explainer](https://github.com/duartecaldascardoso/article-explainer) | Multi-agent system for understanding research articles with AI-powered explanations and Swarm architecture | ![GitHub stars](https://img.shields.io/github/stars/duartecaldascardoso/article-explainer?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/duartecaldascardoso/article-explainer) |
| [MODSetter/SurfSense](https://github.com/MODSetter/SurfSense) | Research agent integrating personal KBs and external sources | ![GitHub stars](https://img.shields.io/github/stars/MODSetter/SurfSense?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/MODSetter/SurfSense) |
| [Intelligent-Internet/ii-researcher](https://github.com/Intelligent-Internet/ii-researcher) | Deep search agent with BAML, multi-provider scraping, async flows | ![GitHub stars](https://img.shields.io/github/stars/Intelligent-Internet/ii-researcher?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/Intelligent-Internet/ii-researcher) |
| [pogjester/company-research-agent](https://github.com/pogjester/company-research-agent) | Company research pipeline with streaming and filtering | ![GitHub stars](https://img.shields.io/github/stars/pogjester/company-research-agent?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/pogjester/company-research-agent) |
| [jolovicdev/shandu](https://github.com/jolovicdev/shandu) | Source evaluation and knowledge synthesis | ![GitHub stars](https://img.shields.io/github/stars/jolovicdev/shandu?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/jolovicdev/shandu) |
| [LearningCircuit/local-deep-research](https://github.com/LearningCircuit/local-deep-research) | Local deep research with multiple LLMs and web searches | ![GitHub stars](https://img.shields.io/github/stars/LearningCircuit/local-deep-research?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/LearningCircuit/local-deep-research) |
| [assafelovic/gpt-researcher](https://github.com/assafelovic/gpt-researcher) | Report-oriented research agent with citations | ![GitHub stars](https://img.shields.io/github/stars/assafelovic/gpt-researcher?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/assafelovic/gpt-researcher) |
| [Just-Curieous/Curie](https://github.com/Just-Curieous/Curie) | Agent for empirical experimentation in ML/systems | ![GitHub stars](https://img.shields.io/github/stars/Just-Curieous/Curie?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/Just-Curieous/Curie) |
| [iblameandrew/local-deepsearch-academic](https://github.com/iblameandrew/local-deepsearch-academic) | Academic paper discovery with S2 + RAPTOR indexing | ![GitHub stars](https://img.shields.io/github/stars/iblameandrew/local-deepsearch-academic?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/iblameandrew/local-deepsearch-academic) |
| [andrestorres123/breeze-agent](https://github.com/andrestorres123/breeze-agent) | Streamlined research flow inspired by STORM on LangGraph | ![GitHub stars](https://img.shields.io/github/stars/andrestorres123/breeze-agent?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/andrestorres123/breeze-agent) |
| [bernatsampera/event-deep-research](https://github.com/bernatsampera/event-deep-research) | Multi-agent biographical research system extracting structured timeline events from historical figures | ![GitHub stars](https://img.shields.io/github/stars/bernatsampera/event-deep-research?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/bernatsampera/event-deep-research) |
| [microsoft/RD-Agent](https://github.com/microsoft/RD-Agent) | R&D automation for data mining, paper analysis, model tuning | ![GitHub stars](https://img.shields.io/github/stars/microsoft/RD-Agent?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/microsoft/RD-Agent) |
| [SalesforceAIResearch/enterprise-deep-research](https://github.com/SalesforceAIResearch/enterprise-deep-research) | Steerable enterprise research stack with planner, specialized search agents, and web UI on LangGraph | ![GitHub stars](https://img.shields.io/github/stars/SalesforceAIResearch/enterprise-deep-research?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/SalesforceAIResearch/enterprise-deep-research) |
| [xyin-anl/Nodeology](https://github.com/xyin-anl/Nodeology) | Simplified scientific workflow builder | ![GitHub stars](https://img.shields.io/github/stars/xyin-anl/Nodeology?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/xyin-anl/Nodeology) |
| [alonlavian/RAGent](https://github.com/alonlavian/RAGent) | Research assistant with PDF processing and web search | ![GitHub stars](https://img.shields.io/github/stars/alonlavian/RAGent?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/alonlavian/RAGent) |
| [lgesuellip/researcher_agent](https://github.com/lgesuellip/researcher_agent) | Turns websites into LLM-ready research content with automated documentation indexing | ![GitHub stars](https://img.shields.io/github/stars/lgesuellip/researcher_agent?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/lgesuellip/researcher_agent) |




<div align="center">

## 🌍 Security & Governance

</div>

*Action verification, provenance tracking, fail-closed mechanisms, prompt injection protection*

| Project | Description | GitHub Stars |
|---|---|---|
| [LembaGang/headless-oracle-v5](https://github.com/LembaGang/headless-oracle-v5) | Fail-closed market status MCP. Pauses stateful LangGraph agents from entering retry loops during closed markets or DST shifts. | ![GitHub stars](https://img.shields.io/github/stars/LembaGang/headless-oracle-v5?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/LembaGang/headless-oracle-v5) |
| [pic-standard](https://github.com/madeinplutofabio/pic-standard) | Local-first protocol for provenance & intent verification before agent actions (fail-closed, verifiable evidence). | ![GitHub stars](https://img.shields.io/github/stars/madeinplutofabio/pic-standard?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/madeinplutofabio/pic-standard) |
| [sidclawhq/platform](https://github.com/sidclawhq/platform) | Approval and audit layer for LangGraph agents. Intercepts tool calls, evaluates them against policies, and holds them for human review before execution. Hash-chain audit trail, 13 framework integrations. Apache 2.0. | ![GitHub stars](https://img.shields.io/github/stars/sidclawhq/platform?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/sidclawhq/platform) |




<div align="center">

## 🌍 Sustainability

</div>

*Environmental impact, green technology, and sustainability analysis*

| Project | Description | GitHub Stars |
|---------|-------------|--------------|
| [vivek-suryavanshi/GreenMeGenAIApp](https://github.com/vivek-suryavanshi/GreenMeGenAIApp) | AI sustainability guide that analyzes lifestyle for carbon footprint reduction | ![GitHub stars](https://img.shields.io/github/stars/vivek-suryavanshi/GreenMeGenAIApp?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/vivek-suryavanshi/GreenMeGenAIApp) |

<div align="center">

## 📋 Templates & Starters

</div>

*Ready-to-use project templates, boilerplates, and starter kits for building LangGraph applications*

| Project | Description | GitHub Stars |
|---|---|---|
| [emanueleielo/deepagents-open-lovable](https://github.com/emanueleielo/deepagents-open-lovable) | Open-source Deep Agents implementation with Lovable platform integration for complex planning and execution workflows | ![GitHub stars](https://img.shields.io/github/stars/emanueleielo/deepagents-open-lovable?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/emanueleielo/deepagents-open-lovable) |
| [wassim249/fastapi-langgraph-agent-production-ready-template](https://github.com/wassim249/fastapi-langgraph-agent-production-ready-template) | FastAPI template for LangGraph agents (logging, persistence, security) | ![GitHub stars](https://img.shields.io/github/stars/wassim249/fastapi-langgraph-agent-production-ready-template?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/wassim249/fastapi-langgraph-agent-production-ready-template) |
| [gtesei/agentic_design_patterns](https://github.com/gtesei/agentic_design_patterns) | A comprehensive, hands-on collection of design patterns for building robust agentic AI systems using LangChain and LangGraph | ![GitHub stars](https://img.shields.io/github/stars/gtesei/agentic_design_patterns?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/gtesei/agentic_design_patterns) |
| [NicholasGoh/fastapi-mcp-langgraph-template](https://github.com/NicholasGoh/fastapi-mcp-langgraph-template) | FastAPI template with LangGraph + MCP and streaming UX | ![GitHub stars](https://img.shields.io/github/stars/NicholasGoh/fastapi-mcp-langgraph-template?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/NicholasGoh/fastapi-mcp-langgraph-template) |
| [lgesuellip/langgraph-whatsapp-agent](https://github.com/lgesuellip/langgraph-whatsapp-agent) | Template for WhatsApp agents with LangGraph and MCP | ![GitHub stars](https://img.shields.io/github/stars/lgesuellip/langgraph-whatsapp-agent?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/lgesuellip/langgraph-whatsapp-agent) |



<div align="center">

## 🏢 Workplace & Productivity

</div>

*Office automation, productivity tools, and workplace management*

| Project | Description | GitHub Stars |
|---|---|---|
| [ashumishra2104/AI_Travel_agent_Streamlit](https://github.com/ashumishra2104/AI_Travel_agent_Streamlit) | Streamlit-based AI travel agent with weather, search, currency conversion, and YouTube integration tools | ![GitHub stars](https://img.shields.io/github/stars/ashumishra2104/AI_Travel_agent_Streamlit?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/ashumishra2104/AI_Travel_agent_Streamlit) |
| [eduly-ai/eduly](https://github.com/eduly-ai/eduly) | AI-powered educational platform for personalized learning experiences and tutoring assistance | ![GitHub stars](https://img.shields.io/github/stars/eduly-ai/eduly?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/eduly-ai/eduly) |
| [emanueleielo/ciana-parrot](https://github.com/emanueleielo/ciana-parrot) | Self-hosted AI personal assistant with Telegram integration, scheduled tasks, multi-provider LLM support, and MCP server integration | ![GitHub stars](https://img.shields.io/github/stars/emanueleielo/ciana-parrot?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/emanueleielo/ciana-parrot) |
| [Clevrr-AI/Clevrr-Computer](https://github.com/Clevrr-AI/Clevrr-Computer) | Desktop task agent focused on safe execution | ![GitHub stars](https://img.shields.io/github/stars/Clevrr-AI/Clevrr-Computer?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/Clevrr-AI/Clevrr-Computer) |
| [tavily-ai/meeting-prep-agent](https://github.com/tavily-ai/meeting-prep-agent) | Meeting prep with calendars, search, and profile research | ![GitHub stars](https://img.shields.io/github/stars/tavily-ai/meeting-prep-agent?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/tavily-ai/meeting-prep-agent) |
| [temporal-cortex/mcp](https://github.com/temporal-cortex/mcp) | Deterministic calendar scheduling MCP server with LangGraph examples — datetime resolution, multi-calendar availability, and atomic booking | ![GitHub stars](https://img.shields.io/github/stars/temporal-cortex/mcp?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/temporal-cortex/mcp) |
| [zamalali/InboxHero](https://github.com/zamalali/InboxHero) | Email triage with attachment reading and reply drafting | ![GitHub stars](https://img.shields.io/github/stars/zamalali/InboxHero?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/zamalali/InboxHero) |
| [khoj-ai/khoj](https://github.com/khoj-ai/khoj) | Self-hosted second brain for docs and web | ![GitHub stars](https://img.shields.io/github/stars/khoj-ai/khoj?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/khoj-ai/khoj) |
| [raj-maharajwala/AI_Agent_Chatbot_Synapse](https://github.com/raj-maharajwala/AI_Agent_Chatbot_Synapse) | Bundle of search/productivity/data agents with UI | ![GitHub stars](https://img.shields.io/github/stars/raj-maharajwala/AI_Agent_Chatbot_Synapse?style=social)<br>![Last commit](https://img.shields.io/github/last-commit/raj-maharajwala/AI_Agent_Chatbot_Synapse) |


---

<div align="center">

## 📚 Learning Resources

</div>


### Official — LangGraph Academy
- **[Introduction to LangGraph](https://academy.langchain.com/courses/intro-to-langgraph)** — Core concepts: graphs, routers, agents, state, memory, streaming, deployment.
- **[Ambient Agents (Project)](https://academy.langchain.com/courses/ambient-agents)** — Build an email assistant. Includes agent evals and LangSmith integration.
- **[Deep Research (Project)](https://academy.langchain.com/courses/deep-research-with-langgraph)** — Build a multi-agent research workflow with supervisors and MCP.
- **[Agent Observability & Evaluations](https://academy.langchain.com/courses/intro-to-langsmith)** — Tracing, testing, evals, prompt iteration, human feedback, production monitoring.

### Community Courses
- **[LangGraph — Develop LLM-Powered AI Agents (Udemy)](https://www.udemy.com/course/langgraph/)** — Practical LangGraph agent patterns. Instructor: [emarco177](https://github.com/emarco177).


<div align="center">

<div align="center">

## 📖 Additional Resources

</div>

*A compact list of tutorials, workshops, blogs, and case studies you can keep growing over time.*

| Name | Type | Description |
|---|---|---|
| [Ava WhatsApp Agent Course](https://github.com/neural-maze/ava-whatsapp-agent-course) | Course | Build a WhatsApp agent with voice processing, image generation, and long-term memory using LangGraph. |
| [GenAI Agents](https://github.com/NirDiamant/GenAI_Agents) | Examples | A collection of agent implementation examples and patterns. |
| [RAG Techniques](https://github.com/NirDiamant/RAG_Techniques) | Tutorials | Several RAG implementations and step-by-step walkthroughs. |
| [Grounding RAG Applications Workshop](https://github.com/carlyrichmond/webdevcon-grounding-rag-applications-workshop) | Workshop | Hands-on RAG chatbot + travel planning agents with JavaScript and Elasticsearch. |
| [LinkedIn — Practical Text-to-SQL](https://www.linkedin.com/blog/engineering/ai/practical-text-to-sql-for-data-analytics) | Blog | Search & discovery and analytics use cases with text-to-SQL at LinkedIn. |
| [Uber — AI-Driven Developer Productivity](https://dpe.org/sessions/ty-smith-adam-huda/this-year-in-ubers-ai-driven-developer-productivity-revolution/) | Talk | How Uber boosts developer productivity and code generation with AI. |
| [GitLab — Duo Workflow](https://handbook.gitlab.com/handbook/engineering/architecture/design-documents/duo_workflow/) | Docs | Architecture documentation for code-generation workflows. |
| [Klarna — Domain Copilot](https://blog.langchain.dev/customers-klarna/) | Case Study | Production copilot for domain-specific tasks. |
| [Rakuten — From Hype to Real Tools](https://rakuten.today/blog/from-ai-hype-to-real-world-tools-rakuten-teams-up-with-langchain.html) | Blog | Partnership details and production applications with LangChain. |
| [Minimal — Multi-Agent Customer Support](https://blog.langchain.dev/how-minimal-built-a-multi-agent-customer-support-system-with-langgraph-langsmith/) | Case Study | Customer support system built with LangGraph and LangSmith. |
| [Komodo Health — Enterprise Assistant](https://www.komodohealth.com/perspectives/new-gen-ai-assistant-empowers-the-enterprise/) | Blog | Enterprise assistant enabling domain workflows in healthcare. |
| [OpenRecovery — Clinical Copilot](https://blog.langchain.dev/customers-openrecovery/) | Case Study | Clinical copilot for healthcare operations. |
| [AppFolio — Embedded Copilots](https://blog.langchain.dev/customers-appfolio/) | Case Study | Product-embedded copilots in a real-estate platform. |
| [Cisco Outshift — DevOps Agent via REST](https://outshift.cisco.com/blog/build-react-agent-application-for-devops-tasks-using-rest-apis) | Blog | Building a React agent app for DevOps tasks using REST APIs. |
| [Elastic — Security GenAI Features](https://www.elastic.co/blog/elastic-security-generative-ai-features) | Blog | Generative AI features for security workflows. |
| [Infor — Product Copilots & Support](https://blog.langchain.dev/customers-infor/) | Case Study | Embedded product experiences, support, and copilots. |
| [AirTop — Browser Automation for Agents](https://blog.langchain.dev/customers-airtop/) | Case Study | Agentic browser automation platform. |
| [Athena Intelligence — Research & Summarization](https://blog.langchain.dev/customers-athena-intelligence/) | Case Study | Research and summarization workflows in production. |
| [Captide — Agentic Equity Research](https://blog.langchain.dev/how-captide-is-redefining-equity-research-with-agentic-workflows-built-on-langgraph-and-langsmith/) | Case Study | Equity research using LangGraph + LangSmith agentic workflows. |

---

<div align="center">

## 👥 Communities

</div>

| Name | Type | Description |
|---|---|---|
| [LangChain Community](https://www.langchain.com/join-community) | Official Community | Central hub for announcements, discussions, events, and channels to connect with the LangChain/LangGraph ecosystem. |
| [LangChain Forum](https://forum.langchain.com/) | Forum | Community discussion forum for asking questions, sharing ideas, and connecting with other LangChain and LangGraph builders. |

<div align="center">

---

## 🤝 Contributing

</div>

We welcome additions and fixes! Please read the **[Contributing Guide](CONTRIBUTING.md)** for the submission process, formatting rules, and category guidelines before opening an issue or pull request.



---

<div align="center">

## 🙏 Acknowledgments

</div>

Special thanks to the [@langchain-ai](https://github.com/langchain-ai) team for building an outstanding framework and ecosystem that enables developers to create powerful AI applications.
