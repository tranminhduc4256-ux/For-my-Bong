# Website tình yêu ♡

Website tĩnh dùng HTML, CSS và JavaScript thuần; có video nền, nhạc nền, hiệu ứng trái tim, album ảnh và thư tình. Không cần cài phần mềm hay thư viện.

## Chạy thử trên máy tính
1. Giải nén thư mục.
2. Mở `index.html` bằng Chrome hoặc Edge.
3. Bấm **Chạm để bắt đầu** để kích hoạt nhạc.

Lưu ý: để thử video/nhạc cục bộ ổn định nhất, hãy đăng lên GitHub Pages như hướng dẫn bên dưới. Một số trình duyệt có thể hạn chế phát tệp âm thanh/video khi mở trực tiếp từ ổ đĩa.

## Thay video và nhạc
1. Chép video MP4 của bạn vào thư mục `assets`, đặt tên `background.mp4`.
2. Chép nhạc MP3 của bạn vào `assets`, đặt tên `music.mp3`.
3. Giữ nguyên tên tệp hoặc sửa đường dẫn trong `index.html`.
4. Nên nén video MP4 H.264, độ phân giải 720p hoặc 1080p và dung lượng vừa phải để trang tải nhanh.

## Thay ảnh
Trong `index.html`, tìm ba thẻ `<img ...>` trong phần album. Thay giá trị `src` bằng đường dẫn ảnh của bạn, ví dụ:
- `src="assets/anh-1.jpg"`
- `src="assets/anh-2.jpg"`
- `src="assets/anh-3.jpg"`

Sau đó tải các ảnh tương ứng vào thư mục `assets`. Sửa nội dung trong `figcaption` để đổi chú thích.

## Sửa lời nhắn / tiêu đề
Mở `index.html` bằng Notepad hoặc VS Code:
- Tìm `My heart` để sửa tiêu đề.
- Tìm `Gửi cậu, người tớ thương` để sửa tiêu đề thư.
- Sửa các đoạn văn trong `letter-wrap` để viết lời nhắn riêng.
- Tìm `For You ♡` để đổi tên trang trên tab trình duyệt.

## Đưa lên GitHub Pages miễn phí
1. Đăng nhập hoặc tạo tài khoản tại https://github.com/
2. Bấm dấu `+` ở góc trên → **New repository**.
3. Đặt tên kho, ví dụ `website-tinh-yeu`. Chọn **Public** → **Create repository**.
4. Giải nén tệp ZIP trên máy tính.
5. Trong trang kho GitHub, chọn **Add file → Upload files**.
6. Tải lên `index.html`, `README.md` và thư mục `assets` (nếu đã có ảnh/nhạc/video). Có thể kéo thả các tệp/thư mục vào trang.
7. Bấm **Commit changes**.
8. Mở **Settings → Pages**.
9. Trong phần **Build and deployment**, chọn **Deploy from a branch**.
10. Chọn branch `main`, thư mục `/(root)`, rồi bấm **Save**.
11. Chờ vài phút. GitHub sẽ hiển thị đường link dạng `https://TEN-TAI-KHOAN.github.io/website-tinh-yeu/`.

Nếu chưa thấy trang, tải lại mục **Settings → Pages** sau 1–5 phút. Khi sửa website, tải tệp mới lên và commit lại.

## Lưu ý quan trọng
- Người có đường link công khai có thể xem trang và tải các tệp công khai; không tải lên thông tin riêng tư nhạy cảm.
- Chỉ dùng nhạc, ảnh, video mà bạn có quyền sử dụng hoặc được phép chia sẻ.
- Trình duyệt thường chặn âm thanh tự phát trước khi người xem tương tác. Nút **Chạm để bắt đầu** được thiết kế để bắt đầu nhạc sau cú bấm đầu tiên.
- GitHub Pages phù hợp với website tĩnh; không có cơ sở dữ liệu hay chức năng đăng nhập.
- Nếu video/nhạc quá lớn, nên nén trước khi tải lên để trang không tải quá chậm.
