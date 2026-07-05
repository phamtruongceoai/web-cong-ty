---
paths:
  - "*.html"
  - "css/**/*.css"
---

# Design style (tham chiếu: `antigravity.google_auth-success_app=antigravity-ide.png`)

Ảnh mẫu là trang "auth success" của Google Antigravity — lấy làm chuẩn phong cách thị giác:

- **Tối giản, nhiều khoảng trắng**: nền trắng/gần trắng, nội dung căn giữa theo chiều ngang,
  không nhồi nhét thông tin. Một ý chính rõ ràng trên màn hình đầu (hero).
- **Bố cục điển hình**:
  - Header mỏng: logo + wordmark ở góc trái, icon menu (hamburger) ở góc phải, nền trong suốt/trắng.
  - Khối trung tâm: icon/logo nhỏ + heading lớn (font weight vừa phải, không quá đậm),
    một dòng mô tả phụ nhỏ, nhẹ, màu xám bên dưới, có thể chứa 1 link inline.
  - Footer/nav phụ: vài link nhỏ, căn giữa, cách nhau bằng dấu `|` hoặc khoảng trắng lớn,
    màu xám nhạt, cỡ chữ nhỏ.
  - Góc dưới-phải: cụm nút tròn nổi (floating action buttons) xếp chồng dọc — ví dụ chat/feedback/help.
- **Điểm nhấn trang trí tinh tế**: các chấm màu nhỏ (đỏ, vàng, xanh dương, xanh lá — không bắt buộc
  đúng màu Google, có thể đổi theo bộ nhận diện công ty) rải rác thưa thớt trên nền, tạo cảm giác
  sống động nhưng không gây rối mắt. Dùng làm chi tiết trang trí ở hero, không lạm dụng.
- **Typography**: sans-serif hiện đại, sạch (ví dụ Inter, hoặc font hệ thống
  `-apple-system, "Segoe UI", Roboto, sans-serif`). Heading lớn dùng font-weight 500–600,
  không dùng weight quá đậm (800–900) để giữ cảm giác nhẹ nhàng, chuyên nghiệp.
- **Màu sắc**: nền trắng là chủ đạo, text chính màu đen/xám đậm (`#1a1a1a` – `#333`),
  text phụ màu xám nhạt (`#6b7280` – `#9ca3af`). Màu accent (nút CTA, link, chấm trang trí)
  dùng màu thương hiệu công ty — cần xác định bộ màu brand trước khi code phần chi tiết.
- **Cảm giác tổng thể**: chuyên nghiệp, đáng tin cậy, "công nghệ nhưng ấm áp" — không lạnh lùng
  kiểu enterprise cứng nhắc, không sặc sỡ kiểu startup rẻ tiền.

Khi cần link liên quan tới thiết kế artifact/preview, dùng skill `artifact-design` hoặc
`design-taste-frontend` nếu người dùng yêu cầu build giao diện chất lượng cao, tránh giao diện "AI slop".
