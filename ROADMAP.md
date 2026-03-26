# 🗺️ ROADMAP — CocAgent Learning Platform

> Tài liệu này theo dõi trạng thái và kế hoạch phát triển của toàn bộ hệ sinh thái khóa học.

---

## Tổng quan hệ sinh thái

| Chương trình | Repo hub | Khóa | Tuần | Trạng thái |
|---|---|---|---|---|
| 🐍 Python | [python/README.md](python/README.md) | 5 | 72 | 🟡 Đang phát triển |
| ⚙️ C++ | [cpp/README.md](cpp/README.md) | 3 | 45 | 🟡 Đang phát triển |
| 🤖 Multi-Agent Systems | [mas/README.md](mas/README.md) | 5 | 65 | 🟡 Đang phát triển |
| 🔗 AI Agent Protocols | [aip/README.md](aip/README.md) | 6 | 78 | 🟡 Đang phát triển |
| **Tổng** | | **19** | **260** | |

**Chú giải:** 🔴 Chưa bắt đầu · 🟡 Đang phát triển · 🟢 Hoàn thành · 🔵 Đang bảo trì

---

## Trạng thái chi tiết

### 🐍 Python Learning Path

| Repo | Trạng thái | Nội dung | Ghi chú |
|---|---|---|---|
| [python-journey](https://github.com/CocAgent/python-journey) | 🟡 Đang phát triển | W01–W15 | Nền tảng cho người mới |
| [python-mastery](https://github.com/CocAgent/python-mastery) | 🟡 Đang phát triển | W01–W12 | Advanced Python |
| [dsa-python-course](https://github.com/CocAgent/dsa-python-course) | 🟡 Đang phát triển | W01–W15 | DSA + 200+ bài tập |
| [data-python-course](https://github.com/CocAgent/data-python-course) | 🟡 Đang phát triển | W01–W15 | Data + 10 dự án |
| [automation-python-course](https://github.com/CocAgent/automation-python-course) | 🟡 Đang phát triển | W01–W15 | Automation + 15 tools |

### ⚙️ C++ Learning Path

| Repo | Trạng thái | Nội dung | Ghi chú |
|---|---|---|---|
| [cpp-foundation](https://github.com/CocAgent/cpp-foundation) | 🟡 Đang phát triển | W01–W15 | C++17 cơ bản |
| [cpp-development](https://github.com/CocAgent/cpp-development) | 🟡 Đang phát triển | W01–W15 | C++20 nâng cao |
| [dsa-cpp-course](https://github.com/CocAgent/dsa-cpp-course) | 🟡 Đang phát triển | W01–W15 | DSA + 8 dự án |

### 🤖 Multi-Agent Systems Track

| Repo | Trạng thái | Nội dung | Ghi chú |
|---|---|---|---|
| [mas-foundations](https://github.com/CocAgent/mas-foundations) | 🟡 Đang phát triển | W01–W13 | BDI, Game Theory, Mesa |
| [mas-programming](https://github.com/CocAgent/mas-programming) | 🟡 Đang phát triển | W01–W13 | Jason, SPADE, CNP |
| [mas-marl](https://github.com/CocAgent/mas-marl) | 🟡 Đang phát triển | W01–W13 | QMIX, MADDPG, Self-Play |
| [mas-llm-agents](https://github.com/CocAgent/mas-llm-agents) | 🟡 Đang phát triển | W01–W13 | LangGraph, CrewAI, RAG |
| [mas-capstone](https://github.com/CocAgent/mas-capstone) | 🟡 Đang phát triển | W01–W13 | Research Studio + Paper |

### 🔗 AI Agent Protocols Track

| Repo | Trạng thái | Nội dung | Ghi chú |
|---|---|---|---|
| [mas-bootcamp](https://github.com/CocAgent/mas-bootcamp) | 🟡 Đang phát triển | W01–W10 | Agent đầu tiên, LLM API |
| [mas-communication](https://github.com/CocAgent/mas-communication) | 🟡 Đang phát triển | W01–W13 | FIPA-ACL, SPADE, Messaging |
| [mas-protocols](https://github.com/CocAgent/mas-protocols) | 🟡 Đang phát triển | W01–W13 | CNP, Auction, REST, gRPC |
| [modern-agent-protocols](https://github.com/CocAgent/modern-agent-protocols) | 🟡 Đang phát triển | W01–W13 | A2A, MCP, ANP, SSE |
| [mas-coordination](https://github.com/CocAgent/mas-coordination) | 🟡 Đang phát triển | W01–W13 | Raft, ZooKeeper, Consensus |
| [mas-production](https://github.com/CocAgent/mas-production) | 🟡 Đang phát triển | W01–W16 | K8s, Istio, Observability |

---

## Phase 1 — Hoàn thiện nội dung (Hiện tại)

**Mục tiêu:** Tất cả 19 repo có đủ nội dung cho từng tuần.

### Checklist mỗi tuần trong mỗi repo

- `weeks/week-NN/notes.md` — lý thuyết + ví dụ code + câu hỏi tư duy
- `labs/` — bài lab thực hành với `--mock` mode (không cần API/infrastructure)
- `tests/` — pytest coverage ≥ 70%
- `README.md` — mục tiêu + curriculum + quick start

### Ưu tiên hoàn thiện (theo nhu cầu người học)

**Python & C++ (nhu cầu cao nhất):**
1. `python-journey` — nhiều người bắt đầu nhất
2. `cpp-foundation` — entry point cho C++
3. `dsa-python-course` + `dsa-cpp-course` — nhu cầu phỏng vấn cao
4. `python-mastery` — prerequisite cho 3 nhánh chuyên ngành
5. `data-python-course` + `automation-python-course`
6. `cpp-development`

**MAS Track (bổ sung nội dung chuyên sâu):**
7. `mas-foundations` — lý thuyết nền tảng
8. `mas-programming` — triển khai thực tế
9. `mas-marl` — MARL algorithms
10. `mas-llm-agents` — LLM orchestration
11. `mas-capstone` — nghiên cứu tổng hợp

**AAP Track (bổ sung nội dung hạ tầng):**
12. `mas-bootcamp` — điểm vào nhanh
13. `mas-communication` — giao tiếp agent
14. `mas-protocols` — giao thức chuẩn
15. `modern-agent-protocols` — A2A, MCP
16. `mas-coordination` — phân tán
17. `mas-production` — production deploy

---

## Phase 2 — Mở rộng chuyên ngành

### Python nâng cao

| Repo (dự kiến) | Nội dung | Tiên quyết | ETA |
|---|---|---|---|
| `web-python-course` | FastAPI · Django REST · async web | python-mastery | TBD |
| `ml-python-course` | PyTorch · scikit-learn · MLOps | data-python | TBD |
| `system-python-course` | CPython internals · C extensions | python-mastery | TBD |

### C++ nâng cao

| Repo (dự kiến) | Nội dung | Tiên quyết | ETA |
|---|---|---|---|
| `cpp-systems` | OS · Memory · Networking | cpp-development | TBD |
| `cpp-embedded` | Bare-metal · RTOS · Arduino | cpp-development | TBD |

### AI / MAS mở rộng

| Repo (dự kiến) | Nội dung | Tiên quyết | ETA |
|---|---|---|---|
| `deep-learning-engineering` | PyTorch · training · serving | mas-marl | TBD |
| `mlops-ai-systems` | MLflow · Kubeflow · model serving | mas-production | TBD |
| `ai-safety-alignment` | RLHF · Constitutional AI · red-teaming | mas-capstone | TBD |

---

## Phase 3 — Hạ tầng học tập

| Tính năng | Mô tả | Công cụ | ETA |
|---|---|---|---|
| **Auto-grading** | Chạy tests tự động khi học viên push | GitHub Actions + pytest/GTest | TBD |
| **Progress tracking** | Dashboard theo dõi tiến độ | GitHub Pages | TBD |
| **Unified template** | Starter project chuẩn hóa | Cookiecutter | TBD |
| **Pre-commit hooks** | Đảm bảo code quality tự động | pre-commit | TBD |
| **Issue templates** | Form báo lỗi chuẩn cho mỗi repo | GitHub Templates | TBD |
| **Cost tracking** | Theo dõi chi phí API trong labs MAS/AAP | Custom dashboard | TBD |

---

## Đề xuất tính năng mới

Có ý tưởng cho khóa học mới hoặc cải tiến? Mở [Feature Request](https://github.com/CocAgent/AHappyNet/blob/main/.github/ISSUE_TEMPLATE/feature_request.md).

Ưu tiên được tính dựa trên: số lượng upvote (👍) trên Issue + alignment với roadmap.

---

*Cập nhật lần cuối: 2025 · Roadmap có thể thay đổi theo phản hồi từ cộng đồng*
