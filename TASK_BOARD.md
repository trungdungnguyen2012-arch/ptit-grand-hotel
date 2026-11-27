# Task Board — Phân Công & Tiến Độ Thực Hiện Đồ Án

Dự án được chia thành **3 phạm vi tệp độc lập** tương ứng với 3 thành viên để dễ dàng làm việc và cập nhật trực tiếp trên giao diện web GitHub mà không xảy ra xung đột mã nguồn (merge conflict).

## 1. Quy ước sở hữu tệp (File Ownership)

- **TV01 — Nguyễn Trung Dũng (`K24DTCN412`):** Phụ trách `index.html`, `README.md`, `TASK_BOARD.md` và kiểm tra tích hợp chung.
- **TV02 — Đỗ Hoàng Duy (`K24DTCN486`):** Phụ trách `style.css` (màu sắc chủ đạo, thẻ phòng, bảng dữ liệu, chân trang và giao diện in).
- **TV03 — Nguyễn Cao Thắng (`K24DTCN406`):** Phụ trách `script.js` (render danh sách phòng, giỏ chờ chốt, validation, lọc đơn và `localStorage`).

> **Quy tắc phối hợp:** Khi cần đổi tên `id` hoặc `class` liên kết giữa HTML, CSS và JS, các thành viên thông báo cho **TV01** để thống nhất trước khi chỉnh sửa.

## 2. Bảng theo dõi công việc chi tiết

| Mã việc | Hạng mục công việc | Phụ trách | Tệp liên quan | Trạng thái / Tiêu chí nghiệm thu |
| --- | --- | --- | --- | --- |
| **W-00** | Khởi tạo repository GitHub, thống nhất cấu trúc `id`/`class` giữa 3 tệp | TV01 + Cả nhóm | Toàn bộ repo | **DONE** — Cấu trúc thư mục rõ ràng, phân quyền Collaborators cho đủ 3 thành viên |
| **W-01** | Xây dựng khung HTML5: Navbar, Hero Banner, bộ lọc, khu vực chốt đơn, bảng lịch sử và Footer | TV01 | `index.html` | **DONE** — Đầy đủ semantic tags, gắn đúng `id` cho các ô nhập liệu và bảng dữ liệu |
| **W-02** | Thiết kế giao diện tông màu Booking.com, sửa lỗi che tiêu đề bằng Sticky Navbar | TV02 | `style.css` | **DONE** — Màu sắc hài hòa (`#003580`, `#febb02`), chữ hiển thị rõ ràng, không tràn khung |
| **W-03** | Định dạng lưới thẻ phòng (CSS Grid), bảng dữ liệu và chế độ in báo cáo `@media print` | TV02 | `style.css` | **DONE** — Thẻ phòng đều đẹp, khi nhấn In tự động ẩn thanh điều hướng và các nút thừa |
| **W-04** | Xây dựng dữ liệu hạng phòng, lời chào thông minh (`Date`, `if...else`, `switch...case`) và bộ lọc phòng | TV03 | `script.js` | **DONE** — Hiển thị đủ 4 hạng phòng, tìm kiếm theo tên và sắp xếp giá chính xác |
| **W-05** | Lập trình giỏ chờ chốt đơn, đồng bộ ngày nhận/trả phòng và kiểm tra số điện thoại (`isNaN`) | TV03 | `script.js` | **DONE** — Tự động tính số đêm, chặn ngày trả trước ngày nhận và chặn SĐT sai định dạng |
| **W-06** | Quản lý đơn đã đặt với `localStorage`, lọc theo tên/ngày, tính tổng doanh thu và hủy đơn | TV03 | `script.js` | **DONE** — Dữ liệu giữ nguyên sau khi F5, lọc đúng điều kiện, hộp thoại `confirm` hoạt động tốt |
| **W-07** | Kiểm thử tích hợp toàn bộ luồng đặt phòng và rà soát tài liệu mô tả | TV01 chủ trì, cả nhóm hỗ trợ | `README.md`, `TASK_BOARD.md` | **DONE** — Đạt 6/6 hạng mục trong bảng xác minh |
| **W-08** | Triển khai bản chạy thử công khai qua GitHub Pages và đóng gói nộp bài | TV01 | Cài đặt GitHub | **READY** — Cập nhật link demo vào `README.md` trước khi nộp |
