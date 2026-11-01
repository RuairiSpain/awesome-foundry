# Security

Threat models, prompt injection, network isolation, secrets, red teaming and content safety.

## Guide

_Planned: `guide.md` in this folder._

## Official Documentation

- [Add guardrails to a hosted agent](https://learn.microsoft.com/azure/foundry/agents/how-to/add-hosted-agent-guardrails) - Attach a content safety guardrail to a hosted agent through its manifest.
- [Configure managed virtual network for Microsoft Foundry](https://learn.microsoft.com/azure/foundry/how-to/managed-virtual-network) - Use a managed virtual network for full isolation without managing IP ranges.
- [Guardrails overview](https://learn.microsoft.com/azure/foundry/guardrails/guardrails-overview) - Safety and security guardrails for models and agents in Foundry.
- [How to configure network isolation for Microsoft Foundry](https://learn.microsoft.com/azure/foundry/how-to/configure-private-link) - Set up private link and network isolation for a Foundry resource.
- [How to create guardrails](https://learn.microsoft.com/azure/foundry/guardrails/how-to-create-guardrails) - Create and assign guardrails with risk controls and thresholds.
- [Network isolation for a toolbox in Microsoft Foundry](https://learn.microsoft.com/azure/foundry/agents/how-to/tools/toolbox-network-isolation) - Use toolboxes in network-isolated projects.
- [Networking options for Foundry Agent Service](https://learn.microsoft.com/azure/foundry/agents/concepts/networking-options) - Compare public, BYO virtual network and managed virtual network options for agents.
- [Run AI Red Teaming Agent Locally (Azure AI Evaluation SDK)](https://learn.microsoft.com/azure/foundry/how-to/develop/run-scans-ai-red-teaming-agent) - Scan models and agents for risks with PyRIT-based attack strategies.
- [Secure autonomous agentic AI systems](https://learn.microsoft.com/security/zero-trust/sfi/secure-agentic-systems) - Zero Trust guidance for securing autonomous agents, including prompt injection defenses.

## Guides & Tutorials

<!-- Add links as: - [Title](url) - one-line description -->

## Samples & Code

- [Managed virtual network Bicep template](https://github.com/microsoft-foundry/foundry-samples/tree/main/infrastructure/infrastructure-setup-bicep/18-managed-virtual-network) - Bicep infrastructure for a Foundry setup with a managed virtual network.
- [Private network standard agent setup (Bicep)](https://github.com/microsoft-foundry/foundry-samples/tree/main/infrastructure/infrastructure-setup-bicep/17-private-network-standard-user-assigned-identity-agent-setup) - Bicep infrastructure for private-network agents with a user-assigned identity.
- [Private network standard agent setup, BYO VNet (Terraform)](https://github.com/microsoft-foundry/foundry-samples/tree/main/infrastructure/infrastructure-setup-terraform/15b-private-network-standard-agent-setup-byovnet/) - Terraform infrastructure for private-network agents in your own virtual network.

## SDKs & Tools

<!-- Add links as: - [Title](url) - one-line description -->

## Blog Posts & Articles

- [Architecting Secure and Trustworthy AI Agents with Microsoft Foundry](https://techcommunity.microsoft.com/blog/azuredevcommunityblog/architecting-secure-and-trustworthy-ai-agents-with-microsoft-foundry/4506580) - Reference guidance for building secure agents on Foundry.
- [Assess Agentic Risks with the AI Red Teaming Agent in Microsoft Foundry](https://devblogs.microsoft.com/foundry/assess-agentic-risks-with-the-ai-red-teaming-agent-in-microsoft-foundry/) - How the AI Red Teaming Agent probes agents for prompt injection and other risks.
- [Securing Azure AI Applications: Against Prompt Injection](https://techcommunity.microsoft.com/blog/azure-ai-foundry-blog/securing-azure-ai-applications-against-prompt-injection--part---2/4517179) - Layered defenses against prompt injection using Prompt Shields and content filtering.
- [Troubleshooting Microsoft Foundry Accessing On-Premises APIs Over Private Networking](https://techcommunity.microsoft.com/blog/azure-ai-foundry-blog/troubleshooting-microsoft-foundry-accessing-on%E2%80%91premises-apis-over-private-networ/4498549) - Diagnose connectivity problems when agents call private on-premises APIs.

## Videos & Talks

<!-- Add links as: - [Title](url) - one-line description -->

## Community

- [Secure Microsoft Foundry: Network, Identity and Guardrails](https://jannikreinhard.com/secure-microsoft-foundry/) - Community walkthrough of network, identity and guardrail hardening.
