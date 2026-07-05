# CLAUDE.md

Hướng dẫn cho Claude Code khi làm việc trong dự án này.

Chi tiết đã được tách theo chủ đề trong `.claude/rules/` (tự động nạp theo chuẩn Claude Code —
file không có `paths` nạp ngay từ đầu phiên, file có `paths` chỉ nạp khi đọc file khớp glob):

- [project-overview.md](.claude/rules/project-overview.md) — tổng quan dự án, thông tin công ty (luôn nạp)
- [project-structure.md](.claude/rules/project-structure.md) — cấu trúc thư mục (luôn nạp)
- [testing-workflow.md](.claude/rules/testing-workflow.md) — cách xem trước/kiểm thử (luôn nạp)
- [mandatory-rules.md](.claude/rules/mandatory-rules.md) — quy tắc bắt buộc: screenshot đối chiếu, mobile-friendly, scroll animation (luôn nạp)
- [design-style.md](.claude/rules/design-style.md) — phong cách thiết kế (nạp khi đọc `*.html`, `css/**/*.css`)
- [code-conventions.md](.claude/rules/code-conventions.md) — quy tắc code HTML/CSS/JS (nạp khi đọc `*.html`, `css/**/*.css`, `js/**/*.js`)
- [content-guidelines.md](.claude/rules/content-guidelines.md) — quy tắc nội dung/ngôn ngữ (nạp khi đọc `*.html`)

Khi cập nhật hướng dẫn dự án, sửa trực tiếp trong file rule tương ứng thay vì thêm lại vào đây.
