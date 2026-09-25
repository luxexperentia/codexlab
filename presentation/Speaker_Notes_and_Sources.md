# Scaling a business with teams of AI agents

18 slides · approximately 15 minutes plus discussion · evidence checked 25 September 2026

## 1. Scaling a business with teams of AI agents

EXECUTIVE BRIEFING / SEPTEMBER 2026

**CAPACITY:** Complete more work without a matching increase in staffing.

**COORDINATION:** Give specialist agents distinct responsibilities and shared goals.

**ECONOMICS:** Scale the workflows that prove their value.

**A 15-minute case for building an agent workforce.**

### Speaker notes

Open with the business constraint: demand grows faster than the organization can recruit, train and coordinate people. This presentation argues for starting a measured deployment now. It does not claim that every business needs a large agent fleet or that agents outperform people at every task. The recommendation is to establish a working capability and expand it on evidence.

## 2. Growth creates more work before it creates more capacity.

01 / THE BUSINESS CONSTRAINT

**More customers:** More questions, onboarding checks, transactions and exceptions.

**More products:** More documentation, research, software changes and support.

**More markets:** More languages, operating hours and local requirements.

**When every additional unit of work requires human attention, growth carries a staffing burden.**

### Speaker notes

Ask the audience to identify the queue that currently limits growth. It might be response times, onboarding, account research or internal engineering requests. The economic opportunity comes from changing the amount of human attention required per completed unit of work. This is an analytical framing, not an empirical claim about every company.

## 3. An agent can carry work through several steps.

02 / WHAT THE TECHNOLOGY CHANGES

**An assistant:** Responds to a request: summarize this account or draft this reply.

**An agent:** Uses permitted tools to inspect the account, choose a next step and complete a bounded task.

**A team of agents:** Divides a larger job among specialists, combines their work and escalates exceptions.

**The business value appears when completed work replaces a queue of manual steps.**

### Speaker notes

These are practical definitions for this presentation. Autonomy is bounded by permissions, tools and business rules. A team can involve a coordinator and specialist workers, or several agents coordinating through shared state. Multiple separate chatbots do not automatically constitute a coordinated team.

[A: Anthropic · multi-agent research · 13 Jun 2025](https://www.anthropic.com/engineering/multi-agent-research-system)

## 4. Divide the work where specialization and parallelism help.

03 / WHY MULTIPLE AGENTS

**Coordinator:** Defines the objective, assigns tasks and tracks completion.

**Specialists:** Research separate sources; inspect records; draft an answer.

**Reviewer + owner:** Check evidence and rules; approve consequential actions.

**Example: a proposal team can investigate the customer, solution and delivery plan concurrently.**

### Speaker notes

This proposal workflow is an illustrative design. Independent research streams can run concurrently; the final proposal still depends on their outputs. Separate roles can keep instructions focused. A reviewer agent can share the same blind spots as the writer, so agreement is not proof of correctness. Business rules, authoritative data and accountable owners remain necessary.

## 5. A research team outperformed a single research agent.

04 / DIRECT MULTI-AGENT EVIDENCE

**+90.2%** — performance on an internal research evaluation

**The comparison:** Anthropic compared an Opus 4 lead with Sonnet 4 workers against a single Opus 4 agent.

**Why it matters:** Independent research streams expand coverage before synthesis.

**The boundary:** A vendor evaluation against one agent; additional compute was used. This is not a human comparison.

**For suitable tasks, coordination can deliver a measurable quality gain.**

### Speaker notes

This result supports a specific architecture on a specific evaluation. It does not isolate coordination from the effects of greater compute or model mix. Ask whether your workflow has independent lines of inquiry whose findings can be checked and combined.

[A: Anthropic · multi-agent research · 13 Jun 2025](https://www.anthropic.com/engineering/multi-agent-research-system)

## 6. Sixteen agents built a substantial compiler prototype.

05 / DIRECT MULTI-AGENT DEMONSTRATION

**16 agents** — roughly two weeks · nearly 2,000 sessions · about $20,000 in API costs

**The output:** A 100,000-line Rust-based C compiler that could build Linux 6.9 on three architectures.

**Human contribution:** A researcher designed the harness, tests and interventions that made parallel work possible.

**The boundary:** The prototype needed external tools and had quality and efficiency limitations. API cost excludes human effort.

**A small supervising team can attempt a much larger body of implementation work.**

### Speaker notes

Anthropic published this experiment in February 2026. The build used external assembler/linker tooling, and x86 bootstrapping still required GCC support. The artifact was not a production compiler replacement. Treat it as evidence of substantial coordinated execution, not proof that a software department can be removed.

[B: Anthropic · compiler experiment · 5 Feb 2026](https://www.anthropic.com/engineering/building-c-compiler)

## 7. Klarna reports substantial customer-service labor substitution.

06 / PRODUCTION ECONOMICS

**$39 million** — reported cost savings in 2024

**Scale:** 80% of customer-service chats handled by its AI assistant during 2025.

**Labor equivalent:** Over 700 full-time agents’ workload, estimated from reductions in human-handled conversations.

**Interpretation:** Routine work moved to software. The workload equivalent is not a verified count of people dismissed.

**This is deployment evidence for AI automation; the filing does not establish a multi-agent architecture.**

### Speaker notes

Klarna’s annual filing gives different time periods for savings and chat share; keep those dates attached to each number. These are company-reported metrics, not an independent causal evaluation. Its prospectus also describes combining scalable AI service with high-quality human support. Savings do not imply that every interaction should be automated.

[C: Klarna · 2025 Form 20-F · company estimates](https://s205.q4cdn.com/644747736/files/doc_financials/2025/q4/Klarna-Group-plc-20-F-2025.pdf)

[F: Klarna · IPO prospectus · Sep 2025](https://www.sec.gov/Archives/edgar/data/2003292/000200329225000052/klarnagroupplc424b4.htm)

## 8. At peak tax season, software absorbed routine support demand.

07 / GROWTH WITHOUT PROPORTIONAL STAFFING

**70%** — of administrative chat engagements resolved autonomously

**The business:** 1-800Accountant, a virtual accounting firm serving small businesses.

**The setting:** Critical tax weeks in 2025, when administrative demand spikes.

**The consequence:** Staff can concentrate on cases that require professional attention.

**The reported result covers administrative chats; it does not mean autonomous accounting or tax advice.**

### Speaker notes

Salesforce published this customer result and included confirmation from the customer’s CTO. It is a vendor-reported production example without a controlled human comparison. The case demonstrates bounded agent automation; it does not disclose evidence that coordination among multiple agents caused the result.

[D: Salesforce · customer results · 23 Jun 2025](https://investor.salesforce.com/news/news-details/2025/Salesforce-Launches-Agentforce-3-to-Solve-the-Biggest-Blockers-to-Scaling-AI-Agents-Visibility-and-Control/)

## 9. “Better” becomes useful when the task and metric are explicit.

08 / THE HUMAN COMPARISON

**Speed · reported:** Klarna: two-minute query resolution versus 12 minutes for human agents, as of September 2024.

**Throughput · studied:** A published study of 5,172 support workers found 15% more issues resolved per hour with AI assistance.

**Quality · conditional:** Klarna reports similar satisfaction. The academic result varies across workers. Neither establishes universal superiority.

**Evaluate speed, quality and cost together on the actual work your business needs done.**

### Speaker notes

The academic result concerns people using an assistant, not autonomous agents replacing people. Klarna’s figures are observational company reports and may reflect differences in case mix. The defensible conclusion is that AI can outperform previous processes on specific measures; the organization must establish that advantage on its own workload.

[C: Klarna · 2025 Form 20-F · company estimates](https://s205.q4cdn.com/644747736/files/doc_financials/2025/q4/Klarna-Group-plc-20-F-2025.pdf)

[E: Brynjolfsson, Li & Raymond · QJE · 2025](https://doi.org/10.1093/qje/qjae044)

## 10. Lower human effort per case changes the capacity of the same team.

09 / HOW THE ADVANTAGE SCALES

**Today:** 1,000 cases × 12 minutes · = 200 human hours

**Illustrative redesign:** 600 automated cases · 400 exceptions × 15 minutes · + 20 hours of review · = 120 human hours

**Capacity released:** 80 hours per 1,000 cases · 40% less human effort · ~1.67× throughput at fixed hours

**Illustration only: assumes stable case mix and quality; excludes software and implementation costs.**

### Speaker notes

Walk through the arithmetic. Automated cases require no direct handling in this scenario; their oversight is included in the 20-hour review allowance. Exceptions take longer than the original average. At a stable 0.12 human hours per case, a 200-hour budget supports about 1,667 cases. Capacity can support growth or redeployment; it becomes cash savings only if spending actually falls. These inputs are hypothetical and are not derived from the preceding case studies.

## 11. Count the cost of a successfully completed case.

10 / THE BUSINESS CASE

**Include every cost:** Model usage, software, integration, supervision, retries and rework.

**Use a quality threshold:** Completion must meet your accuracy, service and escalation standards.

**Connect to value:** Track avoided spending or additional profitable volume; separate both from hours released.

**Unit cost = total workflow cost ÷ cases completed to the required standard.**

### Speaker notes

A cheap response that causes a second contact is not necessarily a cheap outcome. A production decision should include ongoing cost plus an explicit treatment of implementation cost, such as amortizing it over expected volume. Compare the same case types over the same period. This is a proposed evaluation framework, not a return-on-investment forecast.

## 12. Add agents only when the division of work improves results.

11 / WHEN A TEAM EARNS ITS COST

**Good candidates:** Independent research streams, distinct tools, large information sets and checkable outputs.

**Poor candidates:** Simple lookups, tightly dependent steps or tasks without a reliable success measure.

**Economic reality:** Anthropic reports about 15× chat token usage for its multi-agent systems. More capacity has a cost.

**Compare the team against a single agent and a simpler automated workflow.**

### Speaker notes

The reported token multiplier uses chat interactions as its baseline; it is not a universal price ratio or a comparison with human labor. More agents can duplicate work and introduce handoff failures. The decision criterion is the improvement in accepted outcomes per dollar on the target task.

[A: Anthropic · multi-agent research · 13 Jun 2025](https://www.anthropic.com/engineering/multi-agent-research-system)

## 13. The advantage accumulates through operating experience.

12 / WHAT STARTING EARLIER BUYS

**First deployment:** Connect the data, define permissions and discover real exceptions.

**Repeated execution:** Build evaluation examples, measure failures and refine escalation.

**Next workflow:** Reuse integrations, operating knowledge and ownership structures.

**A competitor already operating these workflows may be improving them while you are still selecting tools.**

### Speaker notes

This is a strategic inference, not a quantified finding about a specific competitor. Model access can be purchased quickly; workflow knowledge and trusted deployment practices take repeated execution. The cost of waiting depends on the value and volume of your automatable work. Do not claim that every competitor has already deployed agents.

## 14. Choose one queue and give each agent a defined responsibility.

13 / A PRACTICAL FIRST TEAM

**Intake + research:** Classify the request, retrieve approved records and identify missing information.

**Execution + checking:** Prepare or perform allowed actions; check the result against rules and evidence.

**Human owner:** Handle ambiguity, approve commitments and own customer outcomes.

**Example starting point: administrative customer requests with clear policies and reversible actions.**

### Speaker notes

This is an illustrative team design, not a requirement for five separate model instances. Start with the minimum architecture that works, then separate roles where specialization or parallel execution proves useful. Give each role a clear output, narrow permissions, a spending limit and a handoff path. Customer commitments and sensitive exceptions should follow the business’s existing authority structure.

## 15. Build enough evidence to make a real scaling decision.

14 / THE FIRST 30 DAYS

**Days 1–7 · baseline:** Choose one queue and accountable owner. Measure cost, quality, volume and response time.

**Days 8–21 · compare:** Test on representative cases; compare single-agent and team designs. Run with human review.

**Days 22–30 · decide:** Use a bounded live pilot if ready. Expand only when quality and economics meet agreed thresholds.

**Predefine the success criteria, spending cap and stop conditions before the pilot begins.**

### Speaker notes

This is a proposed schedule, not a promise that every integration can be completed in a month. Include difficult cases in the sample. Agree how errors, repeat contacts and escalation time count. Continue preparation if data access or quality is not ready. A failed pilot that identifies the constraint can still prevent a costly rollout.

## 16. Give one agent team a real business objective now.

15 / THE DECISION

**Assign:** An executive sponsor and an operational owner.

**Fund:** One bounded workflow, with a budget and a measurable baseline.

**Review:** A dated decision to expand, revise or stop based on accepted outcomes and cost.

**The path to an agent workforce starts with one team that earns the right to scale.**

### Speaker notes

Close by asking the audience to name the queue, owner and review date. The case for urgency rests on demonstrated capability and the time required to build operational experience. The evidence supports starting now on suitable work; it does not support buying an arbitrary number of agents or promising universal human replacement.

## 17. What the examples establish

APPENDIX / EVIDENCE REGISTER

**A · research system:** Internal evaluation of a coordinated team versus a single agent. Architecture and compute both differ.

**B · compiler:** Vendor research demonstration with a published artifact. Human setup and technical limits remain material.

**C + F · Klarna:** Company filings on operational savings and labor equivalence, alongside a hybrid service strategy.

**Primary sources are linked below and in the speaker notes.**

### Speaker notes

Use the source documents to check scope and measurement periods. Primary means the organization or researchers reported the result; it does not mean every metric was independently audited. Selected cases are examples, not a representative success rate for agent projects.

[A: Anthropic · multi-agent research · 13 Jun 2025](https://www.anthropic.com/engineering/multi-agent-research-system)

[B: Anthropic · compiler experiment · 5 Feb 2026](https://www.anthropic.com/engineering/building-c-compiler)

[C: Klarna · 2025 Form 20-F · company estimates](https://s205.q4cdn.com/644747736/files/doc_financials/2025/q4/Klarna-Group-plc-20-F-2025.pdf)

[F: Klarna · IPO prospectus · Sep 2025](https://www.sec.gov/Archives/edgar/data/2003292/000200329225000052/klarnagroupplc424b4.htm)

## 18. Keep the comparisons distinct

APPENDIX / EVIDENCE REGISTER

**D · 1-800Accountant:** Customer production result published by its vendor. The metric concerns administrative chats at peak demand.

**E · support-worker study:** Peer-reviewed evidence on AI-assisted people. It is not a multi-agent or autonomous-replacement experiment.

**Illustrations + inferences:** The capacity model, rollout schedule and competitive argument are analytical proposals, not reported customer outcomes.

**Evidence checked 25 September 2026. Source dates and result periods are preserved.**

### Speaker notes

The deck deliberately separates coordinated multi-agent evidence from broader evidence that agent automation changes business economics. A business can combine those capabilities, but it must measure the incremental benefit of coordination locally.

[D: Salesforce · customer results · 23 Jun 2025](https://investor.salesforce.com/news/news-details/2025/Salesforce-Launches-Agentforce-3-to-Solve-the-Biggest-Blockers-to-Scaling-AI-Agents-Visibility-and-Control/)

[E: Brynjolfsson, Li & Raymond · QJE · 2025](https://doi.org/10.1093/qje/qjae044)
