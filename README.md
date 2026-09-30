# Shipping Video Editor PWA — iPhone V1.0

PWA chuyển từ bản Windows sang giao diện dùng trên iPhone.

## Chức năng
- Cài lên Màn hình chính từ Safari.
- Chọn ảnh/video, logo, nhạc từ iPhone.
- Thông tin thương hiệu và template tuyến vận chuyển.
- Chữ overlay xanh dương #0B5ED7 viền trắng.
- Tỷ lệ 9:16, 1:1, 16:9.
- 720p và 1080p.
- Preview trực tiếp.
- Dựng video bằng Canvas + MediaRecorder khi Safari hỗ trợ.
- Danh sách gợi ý nhạc quê hương + tìm preview iTunes.
- Service Worker để giao diện hoạt động offline sau lần tải đầu.

## Cài trên iPhone
PWA phải được host bằng HTTPS. Upload toàn bộ thư mục này lên GitHub Pages, Netlify, Vercel, Cloudflare Pages hoặc hosting có SSL.

Sau đó trên iPhone:
1. Mở URL bằng Safari.
2. Chọn Chia sẻ.
3. Chọn “Thêm vào Màn hình chính”.
4. Bấm “Thêm”.

## Lưu ý
Dựng video trên iPhone phụ thuộc bộ nhớ và codec MediaRecorder của Safari. Nếu 1080p không ổn định, dùng 720p. Nếu Safari không hỗ trợ MP4 cho MediaRecorder, app sẽ dùng codec video khác nếu có.

Nhạc thương mại chỉ nên dùng preview để nghe thử. Muốn chèn bản đầy đủ, hãy chọn file nhạc bạn có quyền sử dụng từ iPhone.


## Bản GitHub dễ upload
Hai file icon-192.png và icon-512.png đã được chuyển ra thư mục gốc. Không cần tạo thư mục icons trên GitHub.
