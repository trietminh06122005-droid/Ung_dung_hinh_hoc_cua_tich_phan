# Ứng dụng hình học của Tích phân

Tài liệu học tập về **Ứng dụng hình học của Tích phân**, được biên soạn bằng [Typst](https://typst.app/).

Mục tiêu của dự án là xây dựng một tài liệu có cấu trúc rõ ràng, dễ đọc, dễ biên tập và có thể biên dịch thành PDF chất lượng cao.

---

## 📚 Nội dung

Tài liệu dự kiến bao gồm các chủ đề chính:

1. **Diện tích hình phẳng**
   - Diện tích hình phẳng giới hạn bởi đường cong và trục hoành
   - Diện tích hình phẳng giới hạn bởi hai hay nhiều đường cong
   - Diện tích hình phẳng trong tọa độ cực
   - Các bài toán ứng dụng thực tế

2. **Thể tích khối tròn xoay**
   - Thể tích vật thể biết diện tích thiết diện
   - Thể tích khối tròn xoay quay quanh trục $Ox$ (Phương pháp đĩa/vòng xuyến)
   - Thể tích khối tròn xoay quay quanh trục $Oy$ (Phương pháp vỏ trụ)
   - Thể tích khối tròn xoay quanh trục bất kỳ

3. **Độ dài cung tròn**
   - Độ dài cung đường cong cho bởi hàm số $y = f(x)$ hoặc $x = g(y)$
   - Độ dài cung đường cong cho bởi phương trình tham số
   - Độ dài cung đường cong trong tọa độ cực

4. **Diện tích mặt tròn xoay**
   - Diện tích mặt tròn xoay quanh trục $Ox$
   - Diện tích mặt tròn xoay quanh trục $Oy$
   - Ứng dụng trong việc tính diện tích các hình học không gian đặc biệt

5. **Ứng dụng thực tế và bài toán vật lý**
   - Tính công thực hiện trong vật lý
   - Lực tác dụng của chất lưu (áp suất nước lên đập)
   - Khối lượng và trọng tâm của thanh/mảnh phẳng (Moment vô hướng)

6. **Bài tập và ứng dụng**
   - Bài tập cơ bản
   - Bài tập nâng cao
   - Bài toán thực tế
   - Bài tập tổng hợp

---

## 🗂️ Cấu trúc dự án

```text
.
├── README.md
├── main.typ
├── typst.toml
├── chapters/
│   ├── 01-dien-tich-hinh-phang.typ
│   ├── 02-the-tich-khoi-tron-xoay.typ
│   ├── 03-do-dai-cung-tron.typ
│   └── 04-dien-tich-mat-xoay.typ
├── exercises/
├── figures/
├── bibliography/
│   └── references.bib
├── templates/
└── assets/
```
---

## ✍️ Công nghệ

Dự án sử dụng:

- **Typst** — hệ thống typesetting chính.
- **Markdown** — tài liệu hướng dẫn và README.
- **BibTeX** — quản lý tài liệu tham khảo.
- **Git** — quản lý phiên bản.

### Cài đặt Typst

Có thể cài đặt Typst từ trang chính thức:

https://typst.app/

Sau khi cài đặt, kiểm tra:

```bash
typst --version
---

## 🚀 Biên dịch

Biên dịch tài liệu chính:

```bash
typst compile main.typ
typst watch main.typ
##📝 Quy ước viết tài liệu
Mỗi chương nên có cấu trúc thống nhất:
Chương
├── Mục tiêu học tập
├── Kiến thức nền
├── Định nghĩa & Công thức
├── Định lý
├── Chứng minh
├── Ví dụ minh họa
├── Nhận xét & Mẹo tính
├── Bài tập
└── Tóm tắt
