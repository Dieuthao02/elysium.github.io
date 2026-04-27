# 🌌 ELYSIUM - Integrated Event Management Platform

**Elysium** là nền tảng quản lý và kết nối sự kiện hiện đại, giúp người dùng tìm kiếm, đăng ký và theo dõi các hoạt động văn hóa, học thuật, giải trí một cách trực quan và chuyên nghiệp.

🔗 **Live Demo:** [Trải nghiệm tại đây](https://dieuthao02.github.io/elysium.github.io/)

---

## 👥 1. Đội ngũ thực hiện

| STT | Họ và Tên | Vai trò | Nhiệm vụ chính |
| :--- | :--- | :--- | :--- |
| 1 | **Nhữ Thị Diệu Thảo** | Project Manager & Core Developer | Chủ trì thiết kế kiến trúc; Phát triển module hạt nhân (Admin, Lịch, Booking); Thiết lập Firebase; Code Review; Viết README. |
| 2 | **Nguyễn Phan Trà My** | Frontend Developer | Phát triển module danh mục và chi tiết sự kiện (Events); Phối hợp xây dựng tài liệu kỹ thuật. |
| 3 | **Phạm Minh Anh** | Member | Thiết kế và xây dựng giao diện các trang bổ trợ (About Us, Contact). |
| 4 | **Đỗ Tiến Thịnh** | Frontend Developer | Hỗ trợ phát triển hiển thị sự kiện (Detail) và tối ưu hóa trải nghiệm trang danh sách. |
| 5 | **Đỗ Việt Công** | Frontend Developer | Xây dựng giao diện trang chủ (Index) và khung hình bảng điều khiển người dùng (Dashboard). |
| 6 | **Trần Đình Minh Đạt** | Logic Developer | Phụ trách hệ thống xác thực người dùng (Auth) và chuẩn hóa Footer toàn trang. |

**Phương thức làm việc:** Nhóm áp dụng quy trình phân chia nhiệm vụ rõ ràng, quản lý phiên bản bằng **GitHub**, phát triển theo từng module và kiểm thử định kỳ (Testing).

---

## 🚀 2. Công nghệ sử dụng

### **Frontend & Logic**
* **HTML5 & CSS3:** Sử dụng Semantic Tags, Flexbox, Grid và Responsive Design.
* **Tailwind CSS:** Framework tối ưu hóa giao diện.
* **JavaScript (Vanilla):** DOM Manipulation, Form Validation, Local Storage.

### **Quản lý dữ liệu**
* **Firebase:** Xác thực người dùng (Authentication) và cấu hình hệ thống.
* **Local Storage:** Lưu trữ tạm thời giỏ hàng, thông tin booking và tùy chỉnh cá nhân để tăng tốc độ phản hồi.

### **Công cụ hỗ trợ**
* **Design:** Figma (Wireframe & UI Design).
* **Dev:** VS Code, Git/GitHub.

---

## 🎨 3. Ngôn ngữ thiết kế
* **Chủ đề:** Modern Luxury / Minimalist.
* **Màu sắc:** Pastel Pink & Cyan chủ đạo.
* **UI Components:** Card sự kiện bo góc, đổ bóng (soft shadows) tạo chiều sâu.

---

## ✨ 4. Tính năng cốt lõi (Cấp độ 3)
* 📅 **Lịch tương tác:** Theo dõi sự kiện theo ngày tháng trực quan.
* 🔍 **Tìm kiếm & Lọc:** Bộ lọc nâng cao theo danh mục, thời gian và từ khóa.
* 🎟️ **Hệ thống Đặt vé:** Quy trình mượt mà với kiểm tra dữ liệu thời gian thực.
* 📊 **Trang Quản trị (Admin):** Quản lý người dùng, sự kiện và thống kê hệ thống.
* 📱 **Responsive:** Hiển thị hoàn hảo trên Mobile, Tablet và Desktop.

---

## 📂 5. Cấu trúc thư mục
```text
Elysium_Group_Project/
├── index.html          # Trang chủ
├── about.html          # Giới thiệu
├── events.html         # Danh sách sự kiện
├── detail.html         # Chi tiết sự kiện
├── booking.html        # Đặt vé
├── auth.html           # Đăng nhập/Đăng ký
├── admin.html          # Quản trị viên
├── css/                # Stylesheets (index.css, responsive.css,...)
├── js/                 # JavaScript Logic (index.js, firebase-config.js,...)
├── img/                # Tài nguyên hình ảnh
├── video/              # Tài nguyên video
└── README.md           # Tài liệu dự án
## 🛠️ 5. Hướng dẫn Cài đặt & Khởi chạy

Để chạy dự án này trên máy tính cá nhân, bạn có thể thực hiện theo các bước sau:

### 5.1. Yêu cầu hệ thống
Trước khi bắt đầu, hãy đảm bảo bạn đã cài đặt các công cụ sau:
* **Trình duyệt web:** Chrome, Edge, Firefox hoặc Safari (phiên bản mới nhất).
* **Trình soạn thảo mã nguồn:** [Visual Studio Code (VS Code)](https://code.visualstudio.com/) (Khuyên dùng).
* **Git:** [Tải Git tại đây](https://git-scm.com/) (Nếu bạn muốn clone dự án từ GitHub).

### 5.2. Các bước cài đặt

**Bước 1: Tải mã nguồn về máy**
* **Cách 1 (Dùng Git):** Mở terminal (hoặc Command Prompt) và chạy lệnh:
  ```bash
  git clone [https://github.com/dieuthao02/elysium.github.io.git](https://github.com/dieuthao02/elysium.github.io.git)
