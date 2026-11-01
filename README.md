# Awesome Foundry [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of Microsoft Foundry resources: docs, guides, samples, SDKs, talks and community content.

Each topic has its own folder with a `README.md` of curated links and (later) a `guide.md`. See [CONTRIBUTING.md](CONTRIBUTING.md) to add links.

## Contents

### Platform & Models

- [Foundry Models](topics/platform-and-models/models/README.md) - Model catalog, model families, deployments, model router, benchmarks and selection.
- [Fine-tuning & Distillation](topics/platform-and-models/fine-tuning/README.md) - Customizing models: supervised fine-tuning, distillation, and custom model deployment.
- [Foundry Local](topics/platform-and-models/foundry-local/README.md) - Running models on-device and at the edge.
- [SDKs](topics/platform-and-models/sdks/README.md) - Foundry SDKs and client libraries (Python, .NET, JS/TS, Java), REST APIs and CLI.
- [Playground](topics/platform-and-models/playground/README.md) - Model, agent and chat playgrounds for prototyping and testing.
- [Projects & Resources](topics/platform-and-models/projects-and-resources/README.md) - Foundry resources, projects, hubs, networking, quotas, regions and pricing.
- [AI Gateway & API Management](topics/platform-and-models/ai-gateway-and-apim/README.md) - AI gateway tier, Azure API Management policies, token limits, load balancing and model governance at the edge.

### Agents

- [Agents Overview](topics/agents/agents/README.md) - Foundry Agent Service concepts, architecture and getting started.
- [Prompt Agents](topics/agents/prompt-agents/README.md) - Declarative agents defined by instructions, model and tools.
- [Hosted Agents](topics/agents/hosted-agents/README.md) - Containerized, code-based agents hosted and scaled by Foundry.
- [Microsoft Agent Framework (MAF)](topics/agents/maf/README.md) - Microsoft Agent Framework: agents, workflows, orchestration patterns and integration with Foundry.
- [Durable Agents](topics/agents/durable-agents/README.md) - Long-running, resumable and stateful agents (Durable Task, Azure Functions).
- [Skills](topics/agents/skills/README.md) - Agent skills: packaging reusable instructions, scripts and resources.
- [Harnesses](topics/agents/harnesses/README.md) - Agent harnesses and runtimes: loops, tool execution, context management and coding-agent harnesses.
- [Multi-agent & Workflows](topics/agents/multi-agent-and-workflows/README.md) - Orchestration, handoffs, workflows and agent-to-agent (A2A) protocols.
- [Agent Sessions](topics/agents/agent-sessions/README.md) - Session lifecycle, state, threads/conversations and session storage.
- [Multiplexing Sessions](topics/agents/multiplexing-sessions/README.md) - Serving many users or conversations through shared agent instances and session routing.
- [Agent Environment Variables](topics/agents/agent-environment-variables/README.md) - Configuring agents with environment variables, secrets and per-environment settings.
- [Agent BFF](topics/agents/agent-bff/README.md) - Backend-for-frontend patterns for agents: auth, streaming, session handling and UI integration.
- [Deploy & Versioning](topics/agents/deploy-and-versioning/README.md) - Agent and model deployment, versions, CI/CD, rollout and rollback.

### Tools, Knowledge & Context

- [MCP (Model Context Protocol)](topics/tools-knowledge-context/mcp/README.md) - MCP servers and clients, remote MCP, authentication and Foundry integration.
- [MCP Toolbox](topics/tools-knowledge-context/mcp-toolbox/README.md) - Foundry tool catalog and toolbox: curated, governed tool collections for agents.
- [Foundry IQ](topics/tools-knowledge-context/foundry-iq/README.md) - Foundry IQ knowledge layer: knowledge bases, agentic retrieval and Azure AI Search.
- [Knowledge](topics/tools-knowledge-context/knowledge/README.md) - Knowledge sources, file search, vector stores, indexing and RAG patterns.
- [Grounding](topics/tools-knowledge-context/grounding/README.md) - Grounding with web, enterprise data and citations.
- [Memory](topics/tools-knowledge-context/memory/README.md) - Short- and long-term agent memory, memory stores and personalization.
- [Data Agents](topics/tools-knowledge-context/data-agents/README.md) - Data agents over Fabric, SQL and analytics sources.
- [Work IQ](topics/tools-knowledge-context/work-iq/README.md) - Work IQ: Microsoft 365 work context (people, files, meetings, mail) for agents.
- [Web IQ](topics/tools-knowledge-context/web-iq/README.md) - Web IQ: web grounding and search for agents.
- [Fabric IQ](topics/tools-knowledge-context/fabric-iq/README.md) - Fabric IQ: semantic and ontology layer over enterprise data.

### Trust, Quality & Operations

- [Governance](topics/trust-quality-operations/governance/README.md) - Policies, control plane, fleet management, compliance and responsible AI.
- [Security](topics/trust-quality-operations/security/README.md) - Threat models, prompt injection, network isolation, secrets, red teaming and content safety.
- [Entra ID for Agents](topics/trust-quality-operations/entra-id-for-agents/README.md) - Agent identities, managed identity, RBAC, on-behalf-of and Entra Agent ID.
- [Evaluations](topics/trust-quality-operations/evaluations/README.md) - Evaluators, datasets, batch and continuous evaluation, and CI integration.
- [Agent Tracing](topics/trust-quality-operations/agent-tracing/README.md) - OpenTelemetry tracing, Application Insights, monitoring and debugging agent runs.
- [Optimization](topics/trust-quality-operations/optimization/README.md) - Prompt, model, latency and cost optimization; agent optimization loops.

### Other

- [Samples & Templates](topics/other/samples-and-templates/README.md) - Reference architectures, azd templates and sample repos.
- [Community](topics/other/community/README.md) - Blogs, videos, talks, newsletters and community projects.
- [News & Releases](topics/other/news-and-releases/README.md) - Announcements, changelogs and what's new.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the contributors have waived all copyright and related rights to this work. See [LICENSE](LICENSE).
