# DỰ ÁN WEBSITE HỌC TIẾNG TRUNG CƠ BẢN (HOA NGỮ TINH HOA)
> **Bài Thi Kiểm Tra Kỹ Năng Thiết Kế Web Frontend (HTML5 & CSS3 Thuần)**

---

## 1. THÔNG TIN SINH VIÊN & ĐỀ TÀI
- **Họ và tên:** Phan Thanh Sơn
- **Mã số sinh viên (MSSV):** 125000277
- **Tên đề tài:** Website Học Tiếng Trung Cơ Bản & Flashcard 3D (Chinese Learning Landing Page)
- **Công nghệ chính:** Semantic HTML5, CSS3 Variables, CSS Grid, CSS Flexbox, Animate.css, CSS 3D Transforms (100% Thuần - Không dùng JavaScript/Java).

---

## 2. CẤU TRÚC REPOSITORY (REPOSITORY STRUCTURE)
Repository được tổ chức khoa học, phân chia rõ ràng theo đúng yêu cầu đề thi:

```text
Son_PhanThanh_125000277/
│
├── index.html                  # File mã nguồn HTML5 chính chuẩn Semantic ngữ nghĩa
├── style.css                   # File định kiểu CSS3 chính (CSS Variables, Flexbox/Grid, Animations)
├── PROMPT_LOG.md               # Nhật ký Prompt AI & các lần tinh chỉnh (Iteration Debug)
├── README.md                   # Tài liệu hướng dẫn cấu trúc dự án & kiểm thử
│
└── assets/                     # Thư mục tài nguyên đa phương tiện của website
    └── images/                 # Thư mục chứa hình ảnh, vector và biểu tượng đồ họa
        ├── favicon.svg         # Biểu tượng Favicon con dấu triện son Á Đông chữ 华
        ├── logo.svg            # Logo vector thương hiệu "Hoa Ngữ Tinh Hoa"
        ├── course-hsk1.svg     # Ảnh minh họa khóa học Tiếng Trung Sơ Cấp HSK 1 - 2
        ├── course-hsk2.svg     # Ảnh minh họa khóa học Tiếng Trung Trung Cấp HSK 3 - 4
        └── course-business.svg # Ảnh minh họa khóa học Tiếng Trung Thương Mại & Du Lịch
```

---

## 3. CÁC TIÊU CHUẨN KỸ THUẬT NỔI BẬT ĐÃ ĐẠT ĐƯỢC

### 1. Chuẩn Semantic HTML5
- Sử dụng đúng ngữ nghĩa các thẻ chuẩn: `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<figure>`, `<aside>`, `<footer>`.
- Hạn chế tối đa việc lạm dụng thẻ `<div>` vô nghĩa.
- Đầy đủ thuộc tính trợ năng Accessibility (`aria-label`, `aria-labelledby`, `role`, `alt`).

### 2. Hệ Thống CSS Variables & Layout Hiện Đại
- Khai báo rõ ràng block `:root` với bảng màu chuẩn Á Đông hiện đại:
  - `--primary-color: #c8102e` (Đỏ son truyền thống)
  - `--secondary-color: #d4af37` (Vàng kim hoàng gia)
  - `--text-color: #1f2937`, `--bg-color: #fbf9f5`
  - `--font-main: 'Plus Jakarta Sans'`, `--font-chinese: 'Noto Serif SC'`
  - `--spacing: 1.5rem` cùng các thang tỷ lệ bo góc, bóng đổ.
- Ứng dụng **CSS Grid & Flexbox** đảm bảo hiển thị cân đối, responsive 100% trên mọi kích thước màn hình (Mobile, Tablet, Desktop).

### 3. Tương Tác 100% Bằng CSS3 Thuần (Không JS/Java)
- **Bộ thẻ Flashcard 3D lật 2 mặt:** Ứng dụng `perspective: 1200px` và `transform-style: preserve-3d`. Lật thẻ khi rê chuột (`:hover`) hoặc click bằng kỹ thuật Checkbox Hack.
- **Bộ lọc từ vựng (Tabs Filter):** Ứng dụng CSS Radio Hack lọc theo 4 chủ đề (*Chào Hỏi*, *Đời Sống*, *Học Tập*, *Ẩm Thực*).
- **Menu di động (Mobile Navigation):** Ứng dụng Checkbox Hack đóng/mở menu trên điện thoại hoàn toàn bằng CSS.
- **Cụm nút tiện ích nổi (Floating Contact Bar):** Nút Gọi Hotline, Chat Zalo, Nhắn tin, Lên đầu trang màu đỏ rực rỡ kèm animation sóng lan tỏa (`@keyframes pulseRipple`) và rung chuông (`@keyframes phoneRingShake`).

### 4. Hiệu Ứng Thẩm Mỹ Cao
- Tích hợp CDN **Animate.css** cho tiêu đề và nút CTA.
- Hiệu ứng Gradient Shimmer lấp lánh ánh kim cho chữ *Tiếng Trung* tại Hero Section.
- Hiệu ứng thẻ bay bồng bềnh lơ lửng 3D (`@keyframes cardFloat3D`).

---

## 4. HƯỚNG DẪN KIỂM THỬ SẢN PHẨM
1. Tải hoặc giải nén thư mục `Son_PhanThanh_125000277`.
2. Mở file `index.html` trực tiếp bằng trình duyệt web bất kỳ (Google Chrome, Microsoft Edge, Mozilla Firefox,...).
3. Trải nghiệm các hiệu ứng:
   - Rê chuột qua các thẻ card và nút bấm để xem hiệu ứng `:hover`, `:focus`.
   - Bấm vào các nút danh mục từ vựng để xem tính năng lọc thẻ CSS.
   - Di chuột hoặc chạm vào bộ thẻ Flashcard để lật xem giải nghĩa chữ Hán 3D.
   - Thử nghiệm cụm nút tiện ích nổi ở góc dưới bên phải màn hình.
