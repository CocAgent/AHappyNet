# 🗺️ ROADMAP — CocAgent Learning Path

> Tài liệu này theo dõi trạng thái và kế hoạch phát triển của toàn bộ hệ sinh thái khóa học.

---

## Trạng thái hiện tại

### 🐍 Python (Phase 1)

| Repo | Trạng thái | Nội dung | Ghi chú |
|------|-----------|---------|---------|
| [python-journey](https://github.com/CocAgent/python-journey) | 🟡 Đang phát triển | W01–W15 | Nền tảng |
| [python-mastery](https://github.com/CocAgent/python-mastery) | 🟡 Đang phát triển | W01–W12 | Advanced Python |
| [dsa-python-course](https://github.com/CocAgent/dsa-python-course) | 🟡 Đang phát triển | W01–W15 | DSA + 200+ bài |
| [data-python-course](https://github.com/CocAgent/data-python-course) | 🟡 Đang phát triển | W01–W15 | Data + 10 projects |
| [automation-python-course](https://github.com/CocAgent/automation-python-course) | 🟡 Đang phát triển | W01–W15 | Automation + 15 tools |

### ⚙️ C++ (Phase 1)

| Repo | Trạng thái | Nội dung | Ghi chú |
|------|-----------|---------|---------|
| [cpp-foundation](https://github.com/CocAgent/cpp-foundation) | 🟡 Đang phát triển | W01–W15 | C++17 cơ bản |
| [cpp-development](https://github.com/CocAgent/cpp-development) | 🟡 Đang phát triển | W01–W15 | C++20 nâng cao |
| [dsa-cpp-course](https://github.com/CocAgent/dsa-cpp-course) | 🟡 Đang phát triển | W01–W15 | DSA + 8 projects |

### 🤖 Multi-Agent Systems (Phase 1)

| Repo | Trạng thái | Nội dung | Ghi chú |
|------|-----------|---------|---------|
| [mas-foundations](https://github.com/CocAgent/mas-foundations) | 🟡 Đang phát triển | W01–W13 | Lý thuyết MAS |
| [mas-programming](https://github.com/CocAgent/mas-programming) | 🟡 Đang phát triển | W01–W13 | Lập trình agent |
| [mas-marl](https://github.com/CocAgent/mas-marl) | 🟡 Đang phát triển | W01–W13 | Multi-Agent RL |
| [mas-llm](https://github.com/CocAgent/mas-llm) | 🟡 Đang phát triển | W01–W13 | LLM-based agents |
| [mas-capstone](https://github.com/CocAgent/mas-capstone) | 🟡 Đang phát triển | W01–W13 | Capstone project |

### 🔗 AI Agent Protocols (Phase 1)

| Repo | Trạng thái | Nội dung | Ghi chú |
|------|-----------|---------|---------|
| [aap-bootcamp](https://github.com/CocAgent/aap-bootcamp) | 🟡 Đang phát triển | W01–W10 | Bootcamp nhanh |
| [aap-communication](https://github.com/CocAgent/aap-communication) | 🟡 Đang phát triển | W01–W13 | Agent communication |
| [aap-protocols](https://github.com/CocAgent/aap-protocols) | 🟡 Đang phát triển | W01–W13 | Protocol design |
| [aap-modern](https://github.com/CocAgent/aap-modern) | 🟡 Đang phát triển | W01–W13 | MCP · A2A |
| [aap-coordination](https://github.com/CocAgent/aap-coordination) | 🟡 Đang phát triển | W01–W13 | Coordination |
| [aap-production](https://github.com/CocAgent/aap-production) | 🟡 Đang phát triển | W01–W16 | K8s · Production |

### 🏛️ Software Architecture & Engineering (Phase 1) `MỚI`

| Repo | Trạng thái | Nội dung | Ghi chú |
|------|-----------|---------|---------|
| [sae-thinking](https://github.com/CocAgent/sae-thinking) | 🟡 Đang phát triển | W01–W12 | Tư duy hệ thống · Deep module · Complexity |
| [sae-architecture](https://github.com/CocAgent/sae-architecture) | 🟡 Đang phát triển | W01–W15 | Kiến trúc PM · Hexagonal · DDD · ADR |
| [sae-building](https://github.com/CocAgent/sae-building) | 🟡 Đang phát triển | W01–W12 | Code sạch · CI/CD · Module rõ |
| [sae-scaling](https://github.com/CocAgent/sae-scaling) | 🟡 Đang phát triển | W01–W15 | Evolutionary arch · DDIA · Team Topologies |
| [sae-evolution](https://github.com/CocAgent/sae-evolution) | 🟡 Đang phát triển | W01–W12 | Refactoring · Legacy code · Pattern evolution |

**Chú giải:** 🔴 Chưa bắt đầu · 🟡 Đang phát triển · 🟢 Hoàn thành · 🔵 Đang bảo trì

---

## Phase 1 — Hoàn thiện nội dung (Hiện tại)

**Mục tiêu:** Tất cả 24 repo có đủ nội dung cho từng tuần.

### Checklist mỗi tuần trong mỗi repo

- `README.md` — mục tiêu + checklist + tài liệu tham khảo
- `lecture/` — ít nhất 2 file code mẫu có comment đầy đủ
- `exercises/` — đề bài 3 cấp độ với gợi ý
- `solutions/` — lời giải với giải thích trade-offs
- `resources/` — link tài liệu cụ thể cho tuần đó

### Ưu tiên hoàn thiện

1. **python-journey** — nhiều người bắt đầu nhất
2. **cpp-foundation** — entry point cho C++
3. **sae-thinking** — entry point cho Software Architecture `MỚI`
4. **dsa-python-course** + **dsa-cpp-course** — nhu cầu phỏng vấn cao
5. **sae-architecture** — trục kiến trúc, khóa quan trọng nhất của SAE `MỚI`
6. **python-mastery** — prerequisite cho 3 nhánh chuyên ngành
7. **data-python-course** + **automation-python-course** — nhánh chuyên ngành
8. **cpp-development** — C++20 advanced
9. **sae-building** → **sae-scaling** → **sae-evolution** — hoàn thiện SAE pipeline `MỚI`

---

## Phase 2 — Mở rộng chuyên ngành

### Python nâng cao

| Repo (dự kiến) | Nội dung | Tiên quyết | ETA |
|----------------|---------|-----------|-----|
| `web-python-course` | FastAPI · Django REST · async web | Mastery | TBD |
| `ml-python-course` | PyTorch · scikit-learn · MLOps | Data | TBD |
| `system-python-course` | CPython internals · C extensions | Mastery | TBD |

### C++ nâng cao

| Repo (dự kiến) | Nội dung | Tiên quyết | ETA |
|----------------|---------|-----------|-----|
| `cpp-systems` | OS · Memory · Networking | Development | TBD |
| `cpp-embedded` | Bare-metal · RTOS · Arduino | Development | TBD |
| `cpp-interview` | Curated problems + solutions | DSA | TBD |

### 🏛️ SAE nâng cao `MỚI`

| Repo (dự kiến) | Nội dung | Tiên quyết | ETA |
|----------------|---------|-----------|-----|
| `sae-distributed` | Distributed systems design · CAP · Consensus | sae-scaling | TBD |
| `sae-cloud-native` | Cloud architecture · K8s · Terraform · Serverless | sae-scaling | TBD |
| `sae-ddd-advanced` | DDD sâu: Event Sourcing · CQRS · Saga pattern | sae-architecture | TBD |
| `sae-platform-engineering` | Platform teams · Internal Developer Platform · DevEx | sae-scaling | TBD |

---

## Phase 3 — Hạ tầng học tập

| Tính năng | Mô tả | Công cụ |
|-----------|-------|---------|
| **Auto-grading** | Chạy tests tự động khi học viên push | GitHub Actions + pytest/GTest |
| **Progress tracking** | Dashboard theo dõi tiến độ | GitHub Pages |
| **Unified template** | Starter project chuẩn hóa | Cookiecutter |
| **Pre-commit hooks** | Đảm bảo code quality tự động | pre-commit |
| **Issue templates** | Form báo lỗi chuẩn cho mỗi repo | GitHub Templates |
| **SAE fitness functions** | Auto-check architectural constraints trong bài tập SAE | GitHub Actions + custom scripts `MỚI` |

---

## Tổng quan quy mô

| Chương trình | Số khóa | Số tuần | Giờ học | Repos |
|-------------|---------|---------|---------|-------|
| 🐍 Python | 5 | 72 | ~720h | 5 |
| ⚙️ C++ | 3 | 45 | ~540h | 3 |
| 🤖 MAS | 5 | 65 | ~560h | 5 |
| 🔗 AAP | 6 | 78 | ~650h | 6 |
| 🏛️ SAE | 5 | 66 | ~600h | 5 |
| **Tổng** | **24** | **326** | **~3.070h** | **24** |

---

## Đề xuất tính năng mới

Có ý tưởng cho khóa học mới hoặc cải tiến? Mở [Feature Request](https://github.com/CocAgent/AHappyNet/issues/new).

Ưu tiên được tính dựa trên: số lượng upvote (👍) trên Issue + alignment với roadmap.

---

*Cập nhật lần cuối: 2026 · Roadmap có thể thay đổi theo phản hồi từ cộng đồng*
