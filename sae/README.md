# 🏛️ Software Architecture & Engineering

[![SAE](https://img.shields.io/badge/%F0%9F%8F%9B%EF%B8%8F%20SAE-5%20Kh%C3%B3a%20%C2%B7%2066%20Tu%E1%BA%A7n-8B4513?style=for-the-badge)](.)
[![License: MIT](https://img.shields.io/badge/License-MIT-22c55e?style=flat-square)](../LICENSE)

> *Từ người viết code thành người thiết kế hệ thống — qua 5 khóa học, 66 tuần, với tư duy tiến hóa, không cách mạng.*

---

## Tầm nhìn

Chương trình này dạy bạn **nghĩ về hệ thống** trước khi nghĩ về code. Không dạy pattern như đơn thuốc. Dạy nhận diện vấn đề trước, rồi pattern xuất hiện như giải pháp tự nhiên.

```
Tư duy → Kiến trúc → Xây dựng → Mở rộng → Tiến hóa
  K1         K2          K3         K4         K5
```

---

## Năm khóa học

| # | Khóa | Repo | Tuần | Trọng tâm |
|---|------|------|------|-----------|
| ① | Tư duy hệ thống | [sae-thinking](https://github.com/CocAgent/sae-thinking) | 12W | Nhận diện phức tạp, giảm coupling, deep module |
| ② | Kiến trúc phần mềm | [sae-architecture](https://github.com/CocAgent/sae-architecture) | 15W | Patterns, boundaries, ADR, DDD cơ bản |
| ③ | Xây dựng hệ thống | [sae-building](https://github.com/CocAgent/sae-building) | 12W | Code sạch, module rõ, flow rõ ràng |
| ④ | Phát triển & mở rộng | [sae-scaling](https://github.com/CocAgent/sae-scaling) | 15W | Evolutionary architecture, team topology, data systems |
| ⑤ | Tái cấu trúc & tiến hóa | [sae-evolution](https://github.com/CocAgent/sae-evolution) | 12W | Refactoring, legacy code, pattern evolution |

---

## Đối tượng

Developer có **1–3 năm kinh nghiệm**, đã viết được code hoạt động nhưng:
- Chưa biết tổ chức hệ thống
- Chưa nhận ra boundary sai, flow rối, coupling quá chặt
- Muốn chuyển từ "code chạy được" sang "hệ thống bảo trì được"

**Ngôn ngữ chính:** Python (có thể mở rộng sang JS/TS)

---

## Dự án xuyên suốt

Một hệ thống duy nhất được phát triển qua 5 khóa, tiến hóa từ script đơn giản thành production-ready:

```
K1: v1 — Script đơn giản, nhận diện vấn đề cấu trúc
K2: v2 — Tổ chức lại theo kiến trúc, viết ADR
K3: v3 — Code sạch, CI/CD, module rõ ràng
K4: v4 — Multi-service, scalable, đo lường được
K5: v5 — Refactored, tested, production-ready
```

---

## Ba lớp phủ xuyên suốt

Mỗi khóa đều có 3 hoạt động chạy song song:

1. **Phân tích & đánh giá hệ thống** — Nhận codebase thực tế, viết báo cáo phân tích
2. **Dự án xuyên suốt** — Hệ thống lớn dần theo từng khóa
3. **Tài liệu kỹ thuật** — ADR, README, CHANGELOG, sơ đồ kiến trúc từ tuần 1

---

## Sách cốt lõi

| # | Sách | Khóa |
|---|------|------|
| 1 | A Philosophy of Software Design (Ousterhout) | K1 |
| 2 | The Pragmatic Programmer (Hunt & Thomas) | K1, K3 |
| 3 | Fundamentals of Software Architecture (Richards & Ford) | K2 |
| 4 | Architecture Patterns with Python (Percival & Gregory) | K2, K3 |
| 5 | Building Evolutionary Architectures (Ford et al.) | K4 |
| 6 | Team Topologies (Skelton & Pais) | K4 |
| 7 | Designing Data-Intensive Applications, 2nd ed. (2026) | K4 |
| 8 | Refactoring, 2nd ed. (Fowler) | K5 |
| 9 | Working Effectively with Legacy Code (Feathers) | K5 |

---

## GitHub Repos tham khảo

| Repo | Khóa | Mục đích |
|------|------|----------|
| [thoughtbot/guides](https://github.com/thoughtbot/guides) | K1, K3 | Code style, review, teamwork |
| [donnemartin/system-design-primer](https://github.com/donnemartin/system-design-primer) | K2, K4 | Case study scalable systems |
| [cosmicpython/book](https://github.com/cosmicpython/book) + [code](https://github.com/cosmicpython/code) | K2, K3 | Kiến trúc ứng dụng Python |
| [joelparkerhenderson/architecture-decision-record](https://github.com/joelparkerhenderson/architecture-decision-record) | K2+ | ADR template & ví dụ |
| [mehdihadeli/awesome-software-architecture](https://github.com/mehdihadeli/awesome-software-architecture) | K2, K4 | Tổng hợp tài nguyên SA |
| [binhnguyennus/awesome-scalability](https://github.com/binhnguyennus/awesome-scalability) | K4 | Patterns scale & reliability |
| [GoogleCloudPlatform/microservices-demo](https://github.com/GoogleCloudPlatform/microservices-demo) | K4 | Hệ thống mẫu nhiều service |
| [emilybache/GildedRose-Refactoring-Kata](https://github.com/emilybache/GildedRose-Refactoring-Kata) | K5 | Refactoring kata kinh điển |

---

## Số liệu

| Metric | Giá trị |
|--------|---------|
| **Số khóa** | 5 |
| **Tổng tuần** | 66 |
| **Giờ học** | ~600h |
| **Sách bắt buộc** | 9 |
| **GitHub repos** | 8+ |
| **Dự án thực hành** | 5 versions + system analysis mỗi khóa |

---

## Chọn điểm bắt đầu

```
Bạn là...                                        Bắt đầu từ
────────────────────────────────────────────────────────────────
Dev 1-2 năm, code chạy nhưng rối              →  sae-thinking (K1)
Biết OOP/patterns cơ bản, muốn kiến trúc      →  sae-architecture (K2)
Có kiến trúc, muốn code sạch hơn              →  sae-building (K3)
Muốn scale hệ thống hiện tại                  →  sae-scaling (K4)
Cần refactor legacy codebase                   →  sae-evolution (K5)
Muốn học toàn diện từ đầu                      →  K1 → K2 → K3 → K4 → K5
```

---

## Triết lý

1. **Học qua làm** — Mỗi khóa có dự án xuyên suốt từ tuần 1
2. **Tư duy trước, pattern sau** — Nhận diện vấn đề trước, pattern là giải pháp tự nhiên
3. **Tiến hóa, không cách mạng** — Hệ thống tiến hóa dần qua quyết định có kiểm soát
4. **Helper vừa đủ** — Main flow phải rõ ràng, không over-engineer
5. **Tài liệu gốc là nguồn chân lý** — Sách gốc, không phụ thuộc tutorial thứ cấp

---

**[① Thinking](https://github.com/CocAgent/sae-thinking)** · **[② Architecture](https://github.com/CocAgent/sae-architecture)** · **[③ Building](https://github.com/CocAgent/sae-building)** · **[④ Scaling](https://github.com/CocAgent/sae-scaling)** · **[⑤ Evolution](https://github.com/CocAgent/sae-evolution)** · **[↑ AHappyNet](https://github.com/CocAgent/AHappyNet)**

*MIT License · CocAgent Learning Platform · 2025–2026*
