# Jarrett West

### AI Engineering Leader | Autonomous Software Delivery | Agentic Platforms & Software Factories

I build AI-native engineering platforms that move software development beyond copilots and one-off coding agents into **governed autonomous delivery systems**.

My current focus is **Mission Control** — an AI Software Factory control plane where humans define intent, constraints, risk, and acceptance criteria while agents execute bounded work, recover from failures, produce evidence, and move changes toward review.

**North Star:**

`Intent → WorkOrder → Agent Execution → Verification → Evidence → Pull Request → Human Approval`

The goal is not simply to run more agents. It is to make autonomous engineering **reliable, inspectable, recoverable, measurable, and safe enough to operate at scale**.

---

## 🚀 Flagship: Mission Control

[**Mission Control**](https://github.com/jaydubya818/MissionControl) is a control plane for human-directed, agent-executed software development.

It is designed around a simple operating model:

- humans own intent, judgment, risk, and irreversible decisions
- agents own bounded execution, iteration, validation support, recovery, and evidence collection
- deterministic controls surround nondeterministic agents
- independent verification, not an agent saying “done,” determines readiness

Current areas of development include:

- governed WorkOrders and immutable Factory versions
- coding-agent orchestration and executor abstractions
- verification-first delivery and criterion-level evidence
- repository, code-scope, policy, risk, budget, and approval controls
- durable Attempts, leases, recovery, and idempotent execution
- GitHub App-controlled publication and human merge authority
- model and harness routing across multiple agent runtimes
- observability, auditability, and exception-first operator workflows
- governed continuous learning and bounded factory improvement
- isolated remote sandbox execution and software-factory cohort patterns

Mission Control is not intended to be another coding assistant. It is the **control plane around autonomous software delivery**.

---

## 🧠 How I Think About Autonomous Engineering

- **Humans own intent. Agents own bounded execution.**
- **Verification matters more than generation.** Fast code generation without trustworthy validation simply moves the bottleneck downstream.
- **Agents should operate inside explicit authority boundaries.** Repository scope, tools, models, budgets, risk, and acceptance criteria should be frozen before execution.
- **Non-deterministic systems need deterministic controls.** Policies, state machines, leases, budgets, verifiers, and publication gates make autonomy operationally useful.
- **Evidence should determine completion.** A system should be able to explain what changed, why, what was tested, what failed, and who authorized the next step.
- **Agent execution should be isolated, observable, budgeted, and recoverable.**
- **AI provenance belongs in execution and evidence records — not Git authorship.**
- The objective is not “more agents.” It is **higher-confidence autonomous delivery**.

---

## 🏗 Autonomous Software Delivery Architecture

```text
Human Intent & Governance
          ↓
     Mission Control
          ↓
Mission → WorkOrder → Task → Attempt
          ↓
    Software Factory
          ↓
Plan → Build → Test → Review → Verify
          ↓
   Agent / Harness Execution
          ↓
Independent Evidence & Verification
          ↓
      Pull Request
          ↓
     Human Approval
```

My focus is moving the engineer from supervising every prompt to governing **outcomes, exceptions, risk, and evidence**.

---

## 📌 Selected Projects

| Project | What it demonstrates |
|---|---|
| [**Mission Control**](https://github.com/jaydubya818/MissionControl) | Governed autonomous software delivery: WorkOrders, agent execution, policy, verification, evidence, recovery, PR publication, and human approval |
| [**AI Software Factory Mastery**](https://github.com/jaydubya818/ai-software-factory-mastery) | Software-factory architecture, autonomous delivery patterns, and agentic engineering operating models |
| [**AI-FDE Agent**](https://github.com/jaydubya818/AI-FDE-Agent) | Forward-deployed AI engineering workflows for discovering friction, automating work, and measuring engineering impact |
| [**Agentic Pi Harness**](https://github.com/jaydubya818/Agentic-Pi-Harness) | Agent harness engineering, tool execution, workflow composition, and controllable model/runtime behavior |
| [**Multi-Agent Observability**](https://github.com/jaydubya818/multi-agent-observability) | Runtime visibility, traces, operational controls, and observability patterns for multi-agent systems |
| [**Agentic-KB**](https://github.com/jaydubya818/Agentic-KB) | Persistent knowledge, context infrastructure, and knowledge-graph patterns for agent systems |

---

## 🛠 Technical Focus

**Agentic Systems**  
OpenAI / Codex · Claude · Pi · Agent SDKs · Multi-Agent Orchestration · Agent Harnesses · Model Routing · Tool / MCP Integration

**Autonomous Delivery**  
Software Factories · Verification-First Workflows · WorkOrders · Durable Execution · Agent Sandboxes · Human-in-the-Loop Governance · Evidence-Driven Acceptance

**AI Infrastructure**  
RAG · Knowledge Graphs · Context Engineering · Evals · Observability · Retrieval · Agent Memory · Runtime Telemetry

**Platform Engineering**  
TypeScript · Python · JavaScript · React · Node.js · Convex · GitHub Apps · Docker · CI/CD · APIs

---

## 🔭 What I'm Exploring

I am particularly interested in the systems required for the next phase of AI-native engineering:

- software factories that operate continuously with bounded autonomy
- isolated execution environments for coding agents
- Best-of-N / multi-candidate engineering workflows
- verification and evidence as first-class delivery primitives
- model + harness + tool routing based on quality, cost, and speed
- forward-deployed AI engineering
- durable agent workflows that survive process and session failure
- learning systems that improve engineering workflows without surrendering human authority

---

## 🤝 Connect

I enjoy connecting with engineers and leaders working on AI developer platforms, agent infrastructure, autonomous software delivery, forward-deployed engineering, and the future of software development.

- GitHub: [@jaydubya818](https://github.com/jaydubya818)
- LinkedIn: [Jarrett West](https://linkedin.com/in/JayWest01)
