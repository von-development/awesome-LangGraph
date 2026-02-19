# 🦜🕸️ Awesome LangGraph & LangChain Ecosystem ![Awesome](https://awesome.re/badge.svg) ![Last Updated](https://img.shields.io/github/last-commit/von-development/awesome-LangGraph)

> The definitive index of frameworks, templates, and real-world projects for building **stateful, tool-using AI agents** with the LangChain + LangGraph stack.

Whether you’re prototyping your first agent or shipping production workflows, this list maps the whole landscape—from **core libraries** and **platform tooling** (LangGraph Platform, LangSmith) to **integrations**, **official examples**, and **community projects** organized by domain.

**What you’ll find**
- Core frameworks: LangChain, LangGraph, LangSmith, and LangGraph Platform
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
    - [Available Files](#available-files)
    - [Format Differences](#format-differences)
  - [🦜 LangGraph 🕸️](#-langgraph-️)
    - [Available Files](#available-files-1)
    - [Format Differences](#format-differences-1)
    - [Usage with IDEs](#usage-with-ides)
  - [🦜 LangSmith 🛠️](#-langsmith-️)
  - [🦜 LangGraph Platform 🚀](#-langgraph-platform-)
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

**🛠️ LangSmith** - Helpful for agent evaluations and observability. Debug poor-performing LLM app runs, evaluate agent trajectories, gain visibility in production, and improve performance over time.

**🚀 LangGraph Platform** - Deploy and scale agents effortlessly with a purpose-built deployment platform for long running, stateful workflows. Discover, reuse, configure, and share agents across teams — and iterate quickly with visual prototyping in LangGraph Studio.

**🤝 LangChain Integrations & Partners** - Third-party integrations and provider packages that extend LangChain's capabilities across the AI ecosystem. These integration packages provide standardized interfaces to work with popular AI services, databases, and tools.



> [!TIP]
> **LangChain v1.0** introduces a major architectural shift where **all LangChain agents are now built on top of LangGraph**. This provides better control, state management, and debugging capabilities for agent workflows. The v1.0 documentation reflects this new LangGraph-first approach to agent development.

<n></n>

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
| **🎯 [Context Engineering](https://docs.langchain.com/oss/python/langchain/context-engineering)** | Techniques for optimizing prompts and context management |
| **📋 [Structured Output](https://docs.langchain.com/oss/python/langchain/structured-output)** | Generate responses in specific formats and schemas |
| **🔗 [Model Context Protocol (MCP)](https://docs.langchain.com/oss/python/langchain/mcp)** | Standardized tool integration and context sharing |
| **👥 Human-in-the-Loop** | Interactive agent workflows with human oversight (*Coming Soon*) |
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
<summary><strong>▫️ LangChain Documentation ▫️</strong></summary>

Access the official LangChain documentation across different versions and languages:

<div align="center">

| Version | Python | JavaScript | Status |
|---------|--------|------------|--------|
| **v1.0 Alpha** | [Alpha Docs](https://docs.langchain.com/oss/python/langchain/overview) | [Alpha Docs](https://docs.langchain.com/oss/javascript/langchain/) | 🚧 Alpha |
| **v0.3** | [Stable Docs](https://python.langchain.com/docs/introduction/) | [Stable Docs](https://js.langchain.com/docs/introduction/) | ✅ Stable |

</div>
</details>

<details>
<summary><strong>▫️ LangChain llms.txt Files ▫️</strong></summary>

**AI-accessible documentation format for LLMs and IDEs** - Documentation files in llms.txt format that allow large language models and agents to access programming documentation and APIs, particularly useful within integrated development environments.

### Available Files

| Language | llms.txt | llms-full.txt |
|----------|----------|---------------|
| **Python** | [python.langchain.com/llms.txt](https://python.langchain.com/llms.txt) | N/A |
| **JavaScript** | [js.langchain.com/llms.txt](https://js.langchain.com/llms.txt) | N/A |

### Format Differences
- **`llms.txt`** - Index file with links and brief descriptions requiring navigation for detailed information
- **`llms-full.txt`** - Complete content in a single file, but may exceed LLM context windows

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
| **👥 Human-in-the-Loop** | Seamless human oversight and intervention capabilities | Approval workflows, manual interventions, state inspection |
| **⏰ Time Travel** | Navigate through agent execution history and states | State debugging, execution replay, historical analysis |
| **🧠 Add and Manage Memory** | Comprehensive memory management for stateful agents | Short-term working memory, long-term persistence, memory optimization |
| **📊 Subgraphs** | Nested graph structures for complex workflow composition | Modular workflows, reusable components, hierarchical execution |

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
<summary><strong> ▫️ LangGraph Starter Templates ▫️</strong></summary>

Get started quickly with LangGraph using the CLI command `langgraph new` to choose from pre-built templates:

| Template | Description | Python | TypeScript |
|----------|-------------|--------|------------|
| **New Project** | Basic chatbot with memory | [new-langgraph-project](https://github.com/langchain-ai/new-langgraph-project) | [new-langgraphjs-project](https://github.com/langchain-ai/new-langgraphjs-project) |
| **ReAct Agent** | Tool-using agent framework | [react-agent](https://github.com/langchain-ai/react-agent) | [react-agent-js](https://github.com/langchain-ai/react-agent-js) |
| **Memory Agent** | Cross-thread memory persistence | [memory-agent](https://github.com/langchain-ai/memory-agent) | [memory-agent-js](https://github.com/langchain-ai/memory-agent-js) |
| **Retrieval Agent** | Knowledge-based QA system | [retrieval-agent-template](https://github.com/langchain-ai/retrieval-agent-template) | [retrieval-agent-template-js](https://github.com/langchain-ai/retrieval-agent-template-js) |
| **Data Enrichment** | Web search & data organization | [data-enrichment](https://github.com/langchain-ai/data-enrichment) | [data-enrichment-js](https://github.com/langchain-ai/data-enrichment-js) |

</details>

<details>
<summary><strong> ▫️ LangGraph Documentation ▫️</strong></summary>

Access the official LangGraph documentation across different languages:

<div align="center">

| Language | Framework | Documentation |
|----------|-----------|---------------|
| **Python** | LangGraph | [Python Docs](https://docs.langchain.com/langgraph/overview) |
| **JavaScript** | LangGraph.js | [JavaScript Docs](https://docs.langchain.com/langgraphjs/overview) |

</div>
</details>

<details>
<summary><strong>▫️ LangGraph llms.txt Files ▫️</strong></summary>

**AI-accessible documentation format for LLMs and IDEs** - Documentation files in llms.txt format that allow large language models and agents to access programming documentation and APIs, particularly useful within integrated development environments.

### Available Files

| Language | llms.txt | llms-full.txt |
|----------|----------|---------------|
| **Python** | [langchain-ai.github.io/langgraph/llms.txt](https://langchain-ai.github.io/langgraph/llms.txt) | [langchain-ai.github.io/langgraph/llms-full.txt](https://langchain-ai.github.io/langgraph/llms-full.txt) |
| **JavaScript** | [langchain-ai.github.io/langgraphjs/llms.txt](https://langchain-ai.github.io/langgraphjs/llms.txt) | [langchain-ai.github.io/langgraphjs/llms-full.txt](https://langchain-ai.github.io/langgraphjs/llms-full.txt) |

### Format Differences
- **`llms.txt`** - Index file with links and brief descriptions requiring navigation for detailed information
- **`llms-full.txt`** - Complete content in a single file, but may exceed LLM context windows

### Usage with IDEs
**With IDEs (Cursor, Windsurf)**: Add `llms-full.txt` as custom documentation. The IDE automatically chunks and indexes content using RAG.

**With MCP Server**: Use the [mcpdoc server](https://github.com/langchain-ai/mcpdoc) to integrate `llms.txt` into tools like Cursor, Windsurf, Claude, and Claude Code.

> **⚠️ Review Output**: Even with up-to-date documentation, current models may not always generate correct code. Always review generated code before production use.

</details>



<n></n>

---

<div align="center">

## 🦜 LangSmith 🛠️

</div>

**LangSmith** is a platform for building production-grade LLM applications with comprehensive observability, evaluation, and prompt engineering capabilities. It's framework agnostic and works with or without LangChain's open source frameworks.




<details>
<summary><strong>🔹 Core Features 🔹</strong></summary>

| Feature | Description | Key Capabilities |
|---------|-------------|-----------------|
| **📊 Tracing** | Gain visibility into each step your application takes | Debug faster, understand application flow, execution monitoring |
| **📈 Evaluation** | Measure quality of applications over time | Automated testing, quality measurement, performance tracking |
| **✏️ Prompt Testing** | Iterate on prompts with version control | Prompt optimization, collaboration, automatic versioning |
| **🏢 Workspace Management** | Team collaboration and project organization | Admin settings, team collaboration, project configuration |

</details>

<details>
<summary><strong>🔹 LangSmith SDK 🔹</strong></summary>

| Package | Python | TypeScript | Description |
|---------|--------|------------|-------------|
| **LangSmith Client SDK** | [`langsmith`](https://github.com/langchain-ai/langsmith-sdk) | [`langsmith`](https://github.com/langchain-ai/langsmith-sdk) | Official SDK for LangSmith platform integration |

</details>

<details>
<summary><strong>🔹 LangSmith Documentation 🔹</strong></summary>

Access the official LangSmith platform documentation:

<div align="center">

| Platform | Documentation |
|----------|---------------|
| **LangSmith** | [Platform Docs](https://docs.langchain.com/langsmith/home) |

</div>
</details>

<n></n>

> [!TIP]
> **Get started with LangSmith for free!** Sign up at [langchain.com/langsmith](https://www.langchain.com/langsmith) and follow the [quickstart guide](https://docs.langchain.com/langsmith/observability-quickstart) to add tracing and monitoring to your LLM applications in minutes.

<n></n>



---

<div align="center">

## 🦜 LangGraph Platform 🚀

</div>

**LangGraph Platform** is a comprehensive solution for deploying and managing agentic applications at scale. It provides production-ready infrastructure, developer tools, and management capabilities for LangGraph applications.

<div align="center">
  <img src="static/langgraph_platform.png" width="500" alt="LangGraph Platform">
  <p><sub>Source: <a href="https://docs.langchain.com/langgraph-platform/overview/">LangGraph Platform Documentation</a></sub></p>
</div>

*In the dropdowns below, you'll find a summary of each component's key concepts and links to the official documentation.*

<details>
<summary><strong>🔺 LangGraph Server 🔺</strong></summary>

**API platform for creating and managing agent-based applications.** Built on the concept of assistants (agents configured for specific tasks) with built-in persistence and task queue for production deployments.

**Key Features:**
- Agent management (assistants, threads, runs)
- Built-in persistence with PostgreSQL
- Task queue with Redis
- Background processing and real-time interactions
- Cron jobs and webhooks support
- Enterprise deployment options (Cloud, Hybrid, Self-hosted)

**Documentation:** [LangGraph Server](https://docs.langchain.com/langgraph-platform/langgraph-server)

</details>

<details>
<summary><strong> 🔺LangGraph CLI 🔺</strong></summary>

**Multi-platform command-line tool for building and running LangGraph API servers locally.** Includes all API endpoints and services required for agent development and deployment.

**Key Commands:**
- `langgraph build` - Build Docker images for deployment
- `langgraph dev` - Start lightweight development server
- `langgraph up` - Start local Docker container instance
- `langgraph dockerfile` - Generate custom Dockerfiles

**Documentation:** [LangGraph CLI](https://docs.langchain.com/langgraph-platform/langgraph-cli)

</details>

<details>
<summary><strong>🔺 LangGraph Studio 🔺</strong></summary>

**Specialized agent IDE for visualization, interaction, and debugging of agentic systems.** Connects to LangGraph Server and integrates with LangSmith for comprehensive development experience.

**Key Features:**
- Graph architecture visualization
- Interactive agent testing and debugging
- Assistant and thread management
- Prompt iteration and experimentation
- Time travel debugging and state inspection
- LangSmith integration for tracing and evaluation

**Documentation:** [LangGraph Studio](https://docs.langchain.com/langgraph-platform/langgraph-studio)

</details>

<details>
<summary><strong>🔺 Python/JS SDK 🔺</strong></summary>

**Programmatic interfaces for interacting with deployed LangGraph applications.** Provides both synchronous and asynchronous clients for comprehensive API access.

**Key Features:**
- Full API access to LangGraph Server
- Synchronous and asynchronous client support
- TypeScript support with type safety
- React hooks for frontend integration
- State management and streaming support

**Documentation:** [Python SDK](https://docs.langchain.com/langgraph-platform/sdk) | [JavaScript SDK](https://docs.langchain.com/langgraph-platform/reference-overview)

</details>

<details>
<summary><strong>🔺 Remote Graph 🔺</strong></summary>

**Interface for interacting with deployed LangGraph applications as if they were running locally.** Seamlessly bridge local development with production deployments.

**Key Features:**
- Local-like interaction with remote deployments
- Compatible with existing LangGraph APIs
- Assistant and graph ID support
- Transparent remote execution
- Development workflow integration

**Documentation:** [Remote Graph](https://docs.langchain.com/langgraph-platform/use-remote-graph)

</details>

<details>
<summary><strong>🔺 Control Plane 🔺</strong></summary>

**Management interface for creating and updating LangGraph Server deployments.** Provides UI and APIs for deployment configuration and administration.

**Key Features:**
- Deployment creation and management
- Configuration and environment settings
- Database provisioning (automatic PostgreSQL setup)
- Team collaboration and access control
- API orchestration for CI/CD workflows

**Documentation:** [Control Plane](https://docs.langchain.com/langgraph-platform/control-plane)

</details>

<details>
<summary><strong>🔺 Data Plane 🔺</strong></summary>

**Runtime infrastructure encompassing LangGraph Servers and supporting components.** Includes all infrastructure required for production agent deployments.

**Key Infrastructure:**
- LangGraph Server instances
- PostgreSQL databases for persistence
- Redis for task queue management
- Secrets store and autoscalers
- Listener applications for Control Plane updates

**Documentation:** [Data Plane](https://docs.langchain.com/langgraph-platform/data-plane)

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
<summary><strong>🔸 Embedding Models 🔸</strong></summary>

**Transform raw text into fixed-length vectors that capture semantic meaning.** Enable machines to compare and search text based on meaning rather than exact words. Essential for RAG applications and semantic search.

- **Python**: [Browse providers](https://docs.langchain.com/oss/python/integrations/text_embedding)
- **JavaScript**: [Browse providers](https://docs.langchain.com/oss/javascript/integrations/text_embedding)

</details>

<details>
<summary><strong>🔸 Vector Stores 🔸</strong></summary>

**Databases optimized for storing and querying high-dimensional vectors using similarity metrics.** Used with embedding models to enable semantic search, document retrieval, and knowledge base applications.

- **Python**: [Browse providers](https://docs.langchain.com/oss/python/integrations/vectorstores)
- **JavaScript**: [Browse providers](https://docs.langchain.com/oss/javascript/integrations/vectorstores)

</details>

<details>
<summary><strong>🔸 Document Loaders 🔸</strong></summary>

**Integrations for ingesting data from hundreds of sources.** Including PDFs, websites, databases, APIs, and cloud services. Transform diverse data formats into LangChain Document objects for processing.

- **Python**: [Browse providers](https://docs.langchain.com/oss/python/integrations/document_loaders)
- **JavaScript**: [Browse providers](https://docs.langchain.com/oss/javascript/integrations/document_loaders)

</details>

<details>
<summary><strong>🔸 Tools & Toolkits 🔸</strong></summary>

**Enable agents to interact with external systems.** Define input schemas for tool calling and executing actions. Support web search, database queries, file operations, and API integrations.

- **Python**: [Browse providers](https://docs.langchain.com/oss/python/integrations/tools)
- **JavaScript**: [Browse providers](https://docs.langchain.com/oss/javascript/integrations/tools)

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

- **Python**: [Browse providers](https://docs.langchain.com/oss/python/integrations/text_splitters)
- **JavaScript**: [Browse providers](https://docs.langchain.com/oss/javascript/integrations/text_splitters)

</details>

<details>
<summary><strong>🔸 Key-Value Stores 🔸</strong></summary>

**Simple storage interfaces for caching and state management.** Support caching embeddings, storing application state, and managing key-value data with various backends including Redis, file systems, and in-memory storage.

- **Python**: [Browse providers](https://docs.langchain.com/oss/python/integrations/stores)
- **JavaScript**: [Browse providers](https://docs.langchain.com/oss/javascript/integrations/stores)

</details>

> [!TIP]
> **Easy Installation**: You can easily install integration packages using:
> - **Python**: `pip install langchain-{provider}` (e.g., `langchain-openai`, `langchain-anthropic`)  
> - **JavaScript**: `npm install @langchain/{provider}` (e.g., `@langchain/openai`, `@langchain/anthropic`)

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
| [souvikmajumder26/Multi-Agent-Medical-Assistant](https://github.com/souvikmajumder26/Multi-Agent-Medical-Assistant) | AI-powered multi-agent system for medical diagnosis, research, and patient interaction, featuring LLMs, RAG, and human-in-the-loop validation | ![GitHub stars](https://img.shields.io/github/stars/souvikmajumder26/Multi-Agent-Medical-Assistant?style=social) |
| [ArcInstitute/SRAgent](https://github.com/ArcInstitute/SRAgent) | Multi-agent framework for automating genomic research and RNA sequencing workflows from scientific databases | ![GitHub stars](https://img.shields.io/github/stars/ArcInstitute/SRAgent?style=social) |

<div align="center">

## 🌐 Web Automation & Scraping

</div>

*Browser control, web task automation, and data extraction*

| Project | Description | GitHub Stars |
|---|---|---|
| [hrithikkoduri/WebRover](https://github.com/hrithikkoduri/WebRover) | Autonomous agent for automating web tasks and research | ![GitHub stars](https://img.shields.io/github/stars/hrithikkoduri/WebRover?style=social) |
| [esinecan/agentic-ai-browser](https://github.com/esinecan/agentic-ai-browser) | Web automation agent with behavioral caching, DOM fidelity, and success pattern recording | ![GitHub stars](https://img.shields.io/github/stars/esinecan/agentic-ai-browser?style=social) |
| [browser-use/browser-use](https://github.com/browser-use/browser-use) | Library for AI agents to control websites and automate tasks | ![GitHub stars](https://img.shields.io/github/stars/browser-use/browser-use?style=social) |
| [stanford-mast/blast](https://github.com/stanford-mast/blast) | High-performance serving engine for browser-augmented LLM applications with auto-scaling and OpenAI-compatible API | ![GitHub stars](https://img.shields.io/github/stars/stanford-mast/blast?style=social) |
| [ScrapeGraphAI/scrapecraft](https://github.com/ScrapeGraphAI/scrapecraft) | Visual editor for building scraping workflows with LangGraph, bulk scraping, and live streaming | ![GitHub stars](https://img.shields.io/github/stars/ScrapeGraphAI/scrapecraft?style=social) |
| [nickhawn/news-agent](https://github.com/nickhawn/news-agent) | News crawler that personalizes daily summaries with Tavily and memory | ![GitHub stars](https://img.shields.io/github/stars/nickhawn/news-agent?style=social) |

<div align="center">

## 📊 Business Intelligence & Market Research

</div>

*Business analysis, market research, and strategic intelligence tools*

| Project | Description | GitHub Stars |
|---|---|---|
| [oba2311/analyst_agent](https://github.com/oba2311/analyst_agent) | Marketing analysis agent with trend/sentiment analysis and report generation | ![GitHub stars](https://img.shields.io/github/stars/oba2311/analyst_agent?style=social) |
| [muratcankoylan/AI-Investigator](https://github.com/muratcankoylan/AI-Investigator) | Agent that discovers and analyzes enterprise AI case studies | ![GitHub stars](https://img.shields.io/github/stars/muratcankoylan/AI-Investigator?style=social) |


<div align="center">

## 🖥️ Chat Interfaces & GUIs

</div>

*Frontend applications, chat interfaces, and graphical user interfaces for AI agents*

| Project | Description | GitHub Stars |
|---|---|---|
| [GaiZhenbiao/ChuanhuChatGPT](https://github.com/GaiZhenbiao/ChuanhuChatGPT) | GUI for ChatGPT/LLMs with agent support, web search, and knowledge base features | ![GitHub stars](https://img.shields.io/github/stars/GaiZhenbiao/ChuanhuChatGPT?style=social) |
| [CopilotKit/open-multi-agent-canvas](https://github.com/CopilotKit/open-multi-agent-canvas) | Multi-agent chat interface with travel/research examples and MCP servers | ![GitHub stars](https://img.shields.io/github/stars/CopilotKit/open-multi-agent-canvas?style=social) |
| [teddynote-lab/LangConnect-Client](https://github.com/teddynote-lab/LangConnect-Client) | Streamlit RAG client with document management, semantic/hybrid search, and MCP integration | ![GitHub stars](https://img.shields.io/github/stars/teddynote-lab/LangConnect-Client?style=social) |

<div align="center">

## ☁️ Cloud & DevOps

</div>

*Cloud infrastructure management, deployment automation, and cloud resource management*

| Project | Description | GitHub Stars |
|---------|-------------|--------------|
| [eosho/ARMA](https://github.com/eosho/ARMA) | Azure Resource Management Assistant with multi-agent architecture for resource provisioning and ARM template validation | ![GitHub stars](https://img.shields.io/github/stars/eosho/ARMA?style=social) |

<div align="center">

## 🤖 Coding/Dev Agents

</div>

*AI agents specifically designed for software development, code generation, and programming assistance*

| Project | Description | GitHub Stars |
|---------|-------------|--------------|
| [KodyKendall/LlamaBot](https://github.com/KodyKendall/LlamaBot) | Web development coding agent for creating HTML/CSS/JavaScript projects and business landing pages | ![GitHub stars](https://img.shields.io/github/stars/KodyKendall/LlamaBot?style=social) |
| [AbhinavTheDev/coding-agent](https://github.com/AbhinavTheDev/coding-agent) | Development tool that uses LangGraph agents to aid coding workflow with natural language | ![GitHub stars](https://img.shields.io/github/stars/AbhinavTheDev/coding-agent?style=social) |
| [langtalks/swe-agent](https://github.com/langtalks/swe-agent) | Software engineering multi-agent system with researcher and developer agents for automated code implementation | ![GitHub stars](https://img.shields.io/github/stars/langtalks/swe-agent?style=social) |

<div align="center">

## 🛎️ Customer Ops

</div>

*Customer support, CRM systems, service management, and customer interaction automation*

| Project | Description | GitHub Stars |
|---|---|---|
| [kargarisaac/telegram_link_summarizer_agent](https://github.com/kargarisaac/telegram_link_summarizer_agent) | Telegram bot that summarizes shared links using LangGraph and multi-tool extraction | ![GitHub stars](https://img.shields.io/github/stars/kargarisaac/telegram_link_summarizer_agent?style=social) |
| [gotohuman/gotohuman-langgraph-lead-example](https://github.com/gotohuman/gotohuman-langgraph-lead-example) | Sales email drafting with human-in-the-loop review | ![GitHub stars](https://img.shields.io/github/stars/gotohuman/gotohuman-langgraph-lead-example?style=social) |
| [multinear-demo/demo-bank-support-lc-py](https://github.com/multinear-demo/demo-bank-support-lc-py) | Banking support chatbot with RAG to reduce hallucinations | ![GitHub stars](https://img.shields.io/github/stars/multinear-demo/demo-bank-support-lc-py?style=social) |
| [tilotech/identity-rag-customer-insights-chatbot](https://github.com/tilotech/identity-rag-customer-insights-chatbot) | Customer insights chatbot that creates golden records for context-aware replies | ![GitHub stars](https://img.shields.io/github/stars/tilotech/identity-rag-customer-insights-chatbot?style=social) |
| [raminmohammadi/ai-agent-smart-assist](https://github.com/raminmohammadi/ai-agent-smart-assist) | Knowledge base + classification + Q&A for support teams (FAISS + RAG) | ![GitHub stars](https://img.shields.io/github/stars/raminmohammadi/ai-agent-smart-assist?style=social) |



<div align="center">

## 📊 Data Platforms  

</div>

*Data analysis, visualization, business intelligence, and data processing agents*

| Project | Description | GitHub Stars |
|---|---|---|
| [starpig1129/AI-Data-Analysis-MultiAgent](https://github.com/starpig1129/AI-Data-Analysis-MultiAgent) | Multi-agent data analysis with visualization and report generation | ![GitHub stars](https://img.shields.io/github/stars/starpig1129/AI-Data-Analysis-MultiAgent?style=social) |
| [project-ryoma/ryoma](https://github.com/project-ryoma/ryoma) | Data agent framework for analysis, engineering, and visualization with LangChain integration | ![GitHub stars](https://img.shields.io/github/stars/project-ryoma/ryoma?style=social) |

<div align="center">

## 🧮 Data Science 

</div>

*Machine learning, statistical analysis, and data science workflow automation*

| Project | Description | GitHub Stars |
|---------|-------------|--------------|
| [business-science/ai-data-science-team](https://github.com/business-science/ai-data-science-team) | AI-powered data science team for common tasks | ![GitHub stars](https://img.shields.io/github/stars/business-science/ai-data-science-team?style=social) |
| [RichardKaranuMbuti/ScienceBridge](https://github.com/RichardKaranuMbuti/ScienceBridge) | Scientific research accelerator that analyzes datasets, generates hypotheses, and validates them through code | ![GitHub stars](https://img.shields.io/github/stars/RichardKaranuMbuti/ScienceBridge?style=social) |


<div align="center">

## 🛠️ Developer Tools

</div>

*Development frameworks, toolkits, and development infrastructure*

| Project | Description | GitHub Stars |
|---|---|---|
| [sanjeed5/ai-conversation-simulator](https://github.com/sanjeed5/ai-conversation-simulator) | Simulated conversations to test assistants; LangSmith integration | ![GitHub stars](https://img.shields.io/github/stars/sanjeed5/ai-conversation-simulator?style=social) |
| [JoshuaC215/agent-service-toolkit](https://github.com/JoshuaC215/agent-service-toolkit) | Toolkit for deploying agents with FastAPI and Streamlit | ![GitHub stars](https://img.shields.io/github/stars/JoshuaC215/agent-service-toolkit?style=social) |
| [HyperbolicLabs/Hyperbolic-AgentKit](https://github.com/HyperbolicLabs/Hyperbolic-AgentKit) | Agent kit with blockchain/compute features | ![GitHub stars](https://img.shields.io/github/stars/HyperbolicLabs/Hyperbolic-AgentKit?style=social) |
| [googleapis/genai-toolbox](https://github.com/googleapis/genai-toolbox) | Infra for agent ↔ DB connectivity (security, observability, pooling) | ![GitHub stars](https://img.shields.io/github/stars/googleapis/genai-toolbox?style=social) |
| [Darwin-lfl/langmanus](https://github.com/Darwin-lfl/langmanus) | Automation framework with web search, crawling, Python execution | ![GitHub stars](https://img.shields.io/github/stars/Darwin-lfl/langmanus?style=social) |
| [hinthornw/trustcall](https://github.com/hinthornw/trustcall) | Tenacious tool calling on LangGraph | ![GitHub stars](https://img.shields.io/github/stars/hinthornw/trustcall?style=social) |
| [andrestorres123/delve](https://github.com/andrestorres123/delve) | Taxonomy generator for unstructured data | ![GitHub stars](https://img.shields.io/github/stars/andrestorres123/delve?style=social) |
| [Bessouat40/RAGLight](https://github.com/Bessouat40/RAGLight) | Modular RAG/Agentic RAG library for multiple providers | ![GitHub stars](https://img.shields.io/github/stars/Bessouat40/RAGLight?style=social) |
| [teddynote-lab/langgraph-mcp-agents](https://github.com/teddynote-lab/langgraph-mcp-agents) | MCP integration toolkit for LangGraph agents | ![GitHub stars](https://img.shields.io/github/stars/teddynote-lab/langgraph-mcp-agents?style=social) |
| [cryxnet/deepmcpagent](https://github.com/cryxnet/deepmcpagent) | MCP-first agent framework (LangChain/LangGraph) over HTTP/SSE | ![GitHub stars](https://img.shields.io/github/stars/cryxnet/deepmcpagent?style=social) |
| [Azzedde/brainstormers](https://github.com/Azzedde/brainstormers) | Curated chains for structured brainstorming | ![GitHub stars](https://img.shields.io/github/stars/Azzedde/brainstormers?style=social) |
| [zamalali/langchain-code](https://github.com/zamalali/langchain-code) | Multi-LLM CLI tool with ReAct & Deep modes for code analysis, feature implementation, and bug fixing | ![GitHub stars](https://img.shields.io/github/stars/zamalali/langchain-code?style=social) |
| [Mediaeater/swarm.at](https://github.com/Mediaeater/swarm-at-ledger) | Settlement protocol that hash-chains every LangGraph node execution into an immutable audit ledger with trust-tiered agent identities | ![GitHub stars](https://img.shields.io/github/stars/Mediaeater/swarm.at?style=social) |
| [mosscomputing/moss-langgraph](https://pypi.org/project/moss-langgraph/) | Cryptographic signing for LangGraph workflows. Add tamper-proof audit trails with ML-DSA-44 post-quantum signatures to node outputs and state transitions | ![GitHub stars](https://img.shields.io/github/stars/mosscomputing/moss-langgraph?style=social) |

<div align="center">

## 💰 Finance & Fintech

</div>

*Financial analysis, trading, banking, investment research, and business intelligence*

| Project | Description | GitHub Stars |
|---|---|---|
| [virattt/ai-hedge-fund](https://github.com/virattt/ai-hedge-fund) | Multi-agent trading system with LangChain | ![GitHub stars](https://img.shields.io/github/stars/virattt/ai-hedge-fund?style=social) |
| [sagar-n/deepagents](https://github.com/sagar-n/deepagents) | Stock research assistant with specialized analysis agents | ![GitHub stars](https://img.shields.io/github/stars/sagar-n/deepagents?style=social) |
| [AKMessi/AI-IPO-Analyst](https://github.com/AKMessi/AI-IPO-Analyst) | IPO analysis agent with PDF parsing and market data enrichment | ![GitHub stars](https://img.shields.io/github/stars/AKMessi/AI-IPO-Analyst?style=social) |
| [johnsonhk88/AI-Bank-Statement-Document-Automation-By-LLM-And-Personal-Finanical-Analysis-Prediction](https://github.com/johnsonhk88/AI-Bank-Statement-Document-Automation-By-LLM-And-Personal-Finanical-Analysis-Prediction) | Bank statement parsing + personal finance analysis with multi-agent workflow | ![GitHub stars](https://img.shields.io/github/stars/johnsonhk88/AI-Bank-Statement-Document-Automation-By-LLM-And-Personal-Finanical-Analysis-Prediction?style=social) |

<div align="center">

## 🎯 Marketing

</div>

*Marketing analysis, content strategy, and promotional automation*

| Project | Description | GitHub Stars |
|---|---|---|
| [denser-org/denser-chat](https://github.com/denser-org/denser-chat) | Tool that breaks down content tasks and drafts long-form pieces | ![GitHub stars](https://img.shields.io/github/stars/denser-org/denser-chat?style=social) |



## 🎥 Media & Podcasts

*Content creation, media processing, podcasts, multimedia generation, and voice processing*

| Project | Description | GitHub Stars |
|---|---|---|
| [souzatharsis/podcastfy](https://github.com/souzatharsis/podcastfy) | Turns multi-modal content into podcast-style dialogues | ![GitHub stars](https://img.shields.io/github/stars/souzatharsis/podcastfy?style=social) |
| [wassim249/YT-Navigator](https://github.com/wassim249/YT-Navigator) | Navigate and search across YouTube channel content | ![GitHub stars](https://img.shields.io/github/stars/wassim249/YT-Navigator?style=social) |
| [artnoage/Podcast](https://github.com/artnoage/Podcast) | Automated podcast pipeline from academic texts | ![GitHub stars](https://img.shields.io/github/stars/artnoage/Podcast?style=social) |
| [benjichat/voice_agent_base](https://github.com/benjichat/voice_agent_base) | Voice agent with STT/TTS and web search in a React UI | ![GitHub stars](https://img.shields.io/github/stars/benjichat/voice_agent_base?style=social) |
| [von-development/voice-file-agent](https://github.com/von-development/voice-file-agent) | Voice-controlled file manager with LangGraph ReAct | ![GitHub stars](https://img.shields.io/github/stars/von-development/voice-file-agent?style=social) |


<div align="center">

## 🤖 Robotics & Embodied AI

</div>

*Robotics applications, embodied AI, and physical world interaction*

| Project | Description | GitHub Stars |
|---------|-------------|--------------|
| [RobotecAI/rai](https://github.com/RobotecAI/rai) | Flexible multi-agent framework for developing and deploying Embodied AI features in robotics with multi-modal interaction support | ![GitHub stars](https://img.shields.io/github/stars/RobotecAI/rai?style=social) |

<div align="center">

## 📚 RAG & Document Processing

</div>

*Retrieval-Augmented Generation, document chatbots, and knowledge base systems*

| Project | Description | GitHub Stars |
|---|---|---|
| [Goodnight77/Just-RAG](https://github.com/Goodnight77/Just-RAG) | Agentic RAG with LangGraph + Qdrant | ![GitHub stars](https://img.shields.io/github/stars/Goodnight77/Just-RAG?style=social) |
| [IlyaRice/RAG-Challenge-2](https://github.com/IlyaRice/RAG-Challenge-2) | RAG with custom PDF parsing, parent retrieval, and reranking | ![GitHub stars](https://img.shields.io/github/stars/IlyaRice/RAG-Challenge-2?style=social) |
| [TAMustafa/Local_Chat_RAG](https://github.com/TAMustafa/Local_Chat_RAG) | Local RAG chat (Ollama) with sources and modern UI | ![GitHub stars](https://img.shields.io/github/stars/TAMustafa/Local_Chat_RAG?style=social) |
| [mayooear/ai-pdf-chatbot-langchain](https://github.com/mayooear/ai-pdf-chatbot-langchain) | PDF chatbot template with LangChain/LangGraph and vector storage | ![GitHub stars](https://img.shields.io/github/stars/mayooear/ai-pdf-chatbot-langchain?style=social) |
| [bRAGAI/bRAG-langchain](https://github.com/bRAGAI/bRAG-langchain) | Tutorial series on RAG from basics to advanced | ![GitHub stars](https://img.shields.io/github/stars/bRAGAI/bRAG-langchain?style=social) |
| [catio-tech/graphqa](https://github.com/catio-tech/graphqa) | Natural language graph analysis framework for querying graphs without complex query languages | ![GitHub stars](https://img.shields.io/github/stars/catio-tech/graphqa?style=social) |
| [zamalali/DeepGit](https://github.com/zamalali/DeepGit) | Agentic workflow for intelligent GitHub repo discovery with hybrid retrieval and re-ranking | ![GitHub stars](https://img.shields.io/github/stars/zamalali/DeepGit?style=social) |


<div align="center">

## 🔬 Research Agents

</div>

*AI research assistants, academic tools, and automated research workflows*

| Project | Description | GitHub Stars |
|---|---|---|
| [bytedance/deer-flow](https://github.com/bytedance/deer-flow) | Deep research framework with search/crawl/Python tools | ![GitHub stars](https://img.shields.io/github/stars/bytedance/deer-flow?style=social) |
| [duartecaldascardoso/article-explainer](https://github.com/duartecaldascardoso/article-explainer) | Multi-agent system for understanding research articles with AI-powered explanations and Swarm architecture | ![GitHub stars](https://img.shields.io/github/stars/duartecaldascardoso/article-explainer?style=social) |
| [MODSetter/SurfSense](https://github.com/MODSetter/SurfSense) | Research agent integrating personal KBs and external sources | ![GitHub stars](https://img.shields.io/github/stars/MODSetter/SurfSense?style=social) |
| [Intelligent-Internet/ii-researcher](https://github.com/Intelligent-Internet/ii-researcher) | Deep search agent with BAML, multi-provider scraping, async flows | ![GitHub stars](https://img.shields.io/github/stars/Intelligent-Internet/ii-researcher?style=social) |
| [pogjester/company-research-agent](https://github.com/pogjester/company-research-agent) | Company research pipeline with streaming and filtering | ![GitHub stars](https://img.shields.io/github/stars/pogjester/company-research-agent?style=social) |
| [jolovicdev/shandu](https://github.com/jolovicdev/shandu) | Source evaluation and knowledge synthesis | ![GitHub stars](https://img.shields.io/github/stars/jolovicdev/shandu?style=social) |
| [LearningCircuit/local-deep-research](https://github.com/LearningCircuit/local-deep-research) | Local deep research with multiple LLMs and web searches | ![GitHub stars](https://img.shields.io/github/stars/LearningCircuit/local-deep-research?style=social) |
| [assafelovic/gpt-researcher](https://github.com/assafelovic/gpt-researcher) | Report-oriented research agent with citations | ![GitHub stars](https://img.shields.io/github/stars/assafelovic/gpt-researcher?style=social) |
| [Just-Curieous/Curie](https://github.com/Just-Curieous/Curie) | Agent for empirical experimentation in ML/systems | ![GitHub stars](https://img.shields.io/github/stars/Just-Curieous/Curie?style=social) |
| [iblameandrew/local-deepsearch-academic](https://github.com/iblameandrew/local-deepsearch-academic) | Academic paper discovery with S2 + RAPTOR indexing | ![GitHub stars](https://img.shields.io/github/stars/iblameandrew/local-deepsearch-academic?style=social) |
| [andrestorres123/breeze-agent](https://github.com/andrestorres123/breeze-agent) | Streamlined research flow inspired by STORM on LangGraph | ![GitHub stars](https://img.shields.io/github/stars/andrestorres123/breeze-agent?style=social) |
| [bernatsampera/event-deep-research](https://github.com/bernatsampera/event-deep-research) | Multi-agent biographical research system extracting structured timeline events from historical figures | ![GitHub stars](https://img.shields.io/github/stars/bernatsampera/event-deep-research?style=social) |
| [microsoft/RD-Agent](https://github.com/microsoft/RD-Agent) | R&D automation for data mining, paper analysis, model tuning | ![GitHub stars](https://img.shields.io/github/stars/microsoft/RD-Agent?style=social) |
| [SalesforceAIResearch/enterprise-deep-research](https://github.com/SalesforceAIResearch/enterprise-deep-research) | Steerable enterprise research stack with planner, specialized search agents, and web UI on LangGraph | ![GitHub stars](https://img.shields.io/github/stars/SalesforceAIResearch/enterprise-deep-research?style=social) |
| [xyin-anl/Nodeology](https://github.com/xyin-anl/Nodeology) | Simplified scientific workflow builder | ![GitHub stars](https://img.shields.io/github/stars/xyin-anl/Nodeology?style=social) |
| [alonlavian/RAGent](https://github.com/alonlavian/RAGent) | Research assistant with PDF processing and web search | ![GitHub stars](https://img.shields.io/github/stars/alonlavian/RAGent?style=social) |
| [lgesuellip/researcher_agent](https://github.com/lgesuellip/researcher_agent) | Turns websites into LLM-ready research content with automated documentation indexing | ![GitHub stars](https://img.shields.io/github/stars/lgesuellip/researcher_agent?style=social) |




<div align="center">

## 🌍 Sustainability

</div>

*Environmental impact, green technology, and sustainability analysis*

| Project | Description | GitHub Stars |
|---------|-------------|--------------|
| [vivek-suryavanshi/GreenMeGenAIApp](https://github.com/vivek-suryavanshi/GreenMeGenAIApp) | AI sustainability guide that analyzes lifestyle for carbon footprint reduction | ![GitHub stars](https://img.shields.io/github/stars/vivek-suryavanshi/GreenMeGenAIApp?style=social) |

<div align="center">

## 📋 Templates & Starters

</div>

*Ready-to-use project templates, boilerplates, and starter kits for building LangGraph applications*

| Project | Description | GitHub Stars |
|---|---|---|
| [wassim249/fastapi-langgraph-agent-production-ready-template](https://github.com/wassim249/fastapi-langgraph-agent-production-ready-template) | FastAPI template for LangGraph agents (logging, persistence, security) | ![GitHub stars](https://img.shields.io/github/stars/wassim249/fastapi-langgraph-agent-production-ready-template?style=social) |
| [gtesei/agentic_design_patterns](https://github.com/gtesei/agentic_design_patterns) | A comprehensive, hands-on collection of design patterns for building robust agentic AI systems using LangChain and LangGraph | ![GitHub stars](https://img.shields.io/github/stars/gtesei/agentic_design_patterns?style=social) |
| [NicholasGoh/fastapi-mcp-langgraph-template](https://github.com/NicholasGoh/fastapi-mcp-langgraph-template) | FastAPI template with LangGraph + MCP and streaming UX | ![GitHub stars](https://img.shields.io/github/stars/NicholasGoh/fastapi-mcp-langgraph-template?style=social) |
| [lgesuellip/langgraph-whatsapp-agent](https://github.com/lgesuellip/langgraph-whatsapp-agent) | Template for WhatsApp agents with LangGraph and MCP | ![GitHub stars](https://img.shields.io/github/stars/lgesuellip/langgraph-whatsapp-agent?style=social) |



<div align="center">

## 🏢 Workplace & Productivity

</div>

*Office automation, productivity tools, and workplace management*

| Project | Description | GitHub Stars |
|---|---|---|
| [ashumishra2104/AI_Travel_agent_Streamlit](https://github.com/ashumishra2104/AI_Travel_agent_Streamlit) | Streamlit-based AI travel agent with weather, search, currency conversion, and YouTube integration tools | ![GitHub stars](https://img.shields.io/github/stars/ashumishra2104/AI_Travel_agent_Streamlit?style=social) |
| [Clevrr-AI/Clevrr-Computer](https://github.com/Clevrr-AI/Clevrr-Computer) | Desktop task agent focused on safe execution | ![GitHub stars](https://img.shields.io/github/stars/Clevrr-AI/Clevrr-Computer?style=social) |
| [tavily-ai/meeting-prep-agent](https://github.com/tavily-ai/meeting-prep-agent) | Meeting prep with calendars, search, and profile research | ![GitHub stars](https://img.shields.io/github/stars/tavily-ai/meeting-prep-agent?style=social) |
| [zamalali/InboxHero](https://github.com/zamalali/InboxHero) | Email triage with attachment reading and reply drafting | ![GitHub stars](https://img.shields.io/github/stars/zamalali/InboxHero?style=social) |
| [khoj-ai/khoj](https://github.com/khoj-ai/khoj) | Self-hosted second brain for docs and web | ![GitHub stars](https://img.shields.io/github/stars/khoj-ai/khoj?style=social) |
| [raj-maharajwala/AI_Agent_Chatbot_Synapse](https://github.com/raj-maharajwala/AI_Agent_Chatbot_Synapse) | Bundle of search/productivity/data agents with UI | ![GitHub stars](https://img.shields.io/github/stars/raj-maharajwala/AI_Agent_Chatbot_Synapse?style=social) |


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

