# nangcap.work 🚀

Trang web chào mừng chính thức của **nangcap.work** — Nền tảng nâng tầm hiệu suất, tự động hoá và giải pháp công việc tương lai.

## ✨ Điểm Nổi Bật

- **Thiết kế hiện đại & Tối giản:** Tông màu Dark Slate, hiệu ứng Glassmorphism, Responsive toàn diện trên mọi kích thước màn hình.
- **Trải nghiệm tương tác:** Lời chào cá nhân hoá theo khung giờ thực tế (sáng/trưa/tối), hiệu ứng icon Lucide mượt mà.
- **Tối ưu tốc độ:** Tối ưu hóa Static HTML, không phụ thuộc build phức tạp, sẵn sàng triển khai thẳng lên Cloudflare Pages.

## ☁️ Hướng Dẫn Triển Khai Lên Cloudflare Pages

Mã nguồn được cấu trúc tĩnh (Static HTML), bạn có thể triển khai lên Cloudflare theo 2 cách đơn giản:

### Cách 1: Kết Nối Git Trực Tiếp Từ Cloudflare Dashboard
1. Truy cập **Cloudflare Dashboard** > **Workers & Pages** > **Create application** > **Pages** > **Connect to Git**.
2. Chọn repository riêng tư (Private) `nangcap.work`.
3. Cấu hình triển khai:
   - **Framework preset:** `None`
   - **Build command:** để trống
   - **Build output directory:** `/` (hoặc `.`)
4. Bấm **Save and Deploy**.

### Cách 2: Triển Khai Qua Wrangler CLI
Nếu có sẵn Wrangler trên máy:
```bash
npx wrangler pages deploy . --project-name=nangcap-work
```

---
© 2026 nangcap.work. All rights reserved.
