# Website Cửa hàng ô tô VinFast

Một website hoàn chỉnh cho cửa hàng ô tô VinFast được xây dựng bằng Next.js 15, TypeScript, và Tailwind CSS.

## 🚀 Tính năng chính


### 🚗 Quản lý sản phẩm
- Danh sách đầy đủ các mẫu xe VinFast (VF 3, VF 5, VF 6, VF 7, VF 8, VF 9, Lux A2.0, Lux SA2.0)
- Trang chi tiết sản phẩm với thông số kỹ thuật đầy đủ
- Bộ lọc theo loại xe, giá cả, năm sản xuất
- Tìm kiếm sản phẩm
- Chức năng so sánh xe

### 🛒 Hệ thống giỏ hàng
- Thêm xe vào giỏ hàng (đặt cọc)
- Quản lý số lượng và màu xe
- Tính toán tổng tiền đặt cọc
- Thanh toán trực tuyến

### 👤 Hệ thống người dùng
- Đăng ký/Đăng nhập
- Quản lý thông tin cá nhân
- Lịch sử đặt hàng

### 🚙 Đăng ký lái thử
- Form đăng ký lái thử chi tiết
- Chọn xe, thời gian, địa điểm
- Xác nhận lịch hẹn

### 📞 Liên hệ
- Form liên hệ tư vấn
- Thông tin showroom
- Bản đồ và thông tin liên hệ

### 📰 Tin tức
- Hệ thống tin tức về VinFast
- Phân loại theo danh mục
- Tìm kiếm tin tức

### 📱 Responsive Design
- Tối ưu cho mobile, tablet, desktop
- Giao diện thân thiện người dùng
- Hiệu ứng và animation mượt mà

## 🛠️ Công nghệ sử dụng

- **Framework**: Next.js 15 (App Router)
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **State Management**: Zustand
- **Form Handling**: React Hook Form
- **Icons**: Lucide React
- **Image Optimization**: Next.js Image

## 📦 Cài đặt và chạy

### Yêu cầu hệ thống
- Node.js 18+
- npm hoặc yarn

### Cài đặt
```bash
# Clone repository
git clone <repository-url>
cd cuahangoto

# Cài đặt dependencies
npm install

# Chạy development server
npm run dev
```

Mở [http://localhost:3000](http://localhost:3000) để xem website.

### Scripts có sẵn
```bash
npm run dev          # Chạy development server
npm run build        # Build production
npm run start        # Chạy production server
npm run lint         # Kiểm tra linting
```

## 📁 Cấu trúc thư mục

```
src/
├── app/                    # App Router pages
│   ├── auth/              # Trang đăng nhập/đăng ký
│   ├── products/          # Trang sản phẩm
│   ├── test-drive/        # Trang đăng ký lái thử
│   ├── contact/           # Trang liên hệ
│   ├── news/              # Trang tin tức
│   ├── compare/           # Trang so sánh xe
│   └── checkout/          # Trang thanh toán
├── components/            # React components
│   ├── Header.tsx         # Header navigation
│   ├── Footer.tsx         # Footer
│   ├── ProductCard.tsx    # Card hiển thị xe
│   ├── Cart.tsx           # Giỏ hàng
│   └── ...
├── data/                  # Dữ liệu mẫu
│   ├── cars.ts           # Dữ liệu xe
│   └── news.ts           # Dữ liệu tin tức
├── stores/               # Zustand stores
│   ├── useCartStore.ts   # Store giỏ hàng
│   └── useAuthStore.ts   # Store authentication
├── lib/                  # Utilities
│   └── utils.ts          # Helper functions
└── hooks/                # Custom hooks
    └── useToast.ts       # Toast notifications
```

## 🎨 Thiết kế

- **Màu chủ đạo**: Xanh VinFast (#1e3a8a)
- **Font**: Inter
- **Style**: Modern, clean, professional
- **Responsive**: Mobile-first approach

## 📊 Dữ liệu mẫu

Website bao gồm dữ liệu mẫu cho:
- 8 mẫu xe VinFast với thông số chi tiết
- Tin tức và bài viết
- Thông tin showroom
- Tài khoản demo: admin@vinfast.com / admin123

## 🔧 Tính năng nâng cao

- **SEO Optimization**: Meta tags, structured data
- **Performance**: Image optimization, lazy loading
- **Accessibility**: ARIA labels, keyboard navigation
- **Error Handling**: 404 page, error boundaries
- **Loading States**: Skeleton screens, spinners

## 🚀 Triển khai

Website có thể được triển khai trên:
- Vercel (khuyến nghị)
- Netlify
- AWS
- Heroku

```bash
# Build production
npm run build

# Start production server
npm run start
```

## 📝 Ghi chú

- Đây là phiên bản demo với dữ liệu mẫu
- Trong thực tế cần tích hợp với database và API backend
- Cần thêm payment gateway cho thanh toán thực
- Cần tích hợp với hệ thống CRM/ERP

## 🤝 Đóng góp

Mọi đóng góp đều được chào đón. Vui lòng tạo issue hoặc pull request.

## 📄 License

MIT License
