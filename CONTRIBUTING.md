# 🤝 CONTRIBUTING — Hướng Dẫn Đóng Góp

Cảm ơn bạn muốn đóng góp! Repo này là hub tổng thể — đóng góp nội dung bài tập nên được thực hiện tại repo tương ứng (xem danh sách bên dưới).

---

## Các loại đóng góp được hoan nghênh

| Loại | Nơi đóng góp | Ví dụ |
|---|---|---|
| Bài tập mới | Repo khóa học tương ứng | Thêm bài tập tuần 5 |
| Sửa lỗi code | Repo khóa học tương ứng | Fix bug trong solution |
| Cải thiện giải thích | Repo khóa học tương ứng | Thêm comment giải thích |
| Đề xuất khóa học mới | Repo này (Issue) | Đề xuất `web-python-course` |
| Sửa lỗi chính tả/link | Repo này hoặc repo con | Fix broken link |
| Cải thiện roadmap | Repo này (PR) | Cập nhật ROADMAP.md |

---

## Quy trình đóng góp

### 1. Báo lỗi (Bug Report)
```
Repo này       → Mở Issue với template "Bug Report"
Repo khóa học  → Mở Issue tại repo đó
```

### 2. Đề xuất nội dung mới (Feature Request)
```
1. Mở Issue tại repo này với template "Feature Request"
2. Mô tả: nội dung đề xuất, lý do, tuần nào phù hợp
3. Chờ feedback trước khi tạo PR
```

### 3. Gửi Pull Request
```bash
# Fork repo tương ứng
git clone https://github.com/YOUR_USERNAME/REPO_NAME.git
cd REPO_NAME
git checkout -b feat/week-05-extra-exercise

# Làm thay đổi
# ...

git add .
git commit -m "feat(week-05): thêm bài tập ⭐⭐ về list comprehension"
git push origin feat/week-05-extra-exercise
# Tạo PR trên GitHub
```

---

## Tiêu chuẩn chất lượng

### Python code
```python
# ✅ Phải pass
# - PEP 8 (chạy flake8 hoặc ruff)
# - Type hints đầy đủ (từ python-mastery trở đi)
# - Docstring cho mọi hàm/class
# - pytest pass nếu có test

def calculate_average(scores: list[float]) -> float:
    """Tính điểm trung bình. Trả 0.0 nếu list rỗng."""
    if not scores:
        return 0.0
    return sum(scores) / len(scores)
```

### C++ code
```cpp
// ✅ Phải pass
// - g++ -std=c++20 -Wall -Wextra -Wpedantic (không warning)
// - Không raw new/delete
// - GTest pass nếu có test

[[nodiscard]] double calculateAverage(const std::vector<double>& scores) {
    if (scores.empty()) return 0.0;
    return std::accumulate(scores.begin(), scores.end(), 0.0) / scores.size();
}
```

### Commit message format
```
feat(week-05): thêm bài tập palindrome ⭐⭐⭐
fix(week-03): sửa lỗi solution ex02 khi input rỗng
docs(week-07): cập nhật link cppreference
refactor(week-10): cải thiện readability của lecture code
```

---

## Liên kết đến các repo

**Python:** [python-journey](https://github.com/CocAgent/python-journey) · [python-mastery](https://github.com/CocAgent/python-mastery) · [dsa-python-course](https://github.com/CocAgent/dsa-python-course) · [data-python-course](https://github.com/CocAgent/data-python-course) · [automation-python-course](https://github.com/CocAgent/automation-python-course)

**C++:** [cpp-foundation](https://github.com/CocAgent/cpp-foundation) · [cpp-development](https://github.com/CocAgent/cpp-development) · [dsa-cpp-course](https://github.com/CocAgent/dsa-cpp-course)

---

*Mọi đóng góp đều tuân theo [MIT License](LICENSE).*
