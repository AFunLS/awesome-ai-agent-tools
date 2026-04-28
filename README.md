# Awesome AI Agent Tools [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of tools, frameworks, marketplaces, and resources for building, deploying, and discovering AI agents.

AI agents are autonomous or semi-autonomous systems powered by large language models (LLMs) that can use tools, execute functions, and complete complex tasks with minimal human intervention. This list helps developers, researchers, and businesses discover the best resources in the rapidly evolving AI agent ecosystem.

## Contents

- [Frameworks](#frameworks)
- [Marketplaces & Discovery](#marketplaces--discovery)
- [Skills & Plugins](#skills--plugins)
- [Development Tools](#development-tools)
- [Vector Databases & Memory](#vector-databases--memory)
- [Multi-Agent Systems](#multi-agent-systems)
- [Documentation & Learning](#documentation--learning)
- [Communities](#communities)
- [Contributing](#contributing)

## Frameworks

Foundational libraries and SDKs for building AI agents.

- [LangChain](https://github.com/langchain-ai/langchain) - Comprehensive framework for developing applications powered by language models with extensive integrations and tool support.
- [LangGraph](https://github.com/langchain-ai/langgraph) - Library for building stateful, multi-actor applications with LLMs, featuring graph-based agent orchestration.
- [AutoGPT](https://github.com/Significant-Gravitas/AutoGPT) - Experimental open-source application showcasing the capabilities of autonomous GPT-4 agents.
- [CrewAI](https://github.com/joaomdmoura/crewAI) - Framework for orchestrating role-playing, autonomous AI agents for collaborative task execution.
- [Microsoft AutoGen](https://github.com/microsoft/autogen) - Framework for building multi-agent conversational systems with support for human-in-the-loop workflows.
- [Semantic Kernel](https://github.com/microsoft/semantic-kernel) - Microsoft's SDK for integrating LLMs into C#, Python, and Java applications with enterprise features.
- [LlamaIndex](https://github.com/run-llama/llama_index) - Data framework for LLM applications, specializing in data indexing, retrieval, and knowledge graph integration.
- [BabyAGI](https://github.com/yoheinakajima/babyagi) - Minimalist framework for autonomous task-driven agents with dynamic task queue management.
- [AgentGPT](https://github.com/reworkd/AgentGPT) - Browser-based platform for assembling, configuring, and deploying autonomous AI agents.
- [Haystack](https://github.com/deepset-ai/haystack) - End-to-end NLP framework for building production-ready LLM applications and agents.
- [Google ADK (Agent Development Kit)](https://google.github.io/adk-docs/) - Google's comprehensive toolkit for building production-grade AI agents with enterprise integrations.
- [Pydantic AI](https://github.com/pydantic/pydantic-ai) - Python framework for building type-safe AI agents with Pydantic model validation.
- [Langflow](https://github.com/logspace-ai/langflow) - Low-code visual interface for building and deploying LangChain workflows and agents.

## Marketplaces & Discovery

Platforms for discovering, sharing, and deploying AI agent tools and skills.

- [tutuoai.com](https://tutuoai.com) - AI agent marketplace with 116+ curated tools, skills, and plugins for enhancing agent capabilities across multiple domains.
- [AWS AI Agent Marketplace](https://aws.amazon.com/marketplace/solutions/ai-agents-and-tools) - Enterprise marketplace for discovering and deploying AI agent solutions on AWS infrastructure.
- [Moveworks AI Agent Marketplace](https://marketplace.moveworks.com/) - 100+ pre-built, installable agent plugins for enterprise automation and support.
- [ServiceNow AI Agent Marketplace](https://store.servicenow.com/store/ai-marketplace) - Enterprise marketplace for industry-specific AI agents and workflows.
- [Kore.ai Agent Marketplace](https://www.kore.ai/ai-marketplace) - Templates, tools, and connectors for custom AI agent development.
- [AI Agent Store](https://aiagentstore.ai/) - Directory of AI agents and frameworks filterable by category, profession, and functionality.
- [AI Agents Directory](https://aiagentsdirectory.com/) - Curated directory of agent skills with install commands for quick deployment.
- [Google Cloud AI Agent Marketplace](https://cloud.google.com/blog/topics/partners/google-cloud-ai-agent-marketplace) - Partner ecosystem for discovering enterprise-grade AI agents in Gemini Enterprise.
- [GitHub MCP Registry](https://github.blog/developer-skills/agentic-ai-mcp-and-spec-driven-development-top-blog-posts-of-2025/) - Central hub for discovering Model Context Protocol (MCP) servers and tools.
- [Silicon Road](https://siliconroad.ai) - Bitcoin Lightning task marketplace for AI agents. Post tasks, complete work, earn sats. Built on Nostr + HTLCs, no custodian required.

## Skills & Plugins

Reusable capabilities and integrations that extend agent functionality.

- [MCP (Model Context Protocol)](https://www.anthropic.com/news/model-context-protocol) - Open protocol for connecting AI agents to external data sources and tools.
- [Claude Skills](https://claude.com/blog/skills-explained) - Anthropic's system for teaching expertise that any agent can apply across tasks.
- [2389 Research Skills](https://skills.2389.ai/) - Open-source Claude Code plugins and MCP servers for development workflows and testing.
- [Microsoft Skills Repository](https://github.com/microsoft/skills) - Skills, MCP servers, and custom agents for Azure SDK and Microsoft AI Foundry integration.
- [LangChain Tools](https://python.langchain.com/docs/integrations/tools/) - Extensive collection of pre-built tools and integrations for LangChain agents.
- [WordPress MCP Adapter](https://developer.wordpress.org/news/2026/02/from-abilities-to-ai-agents-introducing-the-wordpress-mcp-adapter/) - Converts WordPress Abilities into MCP tools for AI agents.
- [mcp-agent](https://github.com/lastmile-ai/mcp-agent) - Build effective agents using Model Context Protocol and workflow patterns.

## Development Tools

Tools for building, testing, and deploying AI agents.

- [LangSmith](https://smith.langchain.com/) - Platform for debugging, testing, and monitoring LLM applications and agents.
- [Langfuse](https://langfuse.com/) - Open-source observability and analytics platform for LLM applications with agent tracking.
- [n8n](https://n8n.io/) - Workflow automation platform with AI agent integration and visual programming interface.
- [Flowise](https://github.com/FlowiseAI/Flowise) - Drag-and-drop UI for building customized LLM flows and AI agents.
- [Spec Kit](https://github.blog/developer-skills/agentic-ai-mcp-and-spec-driven-development-top-blog-posts-of-2025/) - Open-source toolkit for spec-driven development with coding agents.
- [AgentOps](https://www.agentops.ai/) - Observability and monitoring platform specifically designed for AI agents.
- [PromptLayer](https://promptlayer.com/) - Platform for tracking, managing, and versioning prompts for agent development.

## Vector Databases & Memory

Storage solutions for agent memory, context, and knowledge retrieval.

- [Pinecone](https://www.pinecone.io/) - Managed vector database for similarity search and long-term memory in AI agents.
- [Weaviate](https://weaviate.io/) - Open-source vector database with built-in vectorization and hybrid search capabilities.
- [Chroma](https://www.trychroma.com/) - Lightweight, open-source embedding database designed for AI applications.
- [Qdrant](https://qdrant.tech/) - High-performance vector database with advanced filtering and payload support.
- [Milvus](https://milvus.io/) - Open-source vector database built for scalable similarity search and AI applications.

## Multi-Agent Systems

Frameworks specifically designed for coordinating multiple AI agents.

- [CrewAI](https://github.com/joaomdmoura/crewAI) - Role-based multi-agent collaboration with task delegation and hierarchical planning.
- [Microsoft AutoGen](https://github.com/microsoft/autogen) - Multi-agent conversation framework with customizable agent roles and behaviors.
- [MetaGPT](https://github.com/geekan/MetaGPT) - Multi-agent framework that simulates software development teams with specialized roles.
- [ChatDev](https://github.com/OpenBMB/ChatDev) - Collaborative agents forming a virtual software company with roles like CEO, CTO, and developers.
- [CAMEL](https://github.com/camel-ai/camel) - Communicative Agents for "Mind" Exploration of Large Language Model Society.

## Documentation & Learning

Resources for learning about AI agents and staying current.

- [LangChain Documentation](https://python.langchain.com/docs/get_started/introduction) - Comprehensive guides and tutorials for building with LangChain.
- [Anthropic Agent Documentation](https://docs.anthropic.com/en/docs/agents) - Official documentation for building agents with Claude.
- [OpenAI Agents Guide](https://platform.openai.com/docs/assistants/overview) - Guide to building assistants and agents with OpenAI APIs.
- [Awesome Agents List](https://github.com/kyrolabs/awesome-agents) - Another curated collection of AI agent frameworks and tools.
- [Azure AI Agent Training](https://learn.microsoft.com/en-us/training/modules/connect-agent-to-mcp-tools/) - Microsoft Learn courses for integrating MCP tools with Azure AI agents.
- [LlamaIndex Guides](https://www.llamaindex.ai/blog/skills-vs-mcp-tools-for-agents-when-to-use-what) - Deep dives into agent architecture decisions and best practices.

## Communities

Places to discuss, learn, and collaborate on AI agent development.

- [r/AI_Agents](https://www.reddit.com/r/AI_Agents/) - Reddit community for AI agent discussion, tools, and use cases.
- [r/LangChain](https://www.reddit.com/r/LangChain/) - Community focused on LangChain development and agent workflows.
- [r/LLMDevs](https://www.reddit.com/r/LLMDevs/) - Subreddit for LLM developers building agents and applications.
- [AI Agency Alliance Discord](https://discord.com/invite/ai-automation-community-902668725298278470) - 12,000+ member Discord community for AI automation and agent development.
- [LangChain Discord](https://discord.gg/langchain) - Official Discord server for LangChain developers and users.
- [CrewAI Discord](https://discord.gg/crewai) - Community for CrewAI framework users and contributors.
- [AutoGPT Discord](https://discord.gg/autogpt) - Discussion and support for AutoGPT development and usage.

## Contributing

Contributions are welcome! Please read our [contribution guidelines](CONTRIBUTING.md) first.

If you'd like to add a tool, framework, or resource:

1. Make sure it's relevant to AI agent development or deployment
2. Check that it's not already listed
3. Add it in the appropriate category, alphabetically
4. Include a brief description (one sentence, ~10-20 words)
5. Ensure the link works and points to the official source
6. Submit a pull request with a clear description

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the contributors have waived all copyright and related rights to this work.
