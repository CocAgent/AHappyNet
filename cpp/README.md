<div align="center">

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 960 240" width="100%">
  <defs>
    <linearGradient id="hub" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#0a0a0a"/>
      <stop offset="40%" style="stop-color:#111827"/>
      <stop offset="100%" style="stop-color:#0f1f3d"/>
    </linearGradient>
    <linearGradient id="line1" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#3b82f6;stop-opacity:0"/>
      <stop offset="50%" style="stop-color:#3b82f6;stop-opacity:0.6"/>
      <stop offset="100%" style="stop-color:#3b82f6;stop-opacity:0"/>
    </linearGradient>
  </defs>
  <rect width="960" height="240" rx="14" fill="url(#hub)"/>
  <rect x="0" y="0" width="960" height="2" rx="1" fill="url(#line1)"/>
  <rect x="0" y="238" width="960" height="2" rx="1" fill="url(#line1)"/>
  <!-- Three dots like code editor -->
  <circle cx="36" cy="26" r="6" fill="#ef4444" fill-opacity="0.8"/>
  <circle cx="56" cy="26" r="6" fill="#f59e0b" fill-opacity="0.8"/>
  <circle cx="76" cy="26" r="6" fill="#22c55e" fill-opacity="0.8"/>
  <!-- Title -->
  <text x="480" y="95" font-family="Georgia, serif" font-size="42" fill="white" text-anchor="middle" font-weight="bold" letter-spacing="3">CocAgent</text>
  <text x="480" y="135" font-family="Georgia, serif" font-size="24" fill="#60a5fa" text-anchor="middle" letter-spacing="2">C++ Learning Path</text>
  <text x="480" y="175" font-family="monospace" font-size="15" fill="#6b7280" text-anchor="middle">45 tuần · ~540 giờ · Foundation → Development → DSA</text>
  <text x="480" y="210" font-family="monospace" font-size="13" fill="#374151" text-anchor="middle">Từ Hello World đến Engineer-Ready · C++17/20 · GoogleTest · CMake · Algorithms</text>
</svg>

<br/>

[![cpp-foundation](https://img.shields.io/badge/①%20Foundation-C%2B%2B17%20·%2015W-1d4ed8?style=for-the-badge)](https://github.com/CocAgent/cpp-foundation)
[![cpp-development](https://img.shields.io/badge/②%20Development-C%2B%2B20%20·%2015W-0f766e?style=for-the-badge)](https://github.com/CocAgent/cpp-development)
[![dsa-cpp-course](https://img.shields.io/badge/③%20DSA-Algorithms%20·%2015W-7c3aed?style=for-the-badge)](https://github.com/CocAgent/dsa-cpp-course)

</div>

---

## Tầm nhìn

Chương trình **CocAgent C++ Learning Path** được thiết kế với một nguyên tắc duy nhất:

> *Dạy ít hơn nhưng dạy đúng hơn — để học viên thực sự hiểu, không chỉ copy-paste.*

Ba repo tạo thành một hệ sinh thái học tập liên tục, mỗi khóa xây trực tiếp trên nền của khóa trước, với mục tiêu cuối cùng là người học **viết C++ ở mức professional** — code đúng, có thể test, có thể maintain, có hiệu năng.

---

## Toàn cảnh chương trình

```
┌────────────────────────────────────────────────────────────────────────────────┐
│                        CocAgent C++ Learning Path                              │
├─────────────────────┬──────────────────────────┬──────────────────────────────┤
│  ① cpp-foundation   │    ② cpp-development      │    ③ dsa-cpp-course          │
│  ─────────────────  │    ──────────────────────  │    ────────────────────────  │
│  C++17 · Cơ bản     │    C++20 · Nâng cao        │    C++17 · Giải thuật        │
│  15 tuần            │    15 tuần                 │    15 tuần                   │
│                     │                            │                              │
│  Nền tảng tư duy    │    Modern idioms           │    Tư duy thuật toán         │
│  Variables → OOP    │    Concepts · Ranges       │    BigO → DP                 │
│  STL basics         │    Coroutines · Modules    │    8 dự án thực tế           │
│  File I/O           │    GoogleTest (TDD)        │    Interview-ready           │
│  3 console projects │    CMake advanced          │    200+ bài tập              │
│                     │    3 C++20 projects        │                              │
│  Đầu vào: Zero      │    Đầu vào: K1 xong        │    Đầu vào: K1 T1–10        │
│  Đầu ra: K1 done    │    Đầu ra: K2 done         │    Đầu ra: Engineer-ready    │
└─────────────────────┴──────────────────────────┴──────────────────────────────┘
                              ↑ Cả 3 dùng chung ↑
           cppreference · PPP2 · cpp-best-practices · TheAlgorithms
                   + modern-cpp-features · GoogleTest (K2, K3)
```

---

## Lộ trình học đề xuất

### Con đường chuẩn (45 tuần)

```
Tháng 1–4         Tháng 4–8         Tháng 8–12
────────────      ────────────       ─────────────
cpp-foundation    cpp-development    dsa-cpp-course
   W01–W15    →      W01–W15     →      W01–W15
                                  (có thể học song song K2+K3
                                   từ sau K1 tuần 10)
```

### Con đường song song (sau K1 tuần 10)

```
K1 W10 → Rẽ nhánh:
    ├── Tiếp tục K1 W11–W15
    └── Bắt đầu K3 (DSA) song song
           ↓
        Kết thúc K1 → Bắt đầu K2
        K2 W09+ (GTest) → Áp dụng vào test K3 projects
```

### Con đường tốc hành (nếu đã biết C++ cơ bản)

```
Có kiến thức C++11/14 → Bắt đầu K2 W01 (Quick-start review)
                      → Song song K3 từ đầu
```

---

## Mối liên kết giữa các khóa

### K1 → K2: Nâng cấp từng khái niệm

| K1 (Foundation) dạy | K2 (Development) nâng lên |
|---|---|
| Class + constructor | Move constructor · Rule of Five |
| `const&` parameter | Perfect forwarding · `std::forward` |
| Raw pointer | `unique_ptr` · `shared_ptr` · `weak_ptr` |
| Template cơ bản | Concepts · Variadic · Fold expressions |
| STL containers | Concepts constrain STL · Ranges pipeline |
| `try/catch` | `std::expected` · monadic error handling |
| `const` functions | `constexpr` · `consteval` · compile-time |

### K1 → K3: Nền tảng để hiểu DSA

| K1 (Foundation) cung cấp | K3 (DSA) cần để |
|---|---|
| Con trỏ & tham chiếu | Implement LinkedList, Tree node |
| Struct với member | Represent graph vertex, tree node |
| `std::vector` | Understand dynamic array internals |
| Hàm & recursion | DFS, BFS, DP, Backtracking |
| File I/O | Persist data structures |

### K2 → K3: Tools và idioms

| K2 (Development) đóng góp | K3 (DSA) được hưởng |
|---|---|
| Concepts | `template<Comparable T> class BST` |
| Ranges/Views | Pipeline trên CTDL collections |
| GoogleTest | Test coverage cho mọi CTDL |
| Smart pointers | Tree, Graph nodes không leak |
| `std::expected` | Error handling trong graph algorithms |

---

## Tài nguyên dùng chung

Cả ba khóa đều tham chiếu tập tài nguyên sau — mỗi khóa khai thác theo cách khác nhau:

| Tài nguyên | K1 Foundation | K2 Development | K3 DSA |
|---|---|---|---|
| [cppreference.com](https://cppreference.com) | Tra cú pháp C++17 | C++20 features | STL complexity guarantees |
| [PPP2 — Stroustrup](http://103.203.175.90:81/fdScript/RootOfEBooks/E%20Book%20collection%20-%202024%20-%20D/CSE%20%20IT%20AIDS%20ML/Programming%20%20Principles%20and%20Practice%20Using%20C++%20(2024).pdf) | Ch.1–21 (cơ bản) | Ch.18–24 (nâng cao) | Ch.21 (Algorithms) |
| [TheAlgorithms/C++](https://github.com/TheAlgorithms/C-Plus-Plus) | Tham khảo sort, prime | So sánh C++20 idioms | Tham khảo sau khi tự làm |
| [cpp-best-practices](https://github.com/cpp-best-practices/cppbestpractices) | Naming, tools | Build system, testing | Performance, safety |
| [modern-cpp-features](https://github.com/AnthonyCalandra/modern-cpp-features) | — | C++11→C++23 reference | C++17 features review |
| [GoogleTest](https://google.github.io/googletest/) | — | Bắt buộc từ K2 W09 | Khuyến khích từ K3 W01 |
| [LeetCode](https://leetcode.com) | — | — | Applied problems |
| [Visualgo](https://visualgo.net) | — | — | Visualize CTDL |

---

## Số liệu chương trình

| | K1 Foundation | K2 Development | K3 DSA | Tổng |
|---|---|---|---|---|
| **Thời lượng** | 15 tuần | 15 tuần | 15 tuần | **45 tuần** |
| **Giờ học** | ~150 giờ | ~180 giờ | ~180 giờ | **~540 giờ** |
| **Bài tập** | 60+ | 80+ | 200+ | **340+** |
| **Dự án** | 3 | 3 | 8 | **14** |
| **Tiêu chuẩn C++** | C++17 | C++20 | C++17 | — |

---

## Triết lý giảng dạy

**1. Hiểu trước khi dùng.** Mỗi tính năng được giới thiệu kèm *tại sao* nó tồn tại và *vấn đề nào* nó giải quyết — không phải chỉ cú pháp.

**2. Sai chuẩn trước, tối ưu sau.** Mọi tuần đều nhấn mạnh: viết code *đúng* và *sạch* là ưu tiên số 1. Tốc độ và tối ưu là ưu tiên sau.

**3. Tài liệu gốc > tutorial thứ cấp.** Học viên được hướng dẫn đọc cppreference, PPP2, GoogleTest docs — không phụ thuộc vào "tutorial trên YouTube".

**4. Test là một phần của code, không phải thêm vào sau.** Từ K2 Tuần 9, mọi bài tập đều có file test. Không có test = chưa hoàn thành.

**5. Mỗi khóa là một giai đoạn độc lập nhưng có kết nối.** Bạn có thể học K3 (DSA) sau K1 mà không cần K2, và học K2 không phụ thuộc K3. Nhưng học cả ba mang lại tư duy hoàn chỉnh nhất.

---

## Mở rộng trong tương lai

Chương trình được thiết kế để có thể phát triển thành hệ sinh thái hoàn chỉnh:

```
Hiện tại (Phase 1):
  ① cpp-foundation   ② cpp-development   ③ dsa-cpp-course

Roadmap (Phase 2):
  ④ cpp-systems      ← Systems programming: OS, memory, networking
  ⑤ cpp-embedded     ← Embedded C++: bare-metal, RTOS
  ⑥ cpp-interview    ← Curated interview problems + solutions

Roadmap (Phase 3):
  📦 Unified starter template với CI/CD
  🤖 Auto-grading với GitHub Actions
  📊 Progress tracking dashboard
```

---

<div align="center">

### Bắt đầu ở đây

| Bạn là... | Bắt đầu từ |
|---|---|
| Hoàn toàn mới với lập trình | [cpp-foundation →](https://github.com/CocAgent/cpp-foundation) |
| Biết lập trình, mới với C++ | [cpp-foundation W01 →](https://github.com/CocAgent/cpp-foundation/tree/main/week-01) |
| Biết C++11/14, muốn Modern C++ | [cpp-development →](https://github.com/CocAgent/cpp-development) |
| Biết C++ cơ bản, muốn DSA | [dsa-cpp-course →](https://github.com/CocAgent/dsa-cpp-course) |
| Muốn cả Modern C++ lẫn DSA | K2 + K3 song song sau K1 T10 |

<br/>

*CocAgent C++ Learning Path · MIT License*
*Đóng góp, góp ý: mở Issue tại repo tương ứng*

</div>
