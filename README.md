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
```
---

## 🚀 Biên dịch

Biên dịch tài liệu chính:

```bash
typst compile main.typ
typst watch main.typ
```

##📝 Quy ước viết tài liệu

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

### Định nghĩa & Công thức

Các công thức quan trọng nên được trình bày rõ ràng, đi kèm hình vẽ minh họa.

> **Công thức.** Diện tích hình phẳng giới hạn bởi hai đường $y = f(x)$, $y = g(x)$ và hai đường thẳng $x = a$, $x = b$ là:
>
> $$S = \int_{a}^{b} |f(x) - g(x)| \, dx$$

### Định lý

Các kết quả quan trọng được trình bày rõ ràng và đi kèm chứng minh khi phù hợp.

> **Định lý (Phương pháp vỏ trụ).** Thể tích khối tròn xoay sinh ra khi quay hình phẳng giới hạn bởi $y = f(x)$, trục $Ox$, $x = a$, $x = b$ quanh trục $Oy$ được tính bởi:
>
> $$V = 2\pi \int_{a}^{b} x \cdot f(x) \, dx$$
### Ví dụ
Mỗi khái niệm quan trọng nên có ít nhất một ví dụ minh họa có lời giải chi tiết.

### Bài tập
Bài tập được phân loại theo mức độ:

Cơ bản

Trung bình

Nâng cao

Thử thách

## 🧮 Công thức toán học
Toán học trong tài liệu được viết bằng cú pháp của Typst.

Ví dụ:
$ S = integral_a^b |f(x) - g(x)| d x $
Công thức hiển thị độc lập:
$ V = pi integral_a^b [f(x)]^2 d x $

## 📐 Quy ước ký hiệu

| Ký hiệu | Ý nghĩa |
|---|---|
| $S$ | Diện tích hình phẳng / Diện tích mặt xoay |
| $V$ | Thể tích vật thể / Khối tròn xoay |
| $L$ | Độ dài cung đường cong |
| $a, b$ | Cận tích phân $[a, b]$ |
| $f(x), g(x)$ | Các hàm số giới hạn hình phẳng |
| $r, \theta$ | Tọa độ cực (bán kính và góc cực) |
| $Ox, Oy$ | Trục tọa độ vuông góc |
| $A_x, A_y$ | Diện tích thiết diện vuông góc với trục |

## 🎯 Mục tiêu của dự án
Dự án hướng tới việc xây dựng một tài liệu:

Dễ học và dễ tra cứu.

Trình bày toán học chính xác, minh họa trực quan.

Kết nối lý thuyết tích phân với ứng dụng thực tế và vật lý.

Có hệ thống bài tập từ cơ bản đến nâng cao.

Có cấu trúc Typst nhất quán.

Dễ mở rộng và bảo trì.

Có thể sử dụng làm tài liệu học tập hoặc giáo trình tham khảo.

## 🤝 Đóng góp
Nếu muốn đóng góp cho dự án:

Fork repository.

Tạo một branch mới.

Thực hiện thay đổi.

Kiểm tra tài liệu bằng Typst.

Tạo Pull Request.

Khi đóng góp, ưu tiên:

Công thức toán học chính xác.

Ký hiệu nhất quán.

Văn phong rõ ràng.

Ví dụ có lời giải thích chi tiết.

Không đưa nội dung trùng lặp.

Giữ cấu trúc chương thống nhất.

## 📖 Tài liệu tham khảo
Danh mục tài liệu tham khảo được quản lý trong:
bibliography/references.bib
Các nguồn tham khảo dự kiến bao gồm:

Giáo trình Giải tích 1 & Giải tích 2 (Đại học).

Tài liệu Toán học Giải tích phổ thông nâng cao.

Giáo trình Calculus (Stewart Calculus).

Tài liệu chính thức của Typst.
## 📄 Giấy phép
TODO: Chọn giấy phép phù hợp.

## 🌱 Trạng thái dự án
🚧 Dự án đang trong quá trình phát triển.

Nội dung, cấu trúc chương và hệ thống Typst có thể tiếp tục được thay đổi trong quá trình biên soạn.

## 👤 Tác giả
Trượng Ngụy Minh Triết

Học tích phân để hiểu sự biến thiên, áp dụng tích phân để đo lường thế giới.
