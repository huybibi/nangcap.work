# nangcap.work Agency 🚀

**nangcap.work Agency** — Digital Marketing & Performance Agency thế hệ mới, thành lập từ năm **2024**.

Chuyên sâu đồng hành cùng các doanh nghiệp SMEs và E-commerce bứt phá tăng trưởng doanh thu dựa trên dữ liệu, ma trận quảng cáo đa định dạng (MFA) và tối ưu hóa vòng đời khách hàng (LTV).

---

## ⚡ Các Trụ Cột Dịch Vụ Cốt Lõi

1. **Performance Ads (Meta, TikTok, Google Ads):** Tối ưu CPA, chia nhỏ nhóm sở thích đơn lẻ, micro-budget test và đấu thầu thông minh.
2. **Creative & Video Engine:** Sản xuất video ngắn (Reels, TikTok, Shorts) giữ chân người xem cao, content mỏ neo đánh trúng tâm lý mua hàng.
3. **CRM & Tối Ưu LTV:** Khai thác tối đa doanh thu sau bán hàng (Post-Purchase Revenue) với quy trình chăm sóc 3 nấc.
4. **Tư Vấn & Đào Tạo In-house:** Chuyển giao quy trình vận hành và báo cáo minh bạch cho doanh nghiệp.

---

## ☁️ Hướng Dẫn Triển Khai Lên Cloudflare Pages

Mã nguồn được cấu trúc tĩnh thuần túy (Static HTML/JS/Tailwind CDN), sẵn sàng triển khai mượt mà lên Cloudflare Pages:

### Cách 1: Kết Nối Git Từ Cloudflare Dashboard
1. Vào **Cloudflare Dashboard** > **Workers & Pages** > **Create application** > **Pages** > **Connect to Git**.
2. Chọn repository riêng tư (Private) `nangcap.work`.
3. Cấu hình:
   - **Framework preset:** `None`
   - **Build command:** để trống
   - **Build output directory:** `/` (hoặc `.`)
4. Chọn **Save and Deploy**.

### Cách 2: Triển Khai Qua Wrangler CLI
```bash
npx wrangler pages deploy . --project-name=nangcap-work
```

---
© 2024 - 2026 nangcap.work Agency. All rights reserved.
