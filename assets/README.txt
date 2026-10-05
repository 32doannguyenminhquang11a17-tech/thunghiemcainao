WEBSITE PORTFOLIO - ĐOÀN NGUYỄN MINH QUANG
BẢN FINAL ĐÃ FIX LAYOUT PROJECT

CÁCH CHẠY:
1. Giải nén toàn bộ thư mục.
2. Mở index.html bằng Chrome/Edge hoặc dùng Live Server trong VS Code.
3. Nếu vừa thay CSS/ảnh, nhấn Ctrl + F5.

ĐÃ FIX:
- Sửa thẻ </div> dư trong project MISUMI.
- Project MISUMI: màn hình > 650px = chữ bên trái, ảnh bên phải.
- Màn hình <= 650px mới chuyển thành bố cục dọc.
- Ảnh project dùng object-fit: contain để không bị cắt.
- Giữ Times New Roman cho nội dung chính.
- Giữ toàn bộ CSS, JS, responsive và nút tải CV.

THAY ẢNH MISUMI:
- Xóa file assets/project1.jpg hiện tại.
- Chép ảnh thật vào assets/.
- Đổi tên ảnh thật thành project1.jpg.
- Nhấn Ctrl + F5.

THAY CV:
- Thay assets/CV_Doan_Nguyen_Minh_Quang.pdf bằng CV thật.
- Giữ nguyên tên file.

THÔNG TIN CÒN CẦN TỰ SỬA TRONG index.html:
- your-email@example.com
- 09xx xxx xxx
- facebook.com/ten-cua-ban


VIDEO CẢM BIẾN VÂN TAY
----------------------
Để hiện video ở Project 01:
- Chép video MP4 vào thư mục assets
- Đổi tên thành: fingerprint-demo.mp4

Đường dẫn website đang dùng:
assets/fingerprint-demo.mp4

Khuyến nghị:
- Định dạng MP4 (H.264)
- Video ngang 16:9 hoặc 4:3
- Dung lượng nên dưới khoảng 20-30 MB để web tải nhanh hơn


VIDEO AUTOPLAY
--------------
Phiên bản này đã được chỉnh:
- Video tự chạy khi cuộn tới khu vực Project 01
- Tự dừng khi cuộn ra khỏi màn hình
- Tự lặp lại liên tục
- Tắt tiếng để trình duyệt cho phép autoplay
- Không hiện thanh điều khiển
- Hỗ trợ playsinline trên điện thoại

Chỉ cần đặt video tại:
assets/fingerprint-demo.mp4


PROJECT CUỘC THI TỦ ĐIỆN
------------------------
Đã thêm PROJECT 03 về cuộc thi lắp ráp & thiết kế tủ điện.

Nếu muốn thay ảnh:
1. Chép ảnh vào thư mục assets
2. Đổi tên thành: project-tu-dien.jpg
3. Trong index.html, tìm "ẢNH CUỘC THI TỦ ĐIỆN"
4. Xóa khối placeholder
5. Bỏ comment thẻ:
   <img src="./assets/project-tu-dien.jpg" alt="Cuộc thi lắp ráp và thiết kế tủ điện">

Project "Bảo trì & tủ điều khiển PLC" đã được đổi số từ 03 thành 04.
