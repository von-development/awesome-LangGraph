# 🦜🕸️ Awesome LangGraph ![Awesome](https://awesome.re/badge.svg)

> A curated list of awesome projects, resources, and tools for building stateful, multi-actor applications with [LangGraph](https://github.com/langchain-ai/langgraph).

**Welcome to Awesome LangGraph!** This repository is your go-to resource for discovering tools, templates, and examples for building powerful AI applications with LangGraph. Whether you're just getting started or building production-ready systems, you'll find valuable resources to accelerate your development.


## Table of Contents

- [Core Ecosystem](#core-ecosystem)
  - [LangChain Ecosystem Overview](#langchain-ecosystem-overview)
  - [LangGraph Platform](#langgraph-platform)
- [Official Resources](#official-resources)
  - [Starter Templates](#starter-templates)
  - [Pre-built Agents](#pre-built-agents)
  - [Example Applications](#example-applications)
  - [Tools & Integrations](#tools--integrations)
    - [Official Tools](#official-tools)
    - [Third-Party Packages](#third-party-packages)
- [Community Projects](#community-projects)
  - [Pre-built Agents](#community-pre-built-agents)
  - [AI Assistants](#ai-assistants)
  - [Development & Tools](#development--tools)
  - [Content & Media](#content--media)
  - [Knowledge & Retrieval](#knowledge--retrieval)
  - [Finance & Business](#finance--business)
  - [Sustainability](#sustainability)
- [Learning Resources](#learning-resources)
  - [Courses](#courses)
  - [Tutorials & Examples](#tutorials--examples)
- [Companies Using LangGraph](#companies-using-langgraph)
- [Contributing](#contributing)
- [Acknowledgments](#acknowledgments)

### LangChain Ecosystem

#### Overview

LangGraph extends the LangChain ecosystem to provide flexible orchestration for LLM-powered systems. The ecosystem consists of several key components working together to support the entire LLM application lifecycle:
<div align="center">
  <img src="static/langchain_overview.svg" alt="LangChain Ecosystem">
  <p><sub>Source: <a href="https://python.langchain.com/docs/introduction/">LangChain Documentation</a></sub></p>
</div>

#### Core Components

<details>
<summary><strong>LangChain</strong></summary>

- Foundation framework for LLM application development
- Provides standardized interfaces for LLMs and related technologies
- Includes extensive integrations with embedding models and vector stores
- Features reusable components for chains, agents, and memory systems

📚 Documentation: [Python](https://python.langchain.com/docs/introduction/) | [TypeScript](https://js.langchain.com/docs/introduction/)
</details>

<details>
<summary><strong>LangGraph </strong></summary>

- Built on top of LangChain for advanced workflow orchestration
- Enables building stateful, multi-agent systems
- Provides first-class streaming support
- Includes built-in human-in-the-loop capabilities
- Supports complex agent interactions and coordination

📚 Documentation: [LangGraph Docs](https://python.langchain.com/docs/langgraph) | [TypeScript Docs](https://js.langchain.com/docs/introduction/)
</details>

<details>
<summary><strong>LangSmith </strong></summary>

- Comprehensive observability and debugging platform
- Debugging and testing tools
- Playground for experimentation
- Prompt management and versioning
- Annotation and evaluation
- Performance monitoring
- Testing automation

📚 Documentation: [LangSmith Platform](https://smith.langchain.com/) | [LangSmith Docs](https://docs.smith.langchain.com/)
</details>

<details>
<summary><strong>LangGraph Platform </strong></summary>

- Production deployment and management solution
- API generation for LangGraph applications
- Deployment automation
- Scaling infrastructure
- Production monitoring

📚 Documentation: [Platform Overview](https://langchain-ai.github.io/langgraph/concepts/langgraph_platform/#overview)

More details about the platform components and features in the section below.
</details>

### LangGraph Platform

The LangGraph Platform provides tools and services for building, deploying, and managing production-grade applications:

![LangGraph Platform Architecture](static/langgraph_platform.png)


<details>
<summary><strong>LangGraph Server</strong></summary>

- Opinionated API architecture for deploying agentic applications
- Built-in support for streaming, background runs, and task queues
- Horizontally scalable infrastructure
- Integrated monitoring with LangSmith

📚 Documentation: [Server Docs](https://langchain-ai.github.io/langgraph/concepts/langgraph_server/)
</details>

<details>
<summary><strong>LangGraph Studio</strong></summary>

- Visual IDE for development and debugging
- Real-time graph visualization
- Interactive testing environment
- Integrated debugging tools

📚 Documentation: [Studio Docs](https://langchain-ai.github.io/langgraph/concepts/langgraph_studio/)
</details>

<details>
<summary><strong>LangGraph CLI</strong></summary>

- Command-line interface for local development
- Project scaffolding and management
- Deployment automation
- Configuration management

📚 Documentation: [CLI Docs](https://langchain-ai.github.io/langgraph/concepts/langgraph_cli/)
</details>

<details>
<summary><strong>LangGraph SDK</strong></summary>

- Core development toolkit
- Graph construction and management
- State management utilities
- Integration helpers

📚 Documentation: [SDK Docs](https://langchain-ai.github.io/langgraph/concepts/sdk/)
</details>

<details>
<summary><strong>Remote Graph</strong></summary>

- Remote execution of deployed applications
- Seamless integration with deployed servers
- State synchronization
- Distributed execution support

📚 Documentation: [Remote Graph Guide](https://langchain-ai.github.io/langgraph/how-tos/use-remote-graph/)
</details>

---

## Official Resources

### Starter Templates

Templates to help you get started with LangGraph. For deployment instructions, check out the [LangGraph CLI Documentation](https://langchain-ai.github.io/langgraph/cloud/reference/cli/).

| Template | Description | <img src="https://img.shields.io/static/v1?label=&message=Python&color=3776AB&logo=python&logoColor=white&style=flat-square"/> | <img src="https://img.shields.io/static/v1?label=&message=TypeScript&color=3178C6&logo=typescript&logoColor=white&style=flat-square"/> |
|----------|-------------|---------|------------|
| **New Project** | Basic chatbot with memory | [langchain-ai/new-langgraph-project](https://github.com/langchain-ai/new-langgraph-project)  | [langchain-ai/new-langgraphjs-project](https://github.com/langchain-ai/new-langgraphjs-project)  |
| **ReAct Agent** | Tool-using agent framework | [langchain-ai/react-agent](https://github.com/langchain-ai/react-agent) | [langchain-ai/react-agent-js](https://github.com/langchain-ai/react-agent-js)  |
| **Memory Agent** | Cross-thread memory persistence | [langchain-ai/memory-agent](https://github.com/langchain-ai/memory-agent) | [langchain-ai/memory-agent-js](https://github.com/langchain-ai/memory-agent-js)  |
| **Retrieval Agent** | Knowledge-based QA system | [langchain-ai/retrieval-agent-template](https://github.com/langchain-ai/retrieval-agent-template)  | [langchain-ai/retrieval-agent-template-js](https://github.com/langchain-ai/retrieval-agent-template-js) |
| **Data Enrichment** | Web search & data organization | [langchain-ai/data-enrichment](https://github.com/langchain-ai/data-enrichment) | [langchain-ai/data-enrichment-js](https://github.com/langchain-ai/data-enrichment-js)  |



---
### Pre-built Agents

LangGraph comes with a built-in React agent pattern, and the community has developed numerous additional agent libraries. Below are some of the most popular community-built options that extend LangGraph's functionality in various ways.


These are the official agents provided and maintained by LangGraph:

| Agent | Description | <img src="https://img.shields.io/static/v1?label=&message=Python&color=3776AB&logo=python&logoColor=white&style=flat-square"/> | <img src="https://img.shields.io/static/v1?label=&message=TypeScript&color=3178C6&logo=typescript&logoColor=white&style=flat-square"/> |
|-------|-------------|---------|------------|
| **Computer Use Agent** | Agent for automating computer interactions and tasks | [langgraph-cua-py](https://github.com/langchain-ai/langgraph-cua-py) | [langgraph-cua](https://github.com/langchain-ai/langgraphjs/tree/main/libs/langgraph-cua) |
| **Swarm Agent** | Build swarm-style multi-agent systems | [langgraph-swarm-py](https://github.com/langchain-ai/langgraph-swarm-py) | [langgraph-swarm](https://github.com/langchain-ai/langgraphjs/tree/main/libs/langgraph-swarm) |
| **Supervisor** | Build supervisor multi-agent systems | [langgraph-supervisor-py](https://github.com/langchain-ai/langgraph-supervisor-py) | [langgraph-supervisor](https://github.com/langchain-ai/langgraphjs/tree/main/libs/langgraph-supervisor) |
| **MCP Adapters** | Make Anthropic MCP tools compatible with agents | [langchain-mcp-adapters](https://github.com/langchain-ai/langchain-mcp-adapters) | ❌ |
| **LangMem** | Agents that learn and adapt from interactions | [langmem](https://github.com/langchain-ai/langmem) | ❌ |
| **CodeAct** | Advanced function-calling with code generation | [langgraph-codeact](https://github.com/langchain-ai/langgraph-codeact) | ❌ |
| **Reflection** | Agent architecture with self-review capabilities | [langgraph-reflection](https://github.com/langchain-ai/langgraph-reflection) | ❌ |
| **BigTool** | Build agents with large numbers of tools | [langgraph-bigtool](https://github.com/langchain-ai/langgraph-bigtool) | ❌ |



---
### Example Applications

These applications demonstrate real-world implementations using LangGraph. From chatbots to content generation, each example showcases different patterns and best practices for building production-ready systems and can be deployed with LanGraph Cloud.

You can use these as reference architectures or starting points for your own projects.

| Name | Description |
|------|-------------|
| [ChatLangChain](https://github.com/langchain-ai/chat-langchain)![GitHub stars](https://img.shields.io/github/stars/langchain-ai/chat-langchain?style=social) | Documentation assistant powered by RAG-based semantic search with intelligent query analysis. Features automated content indexing, duplicate prevention, GenUI, and sophisticated document tracking system. |
| [OpenGPTs](https://github.com/langchain-ai/opengpts)<br>![GitHub stars](https://img.shields.io/github/stars/langchain-ai/opengpts?style=social) | Open-source GPT alternative supporting 60+ LLM providers and tools. Implements three cognitive architectures (Assistant, RAG, Chatbot) with PostgreSQL backend and flexible deployment options. |
| [Executive AI Assistant](https://github.com/langchain-ai/executive-ai-assistant)<br>![GitHub stars](https://img.shields.io/github/stars/langchain-ai/executive-ai-assistant?style=social) | Smart email management system with calendar integration. Provides intelligent triage, automated response drafting, and meeting coordination through Gmail API with customizable workflows. |
| [Agent Inbox](https://github.com/langchain-ai/agent-inbox)<br>![GitHub stars](https://img.shields.io/github/stars/langchain-ai/agent-inbox?style=social) | Centralized interface for AI agent interactions featuring real-time communication, interrupt handling, and configurable response systems for both local and cloud deployments. |
| [Python Fullstack](https://github.com/langchain-ai/langgraph-fullstack-python)<br>![GitHub stars](https://img.shields.io/github/stars/langchain-ai/langgraph-fullstack-python?style=social) | All-in-one chatbot template combining React-style agents with modern UI. Built with FastHTML components and Claude 3, featuring single-deployment architecture and extensible tools. |
| [LangGraph UI Examples](https://github.com/langchain-ai/langgraphjs-gen-ui-examples)<br>![GitHub stars](https://img.shields.io/github/stars/langchain-ai/langgraphjs-gen-ui-examples?style=social) | Showcase of generative UI agents including stockbroker, trip planner, and email tools. Demonstrates human-in-the-loop workflows with customizable components and tool integrations. |
| [LangChain Next.js](https://github.com/langchain-ai/langchain-nextjs-template)<br>![GitHub stars](https://img.shields.io/github/stars/langchain-ai/langchain-nextjs-template?style=social) | Next.js starter template showcasing LangChain.js modules. Includes streaming chat, structured output, multi-step agents, and RAG implementations with Vercel AI SDK integration. |
| [Custom Auth](https://github.com/langchain-ai/custom-auth)<br>![GitHub stars](https://img.shields.io/github/stars/langchain-ai/custom-auth?style=social) | Supabase-powered authentication template for LangGraph deployments. Implements OAuth2 with Google, user management, and secure chatbot access with conversation thread isolation. |



---

### Development Tools
LangGraph provides official development tools to streamline your workflow, from visual design to code generation. These tools help you build and deploy LangGraph applications more efficiently.

- **[LangGraph Builder](https://github.com/langchain-ai/langgraph-builder)** – Visual canvas for designing cognitive architectures of LangGraph applications with code generation for Python and TypeScript 
- **[LangGraph Generator](https://github.com/langchain-ai/langgraph-gen-py)** – CLI tool for generating LangGraph application stubs from YAML specifications 

#### Third-Party Packages
Ready-to-use integrations for extending LangGraph with external services and tools. Access everything from LLMs, vector stores to databases to development tools.

🔗 [Python Packages](https://python.langchain.com/docs/integrations/providers/all/)  | 🔗 [JavaScript Packages](https://js.langchain.com/docs/integrations/platforms/) 
## Community Projects

This is a curated list of open-source agent and LLM projects. They are grouped by category for easier discovery.


### Community Pre-built Agents
- **[TrustCall](https://github.com/hinthornw/trustcall)** - Tenacious tool calling built on LangGraph ![GitHub stars](https://img.shields.io/github/stars/hinthornw/trustcall)
- **[Data Science Team](https://github.com/business-science/ai-data-science-team)** - AI-powered data science team for common tasks ![GitHub stars](https://img.shields.io/github/stars/business-science/ai-data-science-team)
- **[Delve](https://github.com/andrestorres123/delve)** - A taxonomy generator for unstructured data ![GitHub stars](https://img.shields.io/github/stars/andrestorres123/delve)
- **[Nodeology](https://github.com/xyin-anl/Nodeology)** - Enable researcher to build scientific workflows easily with simplified interface ![GitHub stars](https://img.shields.io/github/stars/xyin-anl/Nodeology)
- **[Breeze Agent](https://github.com/andrestorres123/breeze-agent)** - A streamlined research system built inspired on STORM and built on LangGraph ![GitHub stars](https://img.shields.io/github/stars/andrestorres123/breeze-agent)

Want to contribute your own pre-built agent? Check out the [contribution guidelines](https://langchain-ai.github.io/langgraph/prebuilt/#-contributing-your-library) in the documentation.

### AI Assistants
- **[AI-Data-Analysis-MultiAgent](https://github.com/starpig1129/AI-Data-Analysis-MultiAgent)** – Multi-agent system for data analysis, visualization, and report generation. ![GitHub stars](https://img.shields.io/github/stars/starpig1129/AI-Data-Analysis-MultiAgent)
- **[AI Coding Assistant](https://github.com/AbhinavTheDev/coding-agent)** – Development tool that uses LangGraph agents to aid coding workflow with natural language. ![GitHub stars](https://img.shields.io/github/stars/AbhinavTheDev/coding-agent)
- **[Brainstormers](https://github.com/Azzedde/brainstormers)** – Tool with curated, optimized chains for brainstorming using real-world techniques. ![GitHub stars](https://img.shields.io/github/stars/Azzedde/brainstormers)
- **[Clevrr Computer](https://github.com/Clevrr-AI/Clevrr-Computer)** – Automation agent for basic computer tasks with a focus on safety and accuracy. ![GitHub stars](https://img.shields.io/github/stars/Clevrr-AI/Clevrr-Computer)
- **[ContentMind AI](https://github.com/lgesuellip/researcher_agent)** – Turns websites into LLM-ready research content with automated documentation indexing. ![GitHub stars](https://img.shields.io/github/stars/lgesuellip/researcher_agent)
- **[CopilotKit](https://github.com/CopilotKit/CopilotKit)** – Framework for building AI copilots with generative UI, chat interfaces, and human-in-the-loop capabilities ![GitHub stars](https://img.shields.io/github/stars/CopilotKit/CopilotKit?style=social)
- **[RD-Agent](https://github.com/microsoft/RD-Agent)** – Microsoft's R&D automation tool for data mining, paper analysis, and model tuning. ![GitHub stars](https://img.shields.io/github/stars/microsoft/RD-Agent)
- **[WebRover](https://github.com/hrithikkoduri/WebRover)** – Autonomous AI agent for automating web tasks and research. ![GitHub stars](https://img.shields.io/github/stars/hrithikkoduri/WebRover)
- **[AI Conversation Simulator](https://github.com/sanjeed5/ai-conversation-simulator)** – Test and develop AI assistants through simulated conversations with configurable personas and LangSmith integration ![GitHub stars](https://img.shields.io/github/stars/sanjeed5/ai-conversation-simulator?style=social)
- **[SurfSense](https://github.com/MODSetter/SurfSense)** – Customizable AI research agent that integrates personal knowledge bases with external sources like Tavily, Slack, and Notion ![GitHub stars](https://img.shields.io/github/stars/MODSetter/SurfSense?style=social)
- **[RAI](https://github.com/RobotecAI/rai)** – Flexible multi-agent framework for developing and deploying Embodied AI features in robotics with multi-modal interaction support ![GitHub stars](https://img.shields.io/github/stars/RobotecAI/rai?style=social)



### Development & Tools
- **[AI Agent Service Toolkit](https://github.com/JoshuaC215/agent-service-toolkit)** – Framework for deploying AI agents with FastAPI and Streamlit. ![GitHub stars](https://img.shields.io/github/stars/JoshuaC215/agent-service-toolkit)
- **[Browser Use: Web AI](https://github.com/browser-use/browser-use)** – Library for AI agents to interact with websites and automate web tasks. ![GitHub stars](https://img.shields.io/github/stars/browser-use/browser-use)
- **[Khoj](https://github.com/khoj-ai/khoj)** – Self-hostable AI second brain for web or docs with custom agents. ![GitHub stars](https://img.shields.io/github/stars/khoj-ai/khoj)
- **[Hyperbolic-AgentKit](https://github.com/HyperbolicLabs/Hyperbolic-AgentKit)** – AI agent framework with blockchain and compute features. ![GitHub stars](https://img.shields.io/github/stars/HyperbolicLabs/Hyperbolic-AgentKit)
- **[Agent Protocol](https://github.com/langchain-ai/agent-protocol)** – Codified, framework-agnostic APIs for serving LLM agents in production. ![GitHub stars](https://img.shields.io/github/stars/langchain-ai/agent-protocol)
- **[SRAgent](https://github.com/ArcInstitute/SRAgent)** – Multi-agent framework for automating genomic research and RNA sequencing workflows from scientific databases. ![GitHub stars](https://img.shields.io/github/stars/ArcInstitute/SRAgent)
- **[Google GenAI Toolbox](https://github.com/googleapis/genai-toolbox)** – Production-grade infrastructure for connecting AI agents with databases, featuring security, observability, and connection pooling ![GitHub stars](https://img.shields.io/github/stars/googleapis/genai-toolbox?style=social)



### Content & Media
- **[AgentWrite](https://github.com/denser-org/denser-chat)** – Automated content generation tool that breaks down writing tasks. ![GitHub stars](https://img.shields.io/github/stars/denser-org/denser-chat)
- **[Podcastfy.ai](https://github.com/souzatharsis/podcastfy)** – Transforms multi-modal content into audio conversations in multiple languages. ![GitHub stars](https://img.shields.io/github/stars/souzatharsis/podcastfy)
- **[Robo-blogger](https://github.com/langchain-ai/robo-blogger)** – Voice-to-content pipeline for converting spoken ideas into structured blog posts. ![GitHub stars](https://img.shields.io/github/stars/langchain-ai/robo-blogger)
- **[Social Media Agent](https://github.com/langchain-ai/social-media-agent)** – Generates Twitter & LinkedIn posts from URLs with optional human review. ![GitHub stars](https://img.shields.io/github/stars/langchain-ai/social-media-agent)
- **[YT Navigator](https://github.com/wassim249/YT-Navigator)** – AI-powered tool for efficient navigation and search through YouTube channel content ![GitHub stars](https://img.shields.io/github/stars/wassim249/YT-Navigator?style=social)



### Knowledge & Retrieval
- **[bRAG](https://github.com/bRAGAI/bRAG-langchain)** – Tutorial series on RAG (Retrieval Augmented Generation) from basics to advanced. ![GitHub stars](https://img.shields.io/github/stars/bRAGAI/bRAG-langchain)
- **[Demo Bank Support Bot](https://github.com/multinear-demo/demo-bank-support-lc-py)** – RAG-powered banking support chatbot designed to prevent hallucinations. ![GitHub stars](https://img.shields.io/github/stars/multinear-demo/demo-bank-support-lc-py)
- **[Denser Chat](https://github.com/denser-org/denser-chat)** – Chatbot that answers questions from PDFs and webpages with text extraction. ![GitHub stars](https://img.shields.io/github/stars/denser-org/denser-chat)
- **[IdentityRAG Insights](https://github.com/tilotech/identity-rag-customer-insights-chatbot)** – Chatbot that merges customer data into golden records for context-aware replies. ![GitHub stars](https://img.shields.io/github/stars/tilotech/identity-rag-customer-insights-chatbot)
- **[King RAGent](https://github.com/alonlavian/RAGent)** – AI research assistant with PDF processing, vector storage, and web search integration. ![GitHub stars](https://img.shields.io/github/stars/alonlavian/RAGent)
- **[Reply gAI](https://github.com/langchain-ai/reply_gAI)** – AI clone for X/Twitter profiles with long-term memory and RAG. ![GitHub stars](https://img.shields.io/github/stars/langchain-ai/reply_gAI)
- **[Shandu](https://github.com/jolovicdev/shandu)** – LLM-based research system that automates source evaluation and knowledge synthesis. ![GitHub stars](https://img.shields.io/github/stars/jolovicdev/shandu)
- **[Local Deep Research](https://github.com/LearningCircuit/local-deep-research)** – Privacy-focused research assistant performing deep analysis using multiple LLMs and web searches with local execution capability ![GitHub stars](https://img.shields.io/github/stars/LearningCircuit/local-deep-research?style=social)
- **[GPT Researcher](https://github.com/assafelovic/gpt-researcher)** – Open deep research agent producing detailed reports with citations, using Plan-and-Solve and RAG techniques ![GitHub stars](https://img.shields.io/github/stars/assafelovic/gpt-researcher?style=social)


### Sustainability
- **[GreenMe](https://github.com/vivek-suryavanshi/GreenMeGenAIApp)** – AI sustainability guide that analyzes lifestyle for carbon footprint reduction. ![GitHub stars](https://img.shields.io/github/stars/vivek-suryavanshi/GreenMeGenAIApp)

---

## Learning Resources

### Courses
- **[Introduction to LangGraph](https://academy.langchain.com/courses/intro-to-langgraph)** - Official course covering fundamentals and practical use cases.
- **[LangGraph - Develop LLM powered AI agents](https://www.udemy.com/course/langgraph/)** - Course on building AI agents with LangGraph by [@emarco177](https://github.com/@emarco177)


### Tutorials & Examples
- **[GenAI_Agents](https://github.com/NirDiamant/GenAI_Agents)** - Agent implementation examples ![GitHub stars](https://img.shields.io/github/stars/NirDiamant/GenAI_Agents?style=social)
- **[RAG_Techniques](https://github.com/NirDiamant/RAG_Techniques)** - Several RAG implementations and tutorials ![GitHub stars](https://img.shields.io/github/stars/NirDiamant/RAG_Techniques?style=social)
- **[Grounding RAG Applications Workshop](https://github.com/carlyrichmond/webdevcon-grounding-rag-applications-workshop)** - Hands-on workshop building RAG chatbots and travel planning agents with JavaScript and Elasticsearch ![GitHub stars](https://img.shields.io/github/stars/carlyrichmond/webdevcon-grounding-rag-applications-workshop?style=social)

---

## Companies Using LangGraph

A comprehensive list of organizations using LangGraph in production environments. For more details and case studies, visit the [official adopters page](https://langchain-ai.github.io/langgraph/adopters/).


| Company | Industry | Use Case | Reference |
|---------|----------|----------|-----------|
| [LinkedIn](https://www.linkedin.com/) | Social Media | Code generation; Search & discovery | [Blog post, 2025](https://www.linkedin.com/blog/engineering/ai/practical-text-to-sql-for-data-analytics) |
| [Uber](https://www.uber.com/) | Transportation | Developer productivity; Code generation | [Presentation, 2024](https://dpe.org/sessions/ty-smith-adam-huda/this-year-in-ubers-ai-driven-developer-productivity-revolution/) |
| [GitLab](https://about.gitlab.com/) | Software & Technology | Code generation | [Duo workflow docs](https://handbook.gitlab.com/handbook/engineering/architecture/design-documents/duo_workflow/) |
| [Klarna](https://www.klarna.com/) | Fintech | Copilot for domain-specific task | [Case study, 2025](https://blog.langchain.dev/customers-klarna/) |
| [Rakuten](https://www.rakuten.com/) | E-commerce / Fintech | Copilot for domain-specific task | [Blog post, 2025](https://rakuten.today/blog/from-ai-hype-to-real-world-tools-rakuten-teams-up-with-langchain.html) |
| [Minimal](https://gominimal.ai/) | E-commerce | Customer support | [Case study, 2025](https://blog.langchain.dev/how-minimal-built-a-multi-agent-customer-support-system-with-langgraph-langsmith/) |
| [Komodo Health](https://www.komodohealth.com/) | Healthcare | Copilot for domain-specific task | [Blog post](https://www.komodohealth.com/perspectives/new-gen-ai-assistant-empowers-the-enterprise/) |
| [OpenRecovery](https://www.openrecovery.com/) | Healthcare | Copilot for domain-specific task | [Case study, 2024](https://blog.langchain.dev/customers-openrecovery/) |
| [AppFolio](https://www.appfolio.com/) | Real Estate | Copilot for domain-specific task | [Case study, 2024](https://blog.langchain.dev/customers-appfolio/) |
| [Cisco Outshift](https://outshift.cisco.com/) | Software & Technology | DevOps | [Blog post, 2025](https://outshift.cisco.com/blog/build-react-agent-application-for-devops-tasks-using-rest-apis) |
| [Elastic](https://www.elastic.co/) | Software & Technology | Copilot for domain-specific task | [Blog post, 2025](https://www.elastic.co/blog/elastic-security-generative-ai-features) |
| [Infor](https://infor.com/) | Software & Technology | GenAI embedded product experiences; customer support; copilot | [Case study, 2025](https://blog.langchain.dev/customers-infor/) |
| [AirTop](https://www.airtop.ai/) | Software & Technology (GenAI Native) | Browser automation for AI agents | [Case study, 2024](https://blog.langchain.dev/customers-airtop/) |
| [Athena Intelligence](https://www.athenaintel.com/) | Software & Technology (GenAI Native) | Research & summarization | [Case study, 2024](https://blog.langchain.dev/customers-athena-intelligence/) |
| [Captide](https://www.captide.co/) | Software & Technology (GenAI Native) | Data extraction | [Case study, 2025](https://blog.langchain.dev/how-captide-is-redefining-equity-research-with-agentic-workflows-built-on-langgraph-and-langsmith/) |

---

## Contributing

**We welcome contributions to this awesome list! Please ensure your submission**:


- Includes a clear description of its purpose and value
- Follows the existing format and style
- Is placed in the appropriate category

To contribute:
1. Fork the repository
2. Add your project following the established format
3. Create a pull request with a brief explanation

For questions or suggestions, please open an issue.

---

## Acknowledgments

Special thanks to the [@langchain-ai](https://github.com/langchain-ai) team for building such an amazing framework and ecosystem that enables developers to create powerful AI applications. 
> This list is inspired by [awesome-langchain](https://github.com/kyrolabs/awesome-langchain), which has been a great resource for the community.

---
