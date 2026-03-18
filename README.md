# Web Đặt Vé Máy Bay - Nhóm 10

## Thành viên nhóm
- **22010401** - Duy  

---

## Mục tiêu dự án
Xây dựng **website đặt vé máy bay trực tuyến** bằng **Laravel Framework**, chạy trên **XAMPP**.  
Hệ thống cho phép người dùng:
- Tìm kiếm chuyến bay theo ngày, điểm đi, điểm đến.  
- Xem thông tin chi tiết chuyến bay.  
- Đặt vé trực tuyến và thanh toán.  
- Quản lý đơn đặt vé (người dùng và admin).  

---

## Công nghệ sử dụng
| Thành phần | Công nghệ |
|-------------|------------|
| **Ngôn ngữ lập trình** | PHP (Laravel Framework) |
| **Cơ sở dữ liệu** | MySQL |
| **Frontend** | Blade Template (HTML, CSS, JavaScript, Bootstrap) |
| **Server nội bộ** | XAMPP (Apache, MySQL, PHP) |
| **Quản lý mã nguồn** | Git + GitHub |

---

## Cấu trúc dự án (Laravel)
flight_booking/
├── app/ # Controllers, Models, Logic xử lý
├── bootstrap/ # File khởi tạo ứng dụng
├── config/ # File cấu hình hệ thống
├── database/ # Migration, Seeders
├── public/ # index.php, CSS, JS, ảnh
├── resources/ # Giao diện (Blade), assets
├── routes/ # web.php, api.php
├── storage/ # Logs, cache, file upload
├── tests/ # Unit test
└── composer.json # Quản lý gói PHP


---

## Cài đặt và chạy dự án trên XAMPP
### 1️.Cài đặt môi trường
- Cài **XAMPP** (PHP ≥ 8.1)  
- Cài **Composer**  
- Clone project về:

