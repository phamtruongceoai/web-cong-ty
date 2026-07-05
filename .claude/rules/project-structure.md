# Cấu trúc thư mục

Vì không dùng build tool, giữ cấu trúc phẳng và rõ ràng:

```
/
├── index.html          # Trang chủ (hero + giới thiệu dịch vụ AI)
├── css/
│   └── style.css        # Toàn bộ style, có thể tách thêm file khi lớn dần
├── js/
│   └── main.js           # JS thuần (vanilla), không dùng framework
├── assets/
│   ├── images/           # Ảnh, minh hoạ
│   └── fonts/             # Font nếu tự host thay vì dùng Google Fonts CDN
└── CLAUDE.md
```

Không tạo `package.json`, bundler, hay framework trừ khi người dùng yêu cầu rõ ràng thay đổi stack.
