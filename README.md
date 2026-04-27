# DoSheet — Website Chính Thức

Website giới thiệu sản phẩm DoSheet: phần mềm quản lý doanh nghiệp trên nền tảng Google Sheets.

## Cấu trúc trang

| File | Trang |
|------|-------|
| `index.html` | 🏠 Trang chủ (Landing Page) |
| `login.html` | 🔐 Đăng nhập / Đăng ký |
| `dashboard.html` | 📊 Bảng điều khiển người dùng |
| `blog.html` | 📝 Blog & Kiến thức |
| `community.html` | 👥 Cộng đồng DoSheet |
| `affiliate.html` | 🤝 Chương trình Đối tác (Affiliate) |
| `cham-cong.html` | ⏱️ Quản lý Chấm công & Tính lương |
| `gio-hang.html` | 🛒 Giỏ hàng |
| `checkout.html` | 💳 Thanh toán |
| `help-center.html` | ❓ Trung tâm Hỗ trợ |

---

## 🚀 Deploy lên GitHub Pages (miễn phí)

### Bước 1: Tạo Repository trên GitHub

1. Truy cập [github.com](https://github.com) → Đăng nhập tài khoản
2. Nhấn nút **"New"** (góc trên bên trái) để tạo repo mới
3. Đặt tên repo: `dosheet-website` (hoặc tên bất kỳ)
4. Chọn **Public** → Nhấn **"Create repository"**

### Bước 2: Upload file lên GitHub

**Cách đơn giản nhất (kéo thả):**

1. Vào trang repo vừa tạo
2. Nhấn **"uploading an existing file"** (dòng chữ nhỏ ở giữa trang)
3. **Kéo toàn bộ các file `.html`** vào vùng upload
4. Kéo thêm file `README.md`
5. Nhấn **"Commit changes"** (nút xanh phía dưới)

**Hoặc dùng Git (nếu đã cài):**
```bash
git init
git add .
git commit -m "Initial commit: DoSheet website"
git branch -M main
git remote add origin https://github.com/TÊN_BẠN/dosheet-website.git
git push -u origin main
```

### Bước 3: Bật GitHub Pages

1. Vào repo → Nhấn tab **"Settings"** (⚙️)
2. Cuộn xuống mục **"Pages"** (thanh bên trái)
3. Mục **"Source"** → Chọn **"Deploy from a branch"**
4. Mục **"Branch"** → Chọn **`main`** → Chọn thư mục **`/ (root)`**
5. Nhấn **"Save"**

### Bước 4: Xem website

Sau 1-2 phút, website của bạn sẽ live tại:
```
https://TÊN_BẠN.github.io/dosheet-website/
```

> **Lưu ý:** `TÊN_BẠN` là username GitHub của bạn

---

## 🛠️ Tùy chỉnh nội dung

Tất cả các file đều là HTML thuần — bạn có thể mở bằng bất kỳ trình soạn thảo nào:
- **VS Code** (khuyến nghị) — miễn phí tại [code.visualstudio.com](https://code.visualstudio.com)
- Notepad++ 
- Sublime Text

### Những thứ cần cập nhật trước khi ra mắt:

- [ ] Thay thông tin liên hệ (email, số điện thoại, địa chỉ)
- [ ] Cập nhật link mạng xã hội (Facebook, Zalo, YouTube)
- [ ] Chỉnh bảng giá theo thực tế
- [ ] Thay logo (nếu có file logo)
- [ ] Cập nhật nội dung blog
- [ ] Kết nối form liên hệ (dùng [Formspree](https://formspree.io) — miễn phí)

---

## 🎨 Công nghệ sử dụng

- **HTML5** — Thuần HTML, không cần build tool
- **Tailwind CSS** — Load qua CDN, không cần cài đặt
- **Plus Jakarta Sans** — Font chữ (Google Fonts)
- **Material Symbols** — Icon set (Google)

---

## 📞 Hỗ trợ

Nếu cần hỗ trợ kỹ thuật, liên hệ: dongochung139@gmail.com
