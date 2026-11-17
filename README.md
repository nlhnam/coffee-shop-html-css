# Wild Pine Coffee

Project tự luyện tập dựng giao diện web bán cà phê bằng **HTML5 và CSS3 thuần** (không dùng framework hay JavaScript). Giao diện của trang được mình tham khảo và làm lại theo phong cách tối giản của Blue Bottle Coffee.

Mục tiêu chính khi làm repo này là để nắm chắc cách chia bố cục với Flexbox, CSS Grid và quản lý file CSS sao cho gọn, dễ sửa.

## Các trang đã làm

- **Trang chủ (`index.html`):**
  - Thanh menu trên cùng dính cố định khi cuộn trang (`position: sticky`).
  - Banner chính với hình barista pha pour-over, phủ một lớp gradient tối bên trái để chữ trắng nổi rõ.
  - Khu vực *Holiday Best Sellers* chia 4 cột, có hiệu ứng hover hiện nút thêm vào giỏ hàng.
- **Trang cửa hàng (`shop.html`):**
  - Banner ngang đầu trang và lưới hiển thị 9 sản phẩm (3x3).
- **Trang tài khoản (`login.html`):**
  - Gộp chung form Đăng nhập và Đăng ký thành 2 cột song song trên cùng một màn hình.

## Cấu trúc thư mục

```text
coffee-shop-html-css/
├── index.html          # Trang chủ
├── shop.html           # Trang danh sách sản phẩm
├── login.html          # Trang đăng nhập & đăng ký
├── style.css           # File CSS dùng chung cho cả 3 trang
├── hero-banner.jpg     # Ảnh nền banner chính
└── README.md
