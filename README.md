<div align="center">

# 🌐 AHappyNet

**A community-driven hub for deep, production-grade AI education**

*From theory to deployment — one learning track at a time*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Programs](https://img.shields.io/badge/Programs-Active-brightgreen)]()
[![Language](https://img.shields.io/badge/Language-Python%203.11+-blue)]()

</div>

---

## What is AHappyNet?

**AHappyNet** is an open educational platform that organizes deep technical learning into structured, production-first **learning tracks**. Each track is a self-contained program spanning theory, engineering, and research — designed to take you from fundamentals to deployment-ready systems.

This hub is the **entry point and coordinator** of the ecosystem. It does not contain course content itself; instead, it maps out the landscape, connects the tracks, and helps you navigate your learning journey.

```
AHappyNet (this repo)
│
├── 🤖 Multi-Agent Systems Track        ← Active · 5 courses · 65 weeks
│   ├── mas-foundations
│   ├── mas-programming
│   ├── mas-marl
│   ├── mas-llm-agents
│   └── mas-capstone
│
├── 🧠 [Future Track: Deep Learning Engineering]
├── 📊 [Future Track: MLOps & AI Systems]
└── 🔬 [Future Track: AI Safety & Alignment]
```

> **Philosophy**: Every track is production-first. No demo-only notebooks.  
> Every concept taught is also deployed, evaluated, and documented as research.

---

## 🤖 Multi-Agent Systems Track

> *From symbolic agents to LLM orchestration — build systems that think, coordinate, and learn.*

### Overview

The **Multi-Agent Systems (MAS) Track** is a 5-course, 65-week program that teaches you to design, implement, and research intelligent systems composed of multiple interacting agents. It is one of the deepest technical tracks in the AHappyNet ecosystem.

| | |
|---|---|
| **Total Duration** | 65 weeks (5 courses × 13 weeks) |
| **Depth** | Undergraduate → Graduate → Research |
| **Language** | Python 3.11+ |
| **Format** | Theory + Labs + Projects + Research Paper |
| **Final Output** | Production system + Published-quality research paper |

---

### Who Is This For?

**Primary audience**: Software engineers and CS students who want to move beyond single-model AI applications and build *systems* where multiple agents reason, communicate, and coordinate.

**You will thrive here if you**:
- Are comfortable with Python and basic data structures
- Have seen (or are willing to learn) linear algebra and probability
- Want to understand *how* modern AI agent systems work, not just use them
- Are willing to write tests, document decisions, and deploy real code

**You do not need**:
- Prior experience with reinforcement learning or LLMs
- A GPU (all labs include CPU-compatible and mock modes)
- Industry experience

---

### Outcomes

By the end of this track, you will be able to:

**Engineer** a production multi-agent system from scratch: multi-agent orchestration, shared memory, tool use, evaluation pipelines, Docker deployment, and observability.

**Research** an open question in MAS: formulate a hypothesis, design controlled experiments, analyze emergent behaviors, and write a publication-quality paper.

**Integrate** all paradigms: symbolic BDI reasoning (Course 1–2), reinforcement learning (Course 3), and LLM orchestration (Course 4) into a single cohesive system (Course 5).

---

### The 5-Course Architecture

```
┌──────────────────────────────────────────────────────────────────────┐
│                   MULTI-AGENT SYSTEMS TRACK                          │
│                                                                      │
│  Course 1         Course 2         Course 3                         │
│  FOUNDATIONS  ──► PROGRAMMING  ──► MARL                             │
│  (Theory)         (Code)           (Learning)                       │
│                                         │                           │
│                                         ▼                           │
│                              Course 4                               │
│                              LLM-AGENTS                             │
│                              (Language)                             │
│                                    │                                │
│                                    ▼                                │
│                              Course 5                               │
│                              CAPSTONE                               │
│                              (Research)                             │
└──────────────────────────────────────────────────────────────────────┘
```

Each course is a **prerequisite** for the next. The capstone synthesizes all four.

---

### Course 1 — MAS Foundations

**Repository**: [`mas-foundations`](https://github.com/CocAgent/mas-foundations)  
**Duration**: 13 weeks · **Level**: Introductory  
**Role in track**: Establishes the theoretical vocabulary every subsequent course depends on.

| What you learn | What you build |
|---|---|
| BDI architecture, beliefs, desires, intentions | Schelling segregation model |
| Game theory: Nash Equilibrium, dominant strategies | 8-strategy Prisoner's Dilemma tournament |
| Mechanism design: auctions, incentive-compatibility | Vickrey + First-price auction simulator |
| Coordination: FIPA-ACL, Contract Net Protocol | Protocol-compliant agent system |
| Emergence: stigmergy, self-organization | Mesa-based simulation |

**Key insight delivered**: Intelligence in multi-agent systems emerges from *interactions*, not from individual agents alone.

**Connects to Course 2**: The BDI framework studied here becomes the implementation target. The protocols become SPADE behaviours.

---

### Course 2 — MAS Programming & Simulation

**Repository**: [`mas-programming`](https://github.com/CocAgent/mas-programming)  
**Duration**: 13 weeks · **Level**: Intermediate  
**Role in track**: Bridges theory to production engineering. Every K1 concept is implemented, tested, and deployed.

| What you learn | What you build |
|---|---|
| AgentSpeak / Jason: declarative BDI agents | Multi-miner coordination system |
| SPADE + FIPA-ACL: real XMPP communication | Buyer–seller negotiation with FSMBehaviour |
| Contract Net Protocol (full FIPA spec) | Distributed logistics dispatcher |
| Mesa advanced: NetworkGrid, schedulers, DataCollector | Opinion dynamics on Watts–Strogatz network |
| Epidemic simulation on real network topologies | SEIR model with 5-policy comparison |
| Stigmergy: ACO, Boids, Nagel–Schreckenberg | TSP solver + flocking + traffic phantom jams |
| Beta Reputation System, trust modeling | Deceptive agent detection (10-agent market) |
| **Professional skills**: testing MAS, profiling, security | 40+ unit tests, async SPADE, spatial indexing |

**Key insight delivered**: The same BDI loop that looks clean on paper requires careful engineering—testing, error handling, and timing matter enormously.

**Connects to Course 3**: Mesa simulations built here become RL environments. SPADE communication patterns inform MARL coordination.

---

### Course 3 — Multi-Agent Reinforcement Learning

**Repository**: [`mas-marl`](https://github.com/CocAgent/mas-marl)  
**Duration**: 13 weeks · **Level**: Advanced  
**Role in track**: Introduces the learning paradigm — agents that improve through experience rather than programmed rules.

| What you learn | What you build |
|---|---|
| MDP → Markov Games, Nash Equilibrium in games | Minimax Q-Learning on Rock-Paper-Scissors |
| Non-stationarity: why MARL is harder than RL | IQL pathology visualization (Climbing Game) |
| CTDE paradigm: centralized train, decentralized execute | Full QMIX with hypernetwork + monotone mixing |
| Value decomposition: VDN, QMIX, QTRAN, QPLEX | Benchmark across 5 algorithms, 5 seeds each |
| Policy gradient MARL: MADDPG, COMA, MAPPO | Continuous-action cooperative navigation |
| Reward shaping: PBRS invariance theorem | Potential-based shaped reward for sparse env |
| Communication: CommNet, DIAL | Learned discrete messaging on cooperative task |
| Self-play + ELO rating | TicTacToe self-play with pool of 50 past policies |
| Safe MARL: Lagrangian constraints, fairness | Constrained warehouse robot system |
| **Professional skills**: TensorBoard, gradient norms, reproducibility | 5-seed experiments, statistical significance reports |

**Key insight delivered**: Agents can discover strategies no one programmed — but only with careful experiment design, or you can't tell signal from noise.

**Connects to Course 4**: MARL environments built in Mesa (K2) and PyTorch (K3) become the benchmark environments. The debugging and evaluation skills transfer directly to LLM agent evaluation.

---

### Course 4 — LLM Multi-Agent Systems & Orchestration

**Repository**: [`mas-llm-agents`](https://github.com/CocAgent/mas-llm-agents)  
**Duration**: 13 weeks · **Level**: Advanced  
**Role in track**: Applies the same multi-agent principles to LLM-powered agents — the dominant paradigm in applied AI.

| What you learn | What you build |
|---|---|
| LLM mechanics: tokenization, function calling, sampling | Cost-tracked function calling from scratch |
| ReAct, Chain-of-Thought, Self-Consistency | ReAct agent (no framework) + Reflexion loop |
| Tree of Thoughts, Plan-and-Execute | ToT BFS solver + LLM-generated plans |
| LangGraph: StateGraph, checkpoints, HITL | Research pipeline with time-travel debugging |
| CrewAI: roles, tasks, hierarchical crews | 3-agent research + writing crew |
| AutoGen: conversational agents, GroupChat, code exec | Code-generating team with Docker sandbox |
| RAG: naïve → advanced (hybrid search, reranking) | ChromaDB + BM25 hybrid retrieval |
| LLM-as-Judge: pointwise, pairwise, bias mitigation | 20-case evaluation harness with RAGAS |
| Cost optimization: model routing, prompt caching | 3-tier ModelRouter (60–80% cost reduction) |
| Security: prompt injection, PII, guardrails, A/B test | Adversarial input defense + ABTestRunner |
| Production: FastAPI, Docker, circuit breaker, SSE | Dockerized agent API with Prometheus metrics |

**Key insight delivered**: LLM agents are powerful but expensive and fragile. Engineering discipline — evaluation, cost tracking, and security — is what separates prototypes from production.

**Connects to Course 5**: Every component built here (LangGraph, RAG, evaluation harness, FastAPI) becomes infrastructure for the capstone research system.

---

### Course 5 — Capstone Research Studio

**Repository**: [`mas-capstone`](https://github.com/CocAgent/mas-capstone)  
**Duration**: 13 weeks · **Level**: Research  
**Role in track**: Synthesis. You stop consuming knowledge and start producing it.

This course is structured as a **research studio**, not a course. Teams of 2–4 choose one of four flagship projects and build a production system that integrates knowledge from all four prior courses.

#### The Four Flagship Projects

| Project | Integration | Research Question |
|---------|------------|------------------|
| **Agent Tutor System** | BDI (K2) + RAG (K4) + LLM-Judge (K4) | Does adaptive content delivery improve learning outcomes vs fixed curriculum? |
| **Agent Research Team** | CrewAI (K4) + Reflexion (K4) + Hybrid Search | Can a 4-agent pipeline produce expert-rated literature reviews? |
| **MARL Market Simulator** | QMIX (K3) + Mesa (K2) + Game Theory (K1) | At what agent density does price discovery efficiency peak? |
| **Adaptive Learning Coordinator** | MAPPO (K3) + FastAPI (K4) + BDI (K2) | Does AI-driven resource allocation reduce at-risk students? |

#### Studio Milestones

```
Sprint 0  (Week 1–2)   Architecture Design Review — ADD + 3 ADRs
Sprint 1  (Week 3–5)   Core agents + CI/CD + abstract interfaces
Sprint 2  (Week 6–8)   Intelligence integration + mid-studio critique
Sprint 3  (Week 9–11)  Controlled experiments + ablation + paper draft
Sprint 4  (Week 12–13) Production deployment + Demo Day + final paper
```

**Final deliverables**: Working system (Docker Compose) + Research paper (4–6 pages, NeurIPS format) + Demo Day presentation.

---

### Learning Pathway

#### Recommended Path (Full Track)

```
Course 1  ──►  Course 2  ──►  Course 3  ──►  Course 4  ──►  Course 5
13 weeks       13 weeks       13 weeks       13 weeks       13 weeks
                                                            (team project)
```

Total: 65 weeks at ~5 hours/week = ~325 hours of structured learning.

#### Accelerated Entry Points

You do not have to start at Course 1. Use the table below to find your entry point.

| Your Background | Suggested Entry |
|---|---|
| CS fundamentals, no AI background | Course 1 |
| Familiar with Python + basic ML | Course 2 or 3 |
| Know RL, want multi-agent depth | Course 3, skim Course 1–2 |
| LLM engineer wanting MAS foundations | Course 4, read Course 1–2 theory |
| Researcher wanting capstone only | Course 5 (requires K1–K4 competence) |

#### Prerequisite Map

```
Python 3.x (proficient)
    └──► Course 1 (no other prerequisites)
              └──► Course 2 (K1 required)
                        └──► Course 3 (K1+K2 required, PyTorch recommended)
                                  └──► Course 4 (K1+K2+K3 recommended)
                                            └──► Course 5 (K1–K4 required)
```

---

### Cross-Course Concept Map

The same concepts appear across all five courses, deepening each time:

| Concept | K1 | K2 | K3 | K4 | K5 |
|---------|-----|-----|-----|-----|-----|
| **BDI Architecture** | Theory | Jason/Python | — | ReAct loop | StudentModel |
| **Communication** | FIPA-ACL spec | SPADE XMPP | — | Tool calling | Agent interfaces |
| **Shared Memory** | Blackboard concept | SPADE Blackboard | — | SharedAgentMemory | K4 + Redis |
| **Coordination** | Contract Net | Full CNP impl | CTDE | CrewAI crews | All 4 projects |
| **Simulation** | Mesa basic | Mesa advanced | RL environments | — | Market simulator |
| **Evaluation** | — | Unit tests | ELO + statistics | LLM-as-Judge | Full eval harness |
| **Safety** | Mechanism design | FIPA validation | Lagrangian MARL | Guardrails | Production audit |
| **Emergence** | Schelling, ACO | Boids, traffic | Hide-and-Seek style | — | Market behaviors |

---

### Repository Index

| Repository | Course | Focus | Status |
|---|---|---|---|
| [`mas-foundations`](https://github.com/CocAgent/mas-foundations) | K1 | Theory, BDI, game theory, simulation | ✅ Active |
| [`mas-programming`](https://github.com/CocAgent/mas-programming) | K2 | Jason, SPADE, Mesa, protocols | ✅ Active |
| [`mas-marl`](https://github.com/CocAgent/mas-marl) | K3 | RL, QMIX, MADDPG, self-play | ✅ Active |
| [`mas-llm-agents`](https://github.com/CocAgent/mas-llm-agents) | K4 | LangGraph, CrewAI, RAG, deployment | ✅ Active |
| [`mas-capstone`](https://github.com/CocAgent/mas-capstone) | K5 | Research studio, 4 flagship projects | ✅ Active |

Each repository contains:
- `weeks/` — 13 lecture notes with theory, code examples, and lab guides
- `src/` — production-quality library code
- `labs/` — hands-on lab exercises
- `assignments/` — graded coursework
- `tests/` — full test suite (runs without API keys via `--mock`)
- `docs/` — syllabus, assessment rubric, API setup guide
- `resources/` — glossary, annotated paper list, patterns catalog

---

### Assessments and Projects

#### Per-Course Assessment Structure

Each course (K1–K4) follows the same structure:

| Component | Weight | Description |
|---|---|---|
| Assignments (3×) | 40% | Implement core algorithms from scratch |
| Midterm (take-home) | 20% | 48-hour integration challenge |
| Final Project | 35% | End-to-end working system |
| Participation | 5% | Lab engagement, peer review |

#### Capstone Studio (K5) Assessment

| Component | Weight | Description |
|---|---|---|
| Architecture Design Document | 10% | ADD + 3 ADRs reviewed in Week 2 |
| Sprint Reviews (3×) | 15% | Code review checkpoints |
| Final System | 30% | Production deploy + 20-test eval suite |
| Research Paper | 20% | 4–6 pages, NeurIPS format |
| Demo Day | 15% | Live presentation + Q&A |
| Peer Review | 10% | Contributions to other teams' reviews |

---

### Key Lab Implementations

Across all five courses, you build these systems from scratch (no black-box wrappers):

**Course 1**: Schelling segregation · Prisoner's Dilemma tournament (8 strategies) · Vickrey auction  
**Course 2**: BDI agent in Python + Jason · SPADE FSMBehaviour CNP · SEIR epidemic network · ACO for TSP · Beta reputation system  
**Course 3**: DQN with Double + Dueling · QMIX with hypernetwork · MADDPG · MAPPO · Self-play + ELO  
**Course 4**: ReAct from scratch · LangGraph research pipeline · CrewAI + AutoGen crews · Hybrid RAG · LLM-as-Judge harness · FastAPI + Docker  
**Course 5**: One of four flagship research systems (tutor / research team / market sim / coordinator)

---

### Reference Library

**Textbooks**

| Book | Used In |
|---|---|
| Wooldridge — *Introduction to MultiAgent Systems* (2nd Ed.) | K1, K2, K5 |
| Sutton & Barto — *Reinforcement Learning: An Introduction* | K3 |
| Albrecht, Christianos & Schäfer — *Multi-Agent Deep RL* (free PDF) | K3 |
| Chip Huyen — *AI Engineering* (O'Reilly, 2024) | K4 |
| Bellifemine et al. — *Developing MAS with JADE* | K2 |

**Landmark Papers** (25 papers across the track)

| Paper | Course |
|---|---|
| Rao & Georgeff (1995) — BDI Agents: From Theory to Practice | K1–K2 |
| Mnih et al. (2015) — Human-level control via DRL | K3 |
| Rashid et al. (2018) — QMIX | K3 |
| Lowe et al. (2017) — MADDPG | K3 |
| Yu et al. (2022) — Surprising Effectiveness of PPO in MARL | K3 |
| Baker et al. (2019) — Emergent Tool Use (Hide-and-Seek) | K3 |
| Yao et al. (2022) — ReAct | K4 |
| Shinn et al. (2023) — Reflexion | K4 |
| Lewis et al. (2020) — RAG | K4 |
| Zheng et al. (2023) — LLM-as-Judge | K4 |
| Greshake et al. (2023) — Indirect Prompt Injection | K4 |

Full annotated paper lists are in `resources/papers.md` in each repository.

---

### AHappyNet Ecosystem

This track sits within AHappyNet alongside other planned programs. The hub coordinates:

```
AHappyNet
│
├── Learning Tracks (each = multiple repos with shared structure)
│   ├── 🤖 Multi-Agent Systems        ← This track (5 courses, active)
│   ├── 🧠 Deep Learning Engineering  ← Planned
│   ├── 📊 MLOps & AI Systems         ← Planned
│   └── 🔬 AI Safety & Alignment      ← Planned
│
├── Shared Infrastructure
│   ├── Assessment standards (rubrics, grading philosophy)
│   ├── Code quality standards (ruff, mypy, pytest requirements)
│   └── Deployment templates (Docker, FastAPI, CI/CD patterns)
│
└── Community
    ├── Issue tracker for cross-track questions
    ├── Discussion board for project sharing
    └── Peer review coordination (capstone tracks)
```

**Shared standards across all tracks**:
- All code has type hints, docstrings, and passing tests
- All systems run without API keys via `--mock` flag
- All courses include cost analysis and security considerations
- All capstone projects produce a deployable system + research document

---

### Getting Started

```bash
# 1. Choose your entry course (see Accelerated Entry Points above)
# 2. Clone that repository

git clone https://github.com/CocAgent/mas-foundations.git   # Course 1
# or
git clone https://github.com/CocAgent/mas-programming.git   # Course 2
# etc.

# 3. Follow the course README
cd mas-foundations
python -m venv venv && source venv/bin/activate
pip install -r requirements.txt
python labs/lab-00-setup/verify_setup.py

# 4. Start Week 1
open weeks/week-01/notes.md
```

For the capstone (Course 5), join or form a team first — see `mas-capstone/docs/studio-guide.md`.

---

### Contributing

This is an open educational project. Contributions welcome:

- **Typos and corrections**: open an issue or PR in the relevant course repo
- **New labs or examples**: follow the existing `labs/` structure
- **Paper additions**: add to `resources/papers.md` with one-sentence annotation
- **New learning tracks**: open an issue in this repo describing the track scope

Please read `CONTRIBUTING.md` before submitting.

---

<div align="center">

**AHappyNet** · Open Education · Production-First · Research-Driven

*Build things that matter, then tell the world about them.*

</div>
