# Topic map

Scope of each topic and how overlapping topics divide. A link has one primary home; see `docs/curation-rules.md`.

## Overlap rules

| Question | Rule |
|---|---|
| Foundry IQ, knowledge, grounding | `foundry-iq` is the Foundry IQ product: knowledge bases and agentic retrieval. `knowledge` covers generic knowledge sources: file search, vector stores, indexing, RAG patterns. `grounding` covers grounding an agent in web or enterprise data and returning citations. |
| Work IQ, Web IQ, Fabric IQ | Each IQ product has its own topic. Links about using an IQ with Foundry IQ knowledge bases go in the IQ product's topic, with a cross-reference in `foundry-iq`. |
| MCP vs MCP Toolbox | `mcp` is the protocol, MCP servers and clients, and authentication. `mcp-toolbox` is the Foundry tool catalog and toolbox: curated, governed tool collections. |
| Agents overview vs agent types | `agents` is Agent Service concepts and getting started. `prompt-agents` and `hosted-agents` hold material specific to that agent type. |
| MAF, durable agents, harnesses | `maf` is Microsoft Agent Framework (agents, workflows, orchestration). `durable-agents` is long-running, resumable agents. `harnesses` is the runtime loop around a model: tool execution, context management, coding-agent harnesses. |
| Sessions | `agent-sessions` is session and conversation state and lifecycle. `multiplexing-sessions` is serving many users or conversations through shared instances. `agent-bff` is the backend that sits between a front end and agents. |
| Deployment | `deploy-and-versioning` covers deploying and versioning agents and models, and release processes. `hosted-agents` covers the hosted agent runtime itself. |
| Gateway, governance, security | `ai-gateway-and-apim` is the gateway tier and Azure API Management policies. `governance` is policy, compliance, and fleet control. `security` is threats, isolation, secrets, content safety, and red teaming. `entra-id-for-agents` is identity and access. |
| Evaluation, tracing, optimization | `evaluations` measure quality and safety. `agent-tracing` is telemetry and debugging. `optimization` is improving prompts, models, cost, and latency, using the other two as inputs. |

## Topics

Entries list the scope and the search terms useful for finding sources.

### Platform & Models

- **models**: model catalog, deployments, model router, selection. Terms: "Foundry Models", "model catalog", "model router".
- **fine-tuning**: supervised fine-tuning, distillation. Terms: "Foundry fine-tuning".
- **foundry-local**: on-device and edge inference. Terms: "Foundry Local".
- **sdks**: client libraries, REST, CLI. Terms: "Foundry SDK", "azure-ai-projects", "azd ai".
- **playground**: model and agent playgrounds. Terms: "Foundry playground".
- **projects-and-resources**: resources, projects, networking, quotas, regions, pricing. Terms: "Foundry resource", "Foundry project".
- **ai-gateway-and-apim**: gateway tier, API Management policies. Terms: "AI gateway Foundry", "API Management Foundry".

### Agents

- **agents**: Agent Service concepts. Terms: "Foundry Agent Service".
- **prompt-agents**: declarative agents. Terms: "prompt agent Foundry".
- **hosted-agents**: containerized code agents. Terms: "Foundry hosted agents".
- **maf**: Microsoft Agent Framework. Terms: "Microsoft Agent Framework".
- **durable-agents**: durable, long-running agents. Terms: "durable agents Agent Framework", "Durable Task".
- **skills**: reusable agent skills. Terms: "agent skills".
- **harnesses**: agent runtimes and harnesses. Terms: "agent harness".
- **multi-agent-and-workflows**: orchestration, handoff, A2A. Terms: "multi-agent workflow Foundry", "A2A".
- **agent-sessions**: session state. Terms: "agent session", "conversations".
- **multiplexing-sessions**: many users through shared agents. Terms: "session multiplexing agents".
- **agent-environment-variables**: agent configuration and secrets. Terms: "hosted agent environment variables".
- **agent-bff**: backend-for-frontend with agents. Terms: "backend for frontend agent".
- **deploy-and-versioning**: agent and model versions, CI/CD. Terms: "agent versions Foundry", "azd ai agent".

### Tools, Knowledge & Context

- **mcp**: Model Context Protocol. Terms: "MCP Foundry".
- **mcp-toolbox**: Foundry tool catalog and toolbox. Terms: "Foundry toolbox", "tool catalog".
- **foundry-iq**: knowledge bases, agentic retrieval. Terms: "Foundry IQ".
- **knowledge**: file search, vector stores, RAG. Terms: "Foundry file search", "RAG Foundry".
- **grounding**: web and enterprise grounding. Terms: "grounding with Bing", "web search tool Foundry".
- **memory**: agent memory. Terms: "Foundry memory".
- **data-agents**: agents over data. Terms: "Fabric data agent".
- **work-iq**, **web-iq**, **fabric-iq**: each IQ product.

### Trust, Quality & Operations

- **governance**, **security**, **entra-id-for-agents**, **evaluations**, **agent-tracing**, **optimization**: see the overlap rules.

### Other

- **samples-and-templates**: sample repos and azd templates.
- **community**: blogs, talks, newsletters, projects.
- **news-and-releases**: announcements and what's new.
