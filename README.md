# MODCOMBO Static GitHub Pages Build

Bộ code static được dựng từ HTML gốc của trang chủ MODCOMBO và tối ưu để chạy trực tiếp trên GitHub Pages.

## Cách dùng
1. Upload `index.html` vào root repository.
2. Bật GitHub Pages từ branch chính.
3. Truy cập domain GitHub Pages để kiểm tra.

## Đã fix
- Chuyển lazy image `data-lazy-src` thành `src` thật.
- Loại bỏ script WordPress/WP Rocket/Cloudflare dễ lỗi trên hosting tĩnh.
- Giữ SEO meta, canonical, Open Graph, Twitter Card và JSON-LD.
- Giữ layout trang chủ, menu, slider, grid ứng dụng/game, footer.
- Thêm CSS/JS fallback để chạy ổn không cần backend WordPress.
