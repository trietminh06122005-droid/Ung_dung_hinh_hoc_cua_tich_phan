# Ứng dụng hình học của Tích phân

Tài liệu học tập về **Ứng dụng hình học của Tích phân**, được biên soạn và trình bày chuyên nghiệp bằng LaTeX/Typst.  
Mục tiêu của dự án là xây dựng một tài liệu có cấu trúc rõ ràng, trực quan, có các hình vẽ minh họa chi tiết và dễ dàng biên dịch thành tài liệu PDF chất lượng cao phục vụ cho học tập và giảng dạy.

---

## 📚 Nội dung chi tiết tài liệu

Tài liệu bao gồm các chủ đề chính sau:

### 1. Khái niệm và tính chất của tích phân
* Khái niệm tích phân
* Các tính chất của tích phân
* Các công thức nguyên hàm, tích phân cơ bản
* Các phương pháp tính tích phân

### 2. Ứng dụng tích phân để tính diện tích hình phẳng
* Hình phẳng giới hạn bởi một đồ thị hàm số, trục hoành và hai đường thẳng $x = a, x = b$
* Hình phẳng giới hạn bởi hai đồ thị hàm số và hai đường thẳng $x = a, x = b$

### 3. Ứng dụng tích phân để tính thể tích vật thể
* Tính thể tích của vật thể
* Tính thể tích khối tròn xoay

### 4. Ứng dụng tích phân để tính diện tích mặt tròn xoay
* Công thức tổng quát và các ví dụ áp dụng

### 5. Ứng dụng tích phân để tính độ dài đường cong phẳng
* Trường hợp đường cong $AB$ cho bởi phương trình $y = f(x)$
* Trường hợp đường cong $AB$ cho bởi phương trình tham số
* Trường hợp đường cong $AB$ cho bởi phương trình trong toạ độ cực

### 6. Bài tập và ứng dụng
* Bài tập cơ bản và nâng cao
* Bài toán thực tế

---
## 🎯 Mục tiêu dự án

* **Hệ thống hóa kiến thức:** Cung cấp đầy đủ định nghĩa, định lí và công thức cốt lõi về ứng dụng hình học của tích phân (diện tích hình phẳng, thể tích vật thể/khối tròn xoay, diện tích mặt tròn xoay và độ dài đường cong phẳng).
* **Minh họa trực quan:** Tích hợp các hình vẽ, đồ thị chi tiết và chính xác bằng TikZ/pgfplots theo chuẩn sách giáo khoa.
* **Lời giải chi tiết:** Xây dựng hệ thống ví dụ và bài tập từ cơ bản đến nâng cao kèm lời giải tường minh, dễ hiểu.
* **Chất lượng cao:** Biên soạn bằng LaTeX/Typst với bố cục khoa học, chuyên nghiệp, sẵn sàng biên dịch thành file PDF phục vụ học tập và giảng dạy.
---

## 🛠️ Công nghệ sử dụng
* **LaTeX / Typst**: Định dạng văn bản toán học, công thức và vẽ hình minh họa bằng TikZ/pgfplots.
* **GitHub**: Quản lý phiên bản mã nguồn tài liệu.

---
## 👥 Đối tượng độc giả

* **Học sinh THPT:** Đặc biệt là học sinh lớp 12 đang ôn luyện cho các kỳ thi (kiểm tra định kỳ, tốt nghiệp THPT) cần hệ thống lý thuyết và bài tập ứng dụng tích phân chuẩn xác.
* **Sinh viên đại học:** Sinh viên các khối ngành Kỹ thuật, Công nghệ, Toán - Tin đang theo học các học phần Giải tích hoặc Toán cao cấp.
* **Giáo viên và giảng viên Toán:** Giáo viên THPT và giảng viên đại học có thể sử dụng tài liệu làm nguồn tham khảo uy tín để biên soạn giáo án, bài giảng hoặc ngân hàng bài tập.
* **Người tự học yêu toán học:** Những ai muốn tìm hiểu sâu hơn về bản chất, ý nghĩa hình học và các bài toán thực tiễn liên quan đến tích phân.
---

## 🔤 Quy ước kí hiệu Tích phân và Giải tích

* **$\int f(x) \, \mathrm{d}x$**: Nguyên hàm của hàm số $f(x)$.
* **$\int_{a}^{b} f(x) \, \mathrm{d}x$**: Tích phân xác định của hàm số $f(x)$ trên đoạn $[a; b]$.
* **$\mathrm{d}x, \mathrm{d}y, \mathrm{d}t, \mathrm{d}\varphi$**: Vi phân của các biến tương ứng ($x, y, t, \varphi$).
* **$f'(x), y'(x)$**: Đạo hàm cấp một của hàm số theo biến $x$.
* **$f''(x), y''(x)$**: Đạo hàm cấp hai của hàm số.
* **$\frac{\mathrm{d}y}{\mathrm{d}x}$**: Đạo hàm của hàm ẩn hoặc hàm theo dạng tham số.
* **$C^1[a; b]$**: Không gian các hàm số liên tục và có đạo hàm liên tục trên đoạn $[a; b]$.
* **$\lim$**: Kí hiệu giới hạn (dùng trong định nghĩa tích phân suy rộng hoặc tổng Riemann).
 ---
 ## 📖 Tài liệu tham khảo

1. **Sách giáo khoa Toán 12** (Bộ sách *Kết nối tri thức với cuộc sống* / *Chân trời sáng tạo*), Nhà xuất bản Giáo dục Việt Nam.
2. **Bùi Xuân Diệu**, *Bài giảng Giải tích 1*.
4. **Tài liệu lưu hành nội bộ & các nguồn toán học trực tuyến** (Hỗ trợ phương pháp biên soạn mã nguồn LaTeX và vẽ hình TikZ/pgfplots).
