# 🍽️ Hệ thống Quản lý Đặt bàn và Gọi món Mai Hoa Dining

## 📌 Tổng quan dự án

Đây là dự án phân tích và thiết kế hệ thống quản lý đặt bàn và gọi món cho nhà hàng **Mai Hoa Dining** theo phương pháp **phân tích hướng chức năng**.

Hệ thống được xây dựng nhằm hỗ trợ nhân viên trong việc quản lý đặt bàn, phục vụ món ăn và thanh toán, đồng thời giúp nhà quản lý theo dõi hoạt động kinh doanh thông qua các báo cáo thống kê.

Dự án tập trung vào việc phân tích nghiệp vụ, mô hình hóa hệ thống và thiết kế giao diện người dùng, **không bao gồm việc phát triển phần mềm hoàn chỉnh**.

---

# 🎯 Bài toán

Trong quá trình vận hành, nhà hàng thường gặp các vấn đề:

- Quản lý đặt bàn thủ công dễ xảy ra trùng lịch.
- Khó theo dõi trạng thái bàn theo thời gian thực.
- Quá trình gọi món và chuyển món giữa bếp – phục vụ còn thủ công.
- Việc thanh toán mất nhiều thời gian.
- Khó thống kê doanh thu và hiệu quả hoạt động.

Do đó cần xây dựng một hệ thống giúp số hóa toàn bộ quy trình nghiệp vụ.

---

# 🎯 Mục tiêu

- Quản lý thông tin bàn ăn.
- Tiếp nhận và quản lý đặt bàn.
- Hỗ trợ nhân viên ghi nhận gọi món.
- Quản lý trạng thái phục vụ.
- Thanh toán hóa đơn.
- Thống kê doanh thu và hoạt động kinh doanh.

---

# ⚙️ Chức năng chính

## 1. Quản lý danh mục

- Bàn ăn
- Khu vực
- Thực đơn
- Loại món ăn
- Nhân viên
- Khách hàng

---

## 2. Quản lý đặt bàn

- Tiếp nhận đặt bàn
- Kiểm tra bàn trống
- Chỉnh sửa đặt bàn
- Hủy đặt bàn
- Nhận khách (Check-in)

---

## 3. Quản lý gọi món

- Lập phiếu gọi món
- Thêm món
- Hủy món
- Cập nhật trạng thái phục vụ
- Chuyển món đến bếp

---

## 4. Thanh toán

- Tính tiền
- In hóa đơn
- Hoàn tất thanh toán

---

## 5. Báo cáo thống kê

- Doanh thu
- Món ăn bán chạy
- Tình trạng bàn
- Hiệu suất phục vụ

---

# 📂 Nội dung dự án

Dự án bao gồm:

- Phân tích nghiệp vụ
- Đặc tả chức năng
- Sơ đồ phân rã chức năng (BFD)
- Sơ đồ luồng dữ liệu (DFD)
- Thiết kế giao diện người dùng (UI/UX)
- Prototype trên Figma

---

# 🛠 Công cụ sử dụng

- Draw.io
- Figma
- Microsoft Word

---

# 📁 Cấu trúc dự án

```text
mai-hoa-dining-system/
│
├── README.md
├── LICENSE
│
├── screenshots/
│   ├── diagrams/
│   │   ├── BFD.png
│   │   ├── CD.png
│   │   ├── DFD_level_0.png
│   │   ├── DFD_level1_QlyBanVaThucDon.png
│   │   ├── DFD_leve1_DatBan.png
│   |   ├── DFD_leve1_GoiMon.png
│   │   └── DFD_leve1_ThanhToan.png
│   │
│   └── ui-ux/
│       ├── Dashboard_TongQuan.png
│       ├── DatBan.png
│       ├── GoiMon.png
│       ├── CheBienPhucVu.png
│       └── ThanhToan.png
│
├── prototype/
│   └── figma-link.md
│
└── docs/
    └── Final_Report.pdf
```


---

# 🎨 Prototype

Prototype được thiết kế bằng **Figma**.

> Thêm liên kết Figma tại đây.

---

# 📚 Kiến thức áp dụng

- Phân tích hệ thống thông tin
- Phân tích hướng chức năng
- Business Process Analysis
- Business Function Diagram (BFD)
- Data Flow Diagram (DFD)
- Data Dictionary
- Thiết kế giao diện UI/UX
- Prototype bằng Figma

---

# 👤 Tác giả

**Quách Hải Oanh**
