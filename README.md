# PBT06 - CSS Frameworks (Bootstrap 5)

## Thông tin sinh viên

- **Họ và tên:** Đỗ Việt Hoàng
- **MSSV:** 2451170896
- **Môn học:** CSE391 - Thiết kế Web
- **Track thực hiện:** Bootstrap 5

---

## Giới thiệu

Bài tập thực hành PBT06 về **CSS Frameworks** sử dụng **Bootstrap 5**.

Dự án gồm:

- Trả lời câu hỏi lý thuyết (Phần A, C)
- Landing Page E-Commerce bằng Bootstrap
- Admin Dashboard bằng Bootstrap
- Video thực hành OBS

---

## Cấu trúc thư mục

```text
CSE391_DoVietHoang_2451170896_PBT06/
│
├── answers.md
├── bootstrap_landing.html
├── bootstrap_dashboard.html
├── screenshots/
│   ├── mobile.png
│   ├── tablet.png
│   └── desktop.png
│
├── videos/
│   └── PBT06_DoVietHoang_2451170896.mp4
│
└── README.md
```

---

## Nội dung bài làm

### 1. answers.md

Bao gồm:

- Phần A – Đọc hiểu Bootstrap
- Phần C – Phân tích và so sánh Bootstrap với CSS thuần

---

### 2. bootstrap_landing.html

Landing Page bán hàng sử dụng Bootstrap 5.

#### Chức năng

- Responsive Navbar
- Product Grid
- Product Card
- Sale Badge
- Modal xem nhanh sản phẩm
- Footer 4 cột
- Responsive trên Mobile / Tablet / Desktop

#### Bootstrap Components sử dụng

- Navbar
- Grid System
- Card
- Badge
- Modal
- Buttons
- Utilities

---

### 3. bootstrap_dashboard.html

Trang quản trị Dashboard.

#### Chức năng

- Sidebar cố định
- Topbar + Dropdown
- Statistic Cards
- Search & Filter
- Orders Table
- Accordion FAQ
- Alert thông báo

#### Bootstrap Components sử dụng

- List Group
- Dropdown
- Card
- Table
- Input Group
- Accordion
- Alert

---

## Công nghệ sử dụng

- HTML5
- Bootstrap 5.3
- Bootstrap Icons

CDN:

```html
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">

<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.10.0/font/bootstrap-icons.css">
```

---

## Hướng dẫn chạy

### Cách 1

Mở trực tiếp:

```text
bootstrap_landing.html
```

hoặc

```text
bootstrap_dashboard.html
```

bằng trình duyệt.

### Cách 2

Sử dụng VS Code + Live Server:

1. Mở project bằng VS Code.
2. Chuột phải vào file HTML.
3. Chọn **Open with Live Server**.

---

## Responsive Testing

Đã kiểm tra trên:

| Thiết bị | Kích thước |
| -------- | ---------- |
| Mobile | < 768px |
| Tablet | 768px - 991px |
| Desktop | ≥ 992px |

Ảnh chụp màn hình được lưu trong thư mục:

```text
screenshots/
```

---

## Video OBS

Video thực hành bao gồm:

- Tạo Bootstrap Product Card
- Thêm Sale Badge
- Tạo Modal
- Giải thích Bootstrap Classes
- Demo Responsive Layout

Video được đính kèm trong thư mục:

```text
videos/
```

hoặc link video được ghi trong file:

```text
answers.md
```

---

## Kết luận

### Ưu điểm của Bootstrap

- Phát triển giao diện nhanh
- Có sẵn Grid System responsive
- Nhiều component tích hợp sẵn
- Giảm lượng CSS phải tự viết
- Dễ bảo trì và mở rộng

### Nhược điểm của Bootstrap

- Khả năng tùy biến thấp hơn CSS thuần
- File CSS lớn hơn khi chỉ dùng ít thành phần
- Giao diện dễ bị giống các website Bootstrap khác nếu không tùy chỉnh

---

## Yêu cầu đã hoàn thành

- [x] Phần A – Đọc hiểu
- [x] Phần C – Phân tích
- [x] Landing Page Bootstrap
- [x] Dashboard Bootstrap
- [x] Responsive Layout
- [x] Video OBS
- [x] GitHub Repository
