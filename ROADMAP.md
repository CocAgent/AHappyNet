# 🗺️ ROADMAP — CocAgent Learning Path

> Tài liệu này theo dõi trạng thái và kế hoạch phát triển của toàn bộ hệ sinh thái khóa học.

---

## Trạng thái hiện tại

### 🐍 Python (Phase 1)

| Repo | Trạng thái | Nội dung | Ghi chú |
|---|---|---|---|
| [python-journey](https://github.com/CocAgent/python-journey) | 🟡 Đang phát triển | W01–W15 | Nền tảng |
| [python-mastery](https://github.com/CocAgent/python-mastery) | 🟡 Đang phát triển | W01–W12 | Advanced Python |
| [dsa-python-course](https://github.com/CocAgent/dsa-python-course) | 🟡 Đang phát triển | W01–W15 | DSA + 200+ bài |
| [data-python-course](https://github.com/CocAgent/data-python-course) | 🟡 Đang phát triển | W01–W15 | Data + 10 projects |
| [automation-python-course](https://github.com/CocAgent/automation-python-course) | 🟡 Đang phát triển | W01–W15 | Automation + 15 tools |

### ⚙️ C++ (Phase 1)

| Repo | Trạng thái | Nội dung | Ghi chú |
|---|---|---|---|
| [cpp-foundation](https://github.com/CocAgent/cpp-foundation) | 🟡 Đang phát triển | W01–W15 | C++17 cơ bản |
| [cpp-development](https://github.com/CocAgent/cpp-development) | 🟡 Đang phát triển | W01–W15 | C++20 nâng cao |
| [dsa-cpp-course](https://github.com/CocAgent/dsa-cpp-course) | 🟡 Đang phát triển | W01–W15 | DSA + 8 projects |

**Chú giải:** 🔴 Chưa bắt đầu · 🟡 Đang phát triển · 🟢 Hoàn thành · 🔵 Đang bảo trì

---

## Phase 1 — Hoàn thiện nội dung (Hiện tại)

**Mục tiêu:** Tất cả 8 repo có đủ nội dung cho từng tuần.

### Checklist mỗi tuần trong mỗi repo
- [ ] `README.md` — mục tiêu + checklist + tài liệu tham khảo
- [ ] `lecture/` — ít nhất 2 file code mẫu có comment đầy đủ
- [ ] `exercises/` — đề bài 3 cấp độ với gợi ý
- [ ] `solutions/` — lời giải với giải thích trade-offs
- [ ] `resources/` — link tài liệu cụ thể cho tuần đó

### Ưu tiên hoàn thiện
1. **python-journey** — nhiều người bắt đầu nhất
2. **cpp-foundation** — entry point cho C++
3. **dsa-python-course** + **dsa-cpp-course** — nhu cầu phỏng vấn cao
4. **python-mastery** — prerequisite cho 3 nhánh chuyên ngành
5. **data-python-course** + **automation-python-course** — nhánh chuyên ngành
6. **cpp-development** — C++20 advanced

---

## Phase 2 — Mở rộng chuyên ngành

### Python nâng cao

| Repo (dự kiến) | Nội dung | Tiên quyết | ETA |
|---|---|---|---|
| `web-python-course` | FastAPI · Django REST · async web | Mastery | TBD |
| `ml-python-course` | PyTorch · scikit-learn · MLOps | Data | TBD |
| `system-python-course` | CPython internals · C extensions | Mastery | TBD |

### C++ nâng cao

| Repo (dự kiến) | Nội dung | Tiên quyết | ETA |
|---|---|---|---|
| `cpp-systems` | OS · Memory · Networking | Development | TBD |
| `cpp-embedded` | Bare-metal · RTOS · Arduino | Development | TBD |
| `cpp-interview` | Curated problems + solutions | DSA | TBD |

---

## Phase 3 — Hạ tầng học tập

| Tính năng | Mô tả | Công cụ |
|---|---|---|
| **Auto-grading** | Chạy tests tự động khi học viên push | GitHub Actions + pytest/GTest |
| **Progress tracking** | Dashboard theo dõi tiến độ | GitHub Pages |
| **Unified template** | Starter project chuẩn hóa | Cookiecutter |
| **Pre-commit hooks** | Đảm bảo code quality tự động | pre-commit |
| **Issue templates** | Form báo lỗi chuẩn cho mỗi repo | GitHub Templates |

---

## Đề xuất tính năng mới

Có ý tưởng cho khóa học mới hoặc cải tiến? Mở [Feature Request](.github/ISSUE_TEMPLATE/feature_request.md).

Ưu tiên được tính dựa trên: số lượng upvote (👍) trên Issue + alignment với roadmap.

---

*Cập nhật lần cuối: 2025 · Roadmap có thể thay đổi theo phản hồi từ cộng đồng*
