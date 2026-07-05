---
paths:
  - "*.html"
  - "css/**/*.css"
  - "js/**/*.js"
---

# Quy tắc code

- HTML: semantic tags (`<header>`, `<main>`, `<section>`, `<footer>`, `<nav>`) để tốt cho SEO và
  accessibility. Luôn có `alt` cho ảnh, `lang="vi"` trên thẻ `<html>`.
- CSS: dùng CSS thuần (custom properties `:root { --color-... }` cho bộ màu/spacing), mobile-first,
  responsive bằng flexbox/grid. Không cần framework CSS (Tailwind/Bootstrap) trừ khi được yêu cầu.
- JS: vanilla JS, chỉ thêm khi cần tương tác thực sự (menu mobile, smooth scroll, form validation).
  Không thêm thư viện ngoài nếu không cần thiết.
- Không viết comment giải thích cái gì code đang làm nếu tên biến/class đã rõ nghĩa.
- Giữ trang nhẹ: tối ưu ảnh, hạn chế font-weight/font-family không cần thiết, không tải JS thừa.
