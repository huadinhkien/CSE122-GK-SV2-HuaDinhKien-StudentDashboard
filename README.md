# StudyPath AI — Student Dashboard

Bài kiểm tra giữa kỳ — Học phần: Phát triển ứng dụng Web cơ bản (CSE122)
Sinh viên thực hiện: **Hứa Đình Kiên — MSV 2551060707 (SV2)**
Đề tài BTL nhóm: StudyPath AI (SV1 Hồ Trung Anh — Khách, SV3 Nguyễn Bá Hoàng Tuân — Cố vấn + Quản trị viên)

## Tên đề tài

StudyPath AI — Hệ thống tư vấn & lập kế hoạch học tập cho sinh viên CNTT

## Tên trang đã thực hiện

**Student Dashboard** (`index.html`) — màn hình tổng quan tiến độ học tập của vai trò Sinh viên

## Mục đích của trang

Giúp sinh viên theo dõi tổng quan tiến độ học tập (tín chỉ tích lũy, GPA, số kế hoạch, cảnh báo quá tải học kỳ), xem tiến độ tín chỉ qua các học kỳ, quản lý việc cần làm và theo dõi thông báo từ cố vấn/hệ thống.

## Các chức năng chính

- 4 thẻ chỉ số tổng quan (tín chỉ tích lũy, GPA, kế hoạch, cảnh báo) — render từ mảng JavaScript
- Biểu đồ cột "Tiến độ tín chỉ theo học kỳ" (4 học kỳ gần nhất, HK hiện tại tô màu cam)
- Thẻ "Kế hoạch hiện tại" với trạng thái Bản nháp + cảnh báo vượt ngưỡng 18 tín chỉ
- **Việc cần làm**: tick hoàn thành / mở lại, số việc còn lại cập nhật trực tiếp
- **Thông báo mới**: bấm vào từng dòng để đánh dấu đã đọc (chấm xanh biến mất), "Xem tất cả" đánh dấu hết; badge đỏ trên sidebar đồng bộ theo số thông báo chưa đọc
- Chuyển trạng thái demo (Bình thường / Đang tải / Rỗng / Lỗi) để trình bày các trạng thái giao diện

## Công nghệ sử dụng

- HTML5 (semantic HTML: `header`, `nav`, `main`, `section`)
- CSS3 (Flexbox, Grid, Media Query / Responsive, hiệu ứng hover, skeleton loading)
- JavaScript thuần (DOM, Events, event delegation, render từ mảng dữ liệu — không dùng framework)

## Link Figma

https://www.figma.com/design/UlVlylPnLVm19UE9ICufOq/Dashboard?node-id=0-1

## Link video

_(điền sau)_

## Link GitHub

https://github.com/huadinhkien/CSE122-GK-SV2-HuaDinhKien-StudentDashboard
