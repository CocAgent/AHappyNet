<div align="center">

# 🌐 AHappyNet

**A community-driven hub for deep, production-grade AI education**

*From theory to deployment — one learning track at a time*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Tracks](https://img.shields.io/badge/Active%20Tracks-1-brightgreen)]()
[![Courses](https://img.shields.io/badge/Courses-5-blue)]()
[![Language](https://img.shields.io/badge/Language-Python%203.11+-blue)]()

</div>

---

## What is AHappyNet?

**AHappyNet** is an open educational platform that organizes deep technical learning into structured, production-first **learning tracks**. Each track is a self-contained program spanning theory, engineering, and research — designed to carry you from first principles to deployed, evaluated systems.

This repository is the **entry point and coordinator** of the ecosystem. It maps the learning landscape, connects tracks, and sets shared standards that apply across every course.

```
AHappyNet
│
├── 🤖  Multi-Agent Systems         ← Active · 5 courses · 65 weeks
├── 🧠  Deep Learning Engineering   ← Planned
├── 📊  MLOps & AI Systems          ← Planned
└── 🔬  AI Safety & Alignment       ← Planned
```

> **Core philosophy**: Every track is production-first. No demo-only notebooks.  
> Every concept taught is also deployed, evaluated, and documented as research.

---

## 🤖 Multi-Agent Systems Track

> *From symbolic agents to LLM orchestration — build systems that think, coordinate, and learn.*

The MAS Track is a 5-course, 65-week program that teaches you to design, implement, and research intelligent systems composed of multiple interacting agents. It moves systematically through four paradigms — theory, engineering, learning, and language — before synthesizing them in an open-ended research capstone.

### Track at a Glance

| | Course | Duration | Paradigm | Focus |
|---|--------|----------|----------|-------|
| 1️⃣ | [MAS Foundations](#course-1--mas-foundations) | 13 weeks | Theory | BDI, game theory, mechanism design, emergence |
| 2️⃣ | [MAS Programming](#course-2--mas-programming--simulation) | 13 weeks | Engineering | Jason, SPADE, Mesa, protocols, testing |
| 3️⃣ | [MARL](#course-3--multi-agent-reinforcement-learning) | 13 weeks | Learning | QMIX, MADDPG, MAPPO, self-play |
| 4️⃣ | [LLM Agents](#course-4--llm-multi-agent-systems--orchestration) | 13 weeks | Language | LangGraph, CrewAI, RAG, deployment |
| 5️⃣ | [Capstone Studio](#course-5--capstone-research-studio) | 13 weeks | Research | Integration project + research paper |

**Total**: 65 weeks · ~325 hours · entry to publication-quality research

---

## Course 1 · MAS Foundations

**Repository**: [`mas-foundations`](https://github.com/CocAgent/mas-foundations)

The theoretical backbone of the entire track. Establishes the vocabulary — agents, rationality, BDI reasoning, Nash Equilibrium, mechanism design — that every subsequent course builds on.

**You build**: Schelling segregation model · 8-strategy Prisoner's Dilemma tournament · Vickrey + First-price auction simulator · Mesa emergence simulations

**Key insight**: Intelligence in multi-agent systems emerges from *interactions*, not from individual agents alone.

→ [Full README](https://github.com/CocAgent/mas-foundations#readme) · [Week-by-week notes](https://github.com/CocAgent/mas-foundations/tree/master/weeks)

---

## Course 2 · MAS Programming & Simulation

**Repository**: [`mas-programming`](https://github.com/CocAgent/mas-programming)

Bridges theory to production code. Every K1 concept is implemented, tested, and stress-tested. Introduces professional skills rarely taught alongside agent theory: testing multi-agent systems, profiling at scale, and modeling trust.

**You build**: BDI agent in Python + Jason · Full FIPA Contract Net Protocol (5-phase, with timeout and failure) · SEIR epidemic on 3 network topologies · ACO for TSP · Boids flocking · Nagel–Schreckenberg traffic · Beta reputation system with deceptive agent detection

**40+ unit tests** · SPADE XMPP integration · async testing patterns

**Key insight**: The same BDI loop that looks clean on paper requires careful engineering. Testing, error handling, and timing matter enormously.

→ [Full README](https://github.com/CocAgent/mas-programming#readme) · [Week-by-week notes](https://github.com/CocAgent/mas-programming/tree/master/weeks)

---

## Course 3 · Multi-Agent Reinforcement Learning

**Repository**: [`mas-marl`](https://github.com/CocAgent/mas-marl)

The learning paradigm: agents that discover strategies through experience. Covers the complete MARL landscape from first principles (why IQL fails) to state-of-the-art (QMIX, MADDPG, MAPPO) to the engineering discipline that produces credible results.

**You build**: Double DQN · QMIX with GRU agent network + hypernetwork · MADDPG · MAPPO · CommNet + DIAL learned communication · TicTacToe self-play with ELO + policy pool of 50 · Lagrangian safe MARL

**45+ unit tests** · TensorBoard integration · reproducibility standard (5 seeds, mean ± std, Welch's t-test)

**Key insight**: Agents can discover strategies no one programmed — but only with careful experiment design, or you can't tell signal from noise.

→ [Full README](https://github.com/CocAgent/mas-marl#readme) · [Week-by-week notes](https://github.com/CocAgent/mas-marl/tree/master/weeks)

---

## Course 4 · LLM Multi-Agent Systems & Orchestration

**Repository**: [`mas-llm-agents`](https://github.com/CocAgent/mas-llm-agents)

Applies multi-agent principles to the most commercially relevant paradigm in applied AI today. Production-first: the standard is not "runs in a notebook" but "deployed, evaluated, cost-tracked, and secured."

**You build**: ReAct from scratch (no framework) · Reflexion loop · Tree of Thoughts BFS · LangGraph research pipeline with HITL · CrewAI 3-agent crew · AutoGen GroupChat with code execution · ChromaDB + BM25 hybrid RAG · LLM-as-Judge with position-bias mitigation · 3-tier ModelRouter (60–80% cost reduction) · Prompt injection defense + PIIDetector · FastAPI + Docker + Prometheus + circuit breaker

**55+ unit tests** · All labs run mock-mode (no API keys needed)

**Key insight**: LLM agents are powerful but expensive and fragile. Engineering discipline separates prototypes from production.

→ [Full README](https://github.com/CocAgent/mas-llm-agents#readme) · [Week-by-week notes](https://github.com/CocAgent/mas-llm-agents/tree/master/weeks)

---

## Course 5 · Capstone Research Studio

**Repository**: [`mas-capstone`](https://github.com/CocAgent/mas-capstone)

Not a course — a research studio. Teams of 2–4 build a production multi-agent system integrating K1–K4 knowledge, run controlled experiments, analyze emergent behaviors, and produce a publication-quality paper.

**Four flagship projects**:

| Project | Research Question | K1–K4 Integration |
|---------|------------------|--------------------|
| [Agent Tutor System](https://github.com/CocAgent/mas-capstone/tree/master/projects/project-01-agent-tutor) | Does adaptive content delivery improve learning? | BDI + RAG + LLM-Judge |
| [Agent Research Team](https://github.com/CocAgent/mas-capstone/tree/master/projects/project-02-research-team) | Can agents write expert-rated literature reviews? | Protocols + CrewAI + Reflexion |
| [MARL Market Simulator](https://github.com/CocAgent/mas-capstone/tree/master/projects/project-03-market-simulator) | When does price discovery peak? | Game Theory + Mesa + QMIX |
| [Adaptive Learning Coordinator](https://github.com/CocAgent/mas-capstone/tree/master/projects/project-04-adaptive-coordinator) | Does AI allocation reduce at-risk students? | Mechanism design + MARL + FastAPI |

**Final deliverables**: Working system (Docker Compose) + Research paper (NeurIPS format) + Demo Day

→ [Full README](https://github.com/CocAgent/mas-capstone#readme) · [Studio guide](https://github.com/CocAgent/mas-capstone/blob/master/docs/studio-guide.md) · [Week-by-week notes](https://github.com/CocAgent/mas-capstone/tree/master/weeks)

---

## Who Is This For?

**Primary audience**: Software engineers and CS students who want to move beyond single-model AI and build *systems* where multiple agents reason, communicate, and coordinate.

### Entry Points by Background

| Your Background | Recommended Start |
|---|---|
| CS fundamentals, no prior AI | Course 1 |
| Comfortable with Python + basic ML | Course 2 or 3 |
| Know RL, want multi-agent depth | Course 3 (skim K1–K2 theory) |
| LLM engineer wanting MAS foundations | Course 4 (read K1–K2 theory) |
| Researcher ready to build | Course 5 (requires K1–K4 competence) |

### Prerequisites

```
Python 3.x proficiency
    └──► Course 1   (no other prerequisites)
              └──► Course 2   (K1 required)
                        └──► Course 3   (K1+K2, PyTorch helpful)
                                  └──► Course 4   (K1–K3 recommended)
                                            └──► Course 5   (K1–K4 required)
```

---

## What You Gain

**After Course 1**: Formal vocabulary for multi-agent systems; ability to model strategic interactions; simulation fluency.

**After Course 2**: Production BDI agents; XMPP-based multi-agent communication; simulation at scale; MAS testing and security.

**After Course 3**: MARL algorithms from scratch (QMIX, MADDPG, MAPPO); reproducible research practice; self-play and emergent behavior analysis.

**After Course 4**: LLM agent engineering end-to-end: from ReAct to production FastAPI; RAG; cost optimization; security; evaluation.

**After Course 5**: A production multi-agent system; a research paper; the ability to independently scope and execute AI research.

---

## Concepts Across the Track

The same ideas deepen across all five courses:

| Concept | K1 | K2 | K3 | K4 | K5 |
|---------|-----|-----|-----|-----|-----|
| **BDI** | Theory | Jason + Python | — | ReAct loop | StudentModel |
| **Communication** | FIPA-ACL spec | SPADE XMPP | — | Tool calling | Agent interfaces |
| **Shared Memory** | Blackboard concept | SPADE impl | — | SharedAgentMemory | K4 + Redis |
| **Coordination** | Contract Net | Full CNP | CTDE | CrewAI | All 4 projects |
| **Simulation** | Mesa intro | Mesa advanced | RL environments | — | Market simulator |
| **Evaluation** | — | Unit tests | ELO + statistics | LLM-as-Judge | Full harness |
| **Safety** | Mechanism design | FIPA validation | Lagrangian MARL | Guardrails | Production audit |
| **Emergence** | Schelling, ACO | Boids, traffic | Hide-and-Seek | — | Market behaviors |

---

## Standards Shared Across All Tracks

Every course in the AHappyNet ecosystem follows these non-negotiable standards:

- **All code** has type hints, docstrings, and a passing test suite
- **All systems** run without API keys via `--mock` flag
- **All courses** include cost analysis and security considerations
- **All capstone projects** produce a deployable system and a research document
- **Experiments** report mean ± std over ≥5 seeds with statistical significance tests

---

## AHappyNet Ecosystem

The MAS Track is one program within the AHappyNet ecosystem. Planned tracks will follow the same structure:

```
AHappyNet
│
├── 🤖 Multi-Agent Systems      ← Active (5 courses)
│
├── 🧠 Deep Learning Engineering   ← Planned
│   Neural architectures → training pipelines → deployment
│
├── 📊 MLOps & AI Systems          ← Planned
│   Data pipelines → model serving → monitoring → A/B testing
│
└── 🔬 AI Safety & Alignment       ← Planned
    Interpretability → RLHF → Constitutional AI → red-teaming
```

Shared infrastructure between tracks:
- Assessment rubric design philosophy
- Code quality standards (ruff, mypy, pytest)
- Deployment templates (Docker, FastAPI, CI/CD)
- Research paper standards (NeurIPS format, reproducibility)

---

## Getting Started

```bash
# Choose your entry point (see table above)
# Then clone the appropriate repository:

git clone https://github.com/CocAgent/mas-foundations.git    # Start here if new
# or
git clone https://github.com/CocAgent/mas-programming.git
# or
git clone https://github.com/CocAgent/mas-marl.git
# or
git clone https://github.com/CocAgent/mas-llm-agents.git
# or
git clone https://github.com/CocAgent/mas-capstone.git        # After completing K1–K4

# Each repository has the same first two steps:
cd <repo>
python labs/lab-00-setup/verify_setup.py
```

---

## Contributing

AHappyNet is open to contributions across all courses:

- **Corrections and improvements**: open an issue or PR in the relevant course repository
- **New labs or examples**: follow the `labs/` structure of the relevant course
- **Paper additions**: add to `resources/papers.md` with a one-sentence annotation
- **New learning tracks**: open an issue in this repository with a track scope proposal

See `CONTRIBUTING.md` for style guidelines and review process.

---

## Reference Index

### Textbooks

| Book | Track Usage |
|---|---|
| Wooldridge — *Introduction to MultiAgent Systems* (2nd Ed.) | K1, K2, K5 |
| Shoham & Leyton-Brown — *Multiagent Systems* (free PDF) | K1, K3 |
| Sutton & Barto — *Reinforcement Learning: An Introduction* | K3 |
| Albrecht et al. — *Multi-Agent Deep RL* (free PDF) | K3 |
| Chip Huyen — *AI Engineering* | K4 |

### Key Papers

| Paper | Course |
|---|---|
| Rao & Georgeff (1995) — BDI Agents | K1–K2 |
| Mnih et al. (2015) — DQN | K3 |
| Rashid et al. (2018) — QMIX | K3 |
| Lowe et al. (2017) — MADDPG | K3 |
| Baker et al. (2019) — Emergent Tool Use | K3 |
| Yao et al. (2022) — ReAct | K4 |
| Shinn et al. (2023) — Reflexion | K4 |
| Lewis et al. (2020) — RAG | K4 |
| Zheng et al. (2023) — LLM-as-Judge | K4 |
| Greshake et al. (2023) — Prompt Injection | K4 |
| Henderson et al. (2018) — Deep RL that Matters | K3, K5 |

Full annotated reading lists are in `resources/papers.md` in each course repository.

---

<div align="center">

**AHappyNet** · Open Education · Production-First · Research-Driven

*Build things that matter, then tell the world about them.*

</div>
