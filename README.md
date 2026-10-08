# nangcap.work Agency 🚀

**nangcap.work Agency** — Digital Marketing & Performance Agency thế hệ mới, thành lập từ năm **2024**.

Chuyên sâu đồng hành cùng các doanh nghiệp SMEs và E-commerce bứt phá tăng trưởng doanh thu dựa trên dữ liệu, ma trận quảng cáo đa định dạng (MFA), sản xuất video ngắn chuyển đổi và tối ưu hóa vòng đời khách hàng (LTV).

---

## 📂 Cấu Trúc Hệ Thống Website (Multi-Page Architecture)

Hệ thống bao gồm 5 trang hoàn chỉnh, thiết kế chuẩn hiện đại (Dark Mode, Glassmorphism, Responsive & Tương tác cao):

1. **[`index.html`](index.html) — Trang Chủ (Home):**
   - Định vị thương hiệu thành lập từ 2024 (Est. 2024).
   - Chỉ số năng lực thực chiến (150+ Dự án, ROAS trung bình 3.8x, 95% Khách hàng đồng hành).
   - 4 Trụ cột dịch vụ cốt lõi, quy trình 4 bước thực chiến.
   - Widget tương tác mô phỏng doanh số (ROI Calculator) và Form đăng ký Audit 1-1.

2. **[`dich-vu.html`](dich-vu.html) — Dịch Vụ Chuyên Sâu (Services):**
   - Phân tích chi tiết 4 giải pháp: *Performance Marketing*, *Creative & Video Production*, *Hệ thống CRM & Tối ưu LTV*, *Tư vấn & Đào tạo In-house*.
   - Bảng so sánh 3 gói dịch vụ: **Khởi Động (Starter)**, **Bứt Phá (Growth)**, **Độc Quyền (Enterprise)**.

3. **[`du-an.html`](du-an.html) — Case Studies Thực Chiến (Projects):**
   - Case Study E-commerce Thời trang: Giảm 46% CPA, ROAS đạt 4.8x.
   - Case Study F&B: Tăng 320% lượt đặt bàn ngày trong tuần qua video mỏ neo địa phương.
   - Case Study Mỹ Phẩm Thiên Nhiên: Doanh thu sau bán hàng đạt 42% nhờ CRM 3 nấc.
   - Đánh giá xác thực từ các Founder đối tác.

4. **[`ve-chung-toi.html`](ve-chung-toi.html) — Về Chúng Tôi (About Us):**
   - Câu chuyện thành lập 2024: Giải quyết nỗi đau lãng phí ngân sách và các con số tương tác ảo.
   - 4 Giá trị cốt lõi: *Dữ liệu trung thực*, *Bảo vệ ngân sách*, *Sáng tạo thực chiến*, *Đồng hành dài hạn*.
   - Timeline các cột mốc phát triển 2024 – 2026.

5. **[`lien-he.html`](lien-he.html) — Liên Hệ & Đặt Lịch Tư Vấn (Contact):**
   - Hotline/Zalo, Email, địa chỉ văn phòng Hà Nội & TP. Hồ Chí Minh.
   - Form đăng ký khảo sát kênh chuyên sâu có bộ lọc ngân sách & mục tiêu.
   - Cam kết bảo mật thông tin bằng văn bản NDA.

---

## ☁️ Hướng Dẫn Triển Khai Lên Cloudflare Pages

Toàn bộ các trang là mã nguồn tĩnh thuần túy (Static HTML/CSS/JS), không cần bước build phức tạp, sẵn sàng đưa lên Cloudflare:

### Cách 1: Kết Nối Git Trực Tiếp Từ Cloudflare Dashboard
1. Truy cập **Cloudflare Dashboard** > **Workers & Pages** > **Create application** > **Pages** > **Connect to Git**.
2. Chọn repository riêng tư (Private) `nangcap.work`.
3. Thiết lập thông số:
   - **Framework preset:** `None`
   - **Build command:** để trống
   - **Build output directory:** `/` (hoặc `.`)
4. Nhấn **Save and Deploy**. Cloudflare sẽ tự động cập nhật mỗi khi bạn push code mới!

### Cách 2: Triển Khai Nhanh Bằng Wrangler CLI
```bash
npx wrangler pages deploy . --project-name=nangcap-work
```

---
© 2024 - 2026 nangcap.work Agency. All rights reserved.
