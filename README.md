# Trang Web Chúc Mừng Sinh Nhật Mẹ ❤️

## Cấu trúc thư mục
- `index.html`: Toàn bộ giao diện, hiệu ứng pháo hoa, bánh kem, nhạc chúc mừng và thư viện ảnh.
- `images/`: Thư mục chứa ảnh của Mẹ (`me-1.jpg`, `me-2.jpg`, `me-3.jpg`, `me-4.jpg`, `me-5.jpg`, `me-6.jpg`).

## Cách thay ảnh & chỉnh lời chúc
1. Copy 6 tấm ảnh của Mẹ vào thư mục `images/` và đặt tên lần lượt là:
   - `me-1.jpg`
   - `me-2.jpg`
   - `me-3.jpg`
   - `me-4.jpg`
   - `me-5.jpg`
   - `me-6.jpg`
   *(Web hỗ trợ tự động nhận cả đuôi `.jpg`, `.JPG`, `.png`, `.jpeg`)*
2. Mở file `index.html` bằng Notepad hoặc VS Code, tìm mục `SITE_CONFIG` ở phần `<script>` để sửa lời chúc hoặc chú thích dưới từng ảnh (nếu muốn).

## Cách đẩy lên GitHub và tạo link web thật (GitHub Pages)
1. Tạo một repository mới trên GitHub (ví dụ: `sinh-nhat-me`) ở chế độ **Public**.
2. Đẩy toàn bộ file `index.html` và thư mục `images/` lên repository đó.
3. Vào tab **Settings** -> **Pages** (cột bên trái).
4. Tại mục **Build and deployment** -> **Branch**, chọn nhánh `main` (hoặc `master`), thư mục `/ (root)` -> bấm **Save**.
5. Đợi khoảng 1–2 phút và tải lại trang, GitHub sẽ cấp cho bạn đường link công khai dạng:
   `https://<ten-tai-khoan>.github.io/sinh-nhat-me/`
