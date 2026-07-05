# Quy tắc bắt buộc

- **Sau mỗi thay đổi lớn về giao diện**: chụp screenshot trang đã render và so sánh trực tiếp
  với ảnh design gốc (`antigravity.google_auth-success_app=antigravity-ide.png`) để đối chiếu
  bố cục, khoảng trắng, typography, màu sắc trước khi báo hoàn thành.
- **Mobile-friendly bắt buộc**: mọi trang/section phải responsive tốt trên di động (kiểm tra
  tối thiểu ở các breakpoint ~375px, ~768px, ~1280px), không chỉ tối ưu cho desktop.
- **Animation khi scroll**: mọi section trên trang phải có hiệu ứng xuất hiện khi cuộn tới
  (fade-in/slide-up khi vào viewport), dùng CSS (`@media (prefers-reduced-motion: reduce)`
  để tắt animation cho người dùng yêu cầu giảm chuyển động) kết hợp `IntersectionObserver`
  trong vanilla JS — không cần thư viện animation ngoài.
