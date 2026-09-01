<div align="center">

<img src="https://raw.githubusercontent.com/getagentomy/.github/main/profile/assets/agentomy-logo-dark.svg" alt="Agentomy, the AI agent governance layer" width="360">

**The governance layer for AI agents.**

### Discover. Enforce. Prove.

[![agentomy.com](https://img.shields.io/badge/agentomy.com-Visit%20Website-3b82f6?style=for-the-badge)](https://agentomy.com) [![Start free](https://img.shields.io/badge/agentomy--agent-free%20forever-brightgreen?style=for-the-badge)](https://github.com/getagentomy/agentomy-agent)

</div>

---

> **AI agent governance** is making sure an AI agent's every action is authorized before it happens, recorded so it can be proven, and stoppable by a human, at the moment it acts, not after. Agentomy is the governance layer that does this for agents on any framework, vendor, or cloud.

## Governance belongs before the action, not after it

Every AI agent acts on someone's behalf. It reads, writes, calls tools, moves data, and talks to other agents. The question that matters is never only what an agent did, because the logs can tell you that after the fact. The question is whether the action was authorized, whether the record of it can be proven to a third party, and whether a human could have stopped it. Governance is the discipline of being able to answer those three questions at the moment they are asked.

Most teams reach for governance the way they reach for a fire extinguisher: once something is already burning. They ship agents, and only when a security review, a regulator, or an incident forces the question do they go looking for what those agents have been doing. That is discovery after the fact, and it has a structural flaw. By the time an audit surfaces an ungoverned action, the action is already taken. The refund already went out. The record already left the building. Prevention is different. Prevention means governance is present at the point of action, so a gap is caught while it is still a gap and not yet an incident.

This is as true for one personal agent as for a fleet of a thousand. Scale changes the infrastructure; it does not change the principle. An agent that can act without authorization, without a record, and without an off switch is ungoverned whether there is one of them or a thousand. Agentomy exists to make prevention the default, at any scale, for anyone running agents.

## Who this is for

- **Regulated enterprises** running agents across many vendors, frameworks, and clouds, who need one governance layer that is independent of the agents it governs, because no auditor accepts the vendor grading its own homework.
- **The Claw community and other open agent runtimes.** If you build on OpenClaw, Hermes, or any open runtime, governance should not require you to change your framework. Agentomy wraps around your agents; you keep your code.
- **Individual developers and small businesses.** You do not need a security team to govern the agents you already run. The free tier gives you discovery, permission limits, and an honest posture score on your own machine.

## Start free

**[agentomy-agent](https://github.com/getagentomy/agentomy-agent)** is a governance peer you install in about thirty seconds, free forever, with no account, no API key, and nothing to deploy. It observes every action, flags risks as they appear, and scores the session against GovernanceBench, the open benchmark for what good agent governance looks like. It is the smallest possible starting point, so governance can be present from your first agent rather than retrofitted after your thousandth. When you need to prove something to someone outside your team, you connect the platform for cryptographic audit and enforcement. Until then, the free tier stands on its own.

## Proven, not asserted

- **GovernanceBench**: 6 of 6 dimensions, 235 of 235 core scenarios, 100 of 100. The full library is 448 scenarios across 20 suites.
- **VIGIL**: 148 of 148 adversarial and prompt-injection scenarios.
- **Kevlar**: 10 of 10 of the OWASP Agentic Top 10, across 48 attack scenarios.
- **45 detection methods** and **166 governance patterns** across seven domains, with **24 framework adapters**.
- **More than 19,000 automated tests** across Node, Python, and Go, plus **12 MCP governance tools**.

The benchmarks and the agent SDK below are open source and reproducible. Run them against any platform, including your own. The score is honest because the methodology is open.

## The open pieces

| Repository | What it is |
|---|---|
| [**agentomy-agent**](https://github.com/getagentomy/agentomy-agent) | The free-forever governance peer and agent SDK. Wrap any framework's agent in governance in about thirty seconds. MIT. |
| [**governancebench**](https://github.com/getagentomy/governancebench) | The open benchmark that scores agent governance across six dimensions. Point it at any platform, including your own. Apache-2.0. |
| [**vigil**](https://github.com/getagentomy/vigil) | The open adversarial and prompt-injection battery for agent platforms. Apache-2.0. |
| [**workflowbench**](https://github.com/getagentomy/workflowbench) | The governance benchmark for workflow-shaped agent runtimes. Apache-2.0. |
| [**mcp-gateway**](https://github.com/getagentomy/mcp-gateway) | Govern any stdio MCP server by interposing on tool calls. Fails closed. Apache-2.0. |

## The platform

The open pieces above are the benchmarks anyone can run, the free peer you install, and the gateway that fails closed. The full governance platform is a commercial, self-hosted product with bring-your-own-key, so customer data never leaves the customer's environment. It adds tamper-evident cryptographic audit chains, fleet-wide emergency halt, tier-based enforcement, and compliance proof mapped to frameworks including the EU AI Act, SOC 2, HIPAA, ISO 27001, and PCI DSS.

See what it does, and get it, at **[agentomy.com](https://agentomy.com)**.


## Aligned with the first agentic-AI regulation

In 2026 Singapore's IMDA published the **Model AI Governance Framework for Agentic AI**, widely described as the world's first governance framework written specifically for agents that act rather than only answer. It reframes the risk from wrong answers to wrong actions and organizes governance into four dimensions. Agentomy provides a runtime capability for nearly every technical control it names.

- **Assess and bound the risk.** A five-tier, least-privilege identity model with tier capping and pre-action authorization, so an agent operates at the minimum privilege its role requires and every action is checked against its identity before it runs.
- **Meaningful human accountability.** An escalation path that records a permitted-but-pending action as escalated rather than silently allowed, operator-validated control for sensitive actions, and an explicit authority source and expiry on every decision.
- **Technical controls across the lifecycle.** Named, runnable benchmarks (GovernanceBench, VIGIL, WorkflowBench, and OWASP-agentic coverage) run against the running system, a behavioral monitor, a tamper-evident hash-linked audit trail a third party can verify, and a sub-50ms kill switch with quarantine.
- **End-user responsibility.** An AI-disclosure marker on outbound agent messages, and operator-triggered halt so an agent can be stopped on command.

Where the framework acknowledges that agents interact with other agents but leaves multi-agent guidance open, Agentomy goes further: a cross-fleet threat-intelligence graph, so an attack seen on one agent protects the rest, and a fleet-wide halt that stops every governed agent on one command.

This is a readiness mapping, not a certification. The framework is voluntary and there is nothing to hold; what Agentomy provides is the runtime evidence that makes a readiness case demonstrable rather than asserted. The full control-by-control mapping is at **[agentomy.com/resources/singapore-agentic-ai-governance](https://agentomy.com/resources/singapore-agentic-ai-governance)**.

## Frequently asked questions

### What is AI agent governance?
Governance is the discipline of answering three questions at the moment an agent acts: was this action authorized, can the record be proven to a third party, and could a human have stopped it. It covers authorization, a tamper-evident audit trail, behavioral monitoring, and an emergency stop, applied before the action, not discovered after it in the logs.

### How do I set up governance for my AI agents?
Start with [agentomy-agent](https://github.com/getagentomy/agentomy-agent): a free-forever governance peer you install in about thirty seconds, no account or API key. It gives you agent discovery, permission limits, behavioral monitoring, and an honest posture score on your own machine. When you need cryptographic audit and enforcement you can show an auditor, you connect the self-hosted platform.

### How do I govern MCP agents and tool calls?
[mcp-gateway](https://github.com/getagentomy/mcp-gateway) interposes on any stdio MCP server and governs every tool call, failing closed on anything unauthorized, so MCP governance does not require changing your agent's code.

### How do I monitor AI agents for drift or compromise?
Agentomy runs behavioral monitoring on every action against each agent's own baseline: privilege probing, scope escalation, frequency spikes, identity drift. It flags or halts when an agent starts behaving unlike itself. That is agent observability aimed at governance, not uptime.

### Is there a kill switch to stop an AI agent?
Yes. A fleet-wide emergency halt stops every governed agent, returns a confirmed count, and survives an infrastructure restart. One agent or a thousand.

### How do I prove AI agent compliance to an auditor or for the EU AI Act?
Every governance decision is written into a tamper-evident, hash-linked audit chain you can export and independently verify. The platform maps controls to the EU AI Act, SOC 2, HIPAA, ISO 27001, and PCI DSS. These are self-assessed readiness mappings, not third-party certification, a distinction stated plainly, because a governance product cannot claim what it has not earned.

### How do I test my agent platform against the OWASP Agentic Top 10?
Point the open [governancebench](https://github.com/getagentomy/governancebench) and [vigil](https://github.com/getagentomy/vigil) at any platform, including your own. GovernanceBench scores six governance dimensions; VIGIL runs an adversarial and prompt-injection battery; the Kevlar suite covers the OWASP Agentic Top 10. The score is honest because the methodology is open.

### Does Agentomy map to Singapore's Model AI Governance Framework for Agentic AI?
Yes. Singapore's IMDA published the framework in 2026, widely described as the world's first written for agentic AI, and it organizes governance into four dimensions. Agentomy provides a runtime capability for nearly every technical control across all four: least-privilege identity and pre-action authorization for bounding risk; an escalation path and operator-validated control for human accountability; agent-specific benchmarks, a tamper-evident audit trail, and a sub-50ms kill switch for technical controls; and an AI-disclosure marker plus operator halt for end-user responsibility. Where the framework leaves multi-agent risk open, Agentomy adds a cross-fleet threat graph and fleet-wide halt. This is a readiness mapping, not certification. The full control-by-control mapping is at [agentomy.com/resources/singapore-agentic-ai-governance](https://agentomy.com/resources/singapore-agentic-ai-governance).
