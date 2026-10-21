# Thiệp hoa điện tử 20/10 — phiên bản trải nghiệm điện thoại

## Luồng người nhận
1. Màn hình mở đầu là ảnh mèo đáng yêu, kèm dòng **“Nhấp vào ảnh có bất ngờ”**.
2. Khi chạm ảnh, bài nhạc đã chọn bắt đầu phát (trình duyệt thường yêu cầu thao tác chạm để cho phép phát âm thanh), rồi chuyển sang cảnh hoa hồng nở và dòng **“Chúc mừng ngày 20/10”**.
3. Chạm **“Mở thư yêu thương”** để xem lời chúc, tên người nhận/người gửi.
4. Người nhận có thể chọn **“Đọc lại thư”** hoặc **“Tiếp theo”**. Có nút đọc thư thành tiếng bằng giọng đọc của trình duyệt, không bắt buộc.
5. Trang cuối có hiệu ứng hoa bung và dòng **“HAPPY WOMEN DAY”**.

## Chạy thử
- Giải nén toàn bộ ZIP.
- Giữ `index.html` và `cat-intro.png` trong cùng một thư mục.
- Mở `index.html` bằng Chrome hoặc Edge.
- Trong trình chỉnh sửa, chọn một bài nhạc, nhập tên/lời chúc rồi tạo link chia sẻ.

## Đưa lên mạng
Tải cả `index.html` và `cat-intro.png` lên cùng thư mục ở GitHub Pages hoặc hosting tĩnh tương tự. Chia sẻ link được tạo từ website đã triển khai; đường link lưu tên, lời chúc và mã bài nhạc đã chọn.

## Lưu ý âm thanh
- Nhạc gợi ý dùng trình phát YouTube nhúng. Việc tự phát phụ thuộc vào chính sách trình duyệt, kết nối Internet và việc video có cho phép nhúng hay không. Thao tác chạm ảnh mở đầu là thao tác tương tác đầu tiên để xin phát nhạc.
- Có thể tải tệp nhạc riêng trong phần chỉnh sửa để phát trực tiếp trong bản xem trước. Tệp nhạc/ảnh người dùng tải từ máy không tự tải lên hosting và không tự đi kèm link chia sẻ.
- Đọc thư thành tiếng dùng `SpeechSynthesis` của trình duyệt; giọng tiếng Việt có thể khác nhau tùy thiết bị.


## Chia sẻ bằng QR code (quan trọng)
- QR chỉ hoạt động trên điện thoại khác khi mã dẫn tới địa chỉ website công khai dạng `https://...`. Đường dẫn `file:///C:/...` chỉ trỏ tới file cục bộ trên máy tạo thiệp, vì vậy điện thoại không thể mở nó.
- Đưa cả `index.html` và `cat-intro.png` lên GitHub Pages hoặc hosting tĩnh. Ví dụ địa chỉ sau khi đăng tải có thể có dạng `https://ten-tai-khoan.github.io/ten-repository/`.
- Nếu đang mở `index.html` bằng cách nhấp đúp trên máy tính, bấm **Tạo mã QR**, dán URL công khai vào ô **Địa chỉ website đã đăng tải**, rồi bấm tạo mã QR lần nữa.
- Bấm **Tải ảnh QR xuống (PNG)** để lưu ảnh mã QR và gửi ảnh qua Zalo/Messenger. Người nhận quét mã sẽ mở website công khai với đúng tên, lời chúc và bài nhạc gợi ý đang chọn trong URL.
- Khi website đã được mở từ địa chỉ `https://...`, không cần nhập URL thủ công; hệ thống sẽ dùng địa chỉ đang mở để tạo link và QR.
- Ảnh tùy chỉnh và tệp nhạc tải từ máy tính không được nhúng trong link. Muốn người nhận cùng xem/nghe ảnh hoặc tệp nhạc riêng, cần tải các tệp đó lên nơi lưu trữ công khai và bổ sung URL tệp trong thiệp.
