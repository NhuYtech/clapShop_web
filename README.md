🛒 ClapShop – Ứng dụng mua laptop trực tuyến  
📌 Báo cáo học phần môn Lập trình web  
📍 Trường Đại học Kỹ thuật – Công nghệ Cần Thơ (CTUT)  
👨‍🏫 Giảng viên hướng dẫn: ThS. Phạm Yến Nhi  

👨‍💻 Nhóm sinh viên thực hiện:

- Nguyễn Thành Đạt – HTTT2211003
- Nguyễn Trần Anh Khoa – HTTT2211026
- Huỳnh Như Ý – HTTT2211015
- Võ Trường Nguyên – HTTT2211025
- Nguyễn Thành Phát – HTTT2211004

🎯 Mục tiêu của hệ thống  
Ứng dụng ClapShop được xây dựng nhằm giúp khách hàng mua sắm sản phẩm trực tuyến một cách tiện lợi và nhanh chóng. Hệ thống hướng đến mục tiêu:
- Tối ưu hóa trải nghiệm mua sắm của người dùng qua website.
- Hỗ trợ cửa hàng trong việc quản lý sản phẩm, đơn hàng và khách hàng.
- Cung cấp công cụ quản lý tài khoản người dùng và hỗ trợ thanh toán trực tuyến.

🧩 Các chức năng chính

👤 **Quản lý tài khoản**  
- Đăng ký / Đăng nhập  
- Cập nhật thông tin cá nhân
- Quên mật khẩu  

🛍️ **Quản lý sản phẩm & giỏ hàng**  
- Hiển thị danh sách sản phẩm  
- Thêm sản phẩm vào giỏ hàng  
- Cập nhật số lượng, xóa sản phẩm trong giỏ hàng  
- Tìm kiếm sản phẩm  
- Lọc sản phẩm theo danh mục  

📦 **Quản lý đơn hàng**  
- Đặt hàng, xác nhận đơn hàng  
- Theo dõi trạng thái đơn hàng  
- Xem lịch sử giao dịch  

🧑‍🤝‍🧑 **Quản lý người dùng**  
- Xem và chỉnh sửa hồ sơ cá nhân  
- Địa chỉ giao hàng  
- Chăm sóc khách hàng  

🛠️ **Công nghệ sử dụng**

| Thành phần          | Công nghệ                 |
|---------------------|---------------------------|
| Ngôn ngữ lập trình  | PHP, Laravel              |
| IDE                 | VS Code, Sublime Text     |
| UI Framework        | Bootstrap 4, jQuery       |
| Database            | MySQL                     |
| Image Handling      | Intervention Image        |
| Source Control      | GitHub                    |
| Kiến trúc           | MVC (Model - View - Controller) |

👥 **Đối tượng sử dụng**  
- **Khách hàng**: Đăng nhập/đăng ký tài khoản, duyệt sản phẩm, đặt hàng, xem lịch sử giao dịch.  
- **Cửa hàng**: Quản lý sản phẩm, đơn hàng, phản hồi khách hàng, thống kê doanh thu.  

💡 **Các điểm nổi bật**
- 📱 Giao diện hiện đại, tương thích với nhiều kích thước màn hình.  
- 🧠 Kiến trúc MVC giúp dễ bảo trì và mở rộng.  
- 🔄 Tính năng tìm kiếm và lọc sản phẩm nhanh chóng.  
- 🛒 Giỏ hàng thông minh, hỗ trợ thay đổi số lượng và xóa sản phẩm dễ dàng.  
- 📈 Cung cấp thống kê đơn hàng, doanh thu cho người quản lý.  

📌 **Ghi chú**  
Đây là báo cáo môn Lập trình web, được thực hiện tại Trường Đại học Kỹ thuật – Công nghệ Cần Thơ. Ứng dụng ClapShop mô phỏng quy trình mua sắm trực tuyến và quản lý sản phẩm, đơn hàng tại một cửa hàng trực tuyến.

📬 **Liên hệ**
- 👩‍💻 Sinh viên: Huỳnh Như Ý – HTTT2211015  
- 📞 Hotline: 0982 147 252  
- 📧 Email: huynhnhuy.tech@gmail.com
- 🔗 GitHub: https://github.com/NhuYtech  
- 💻 Source code hiện đang được phát triển và cập nhật tại:  
  - 🔗 https://github.com/NhuYtech/ClapShop

---


# Fresh database

php artisan migrate:fresh --seed

# Account: `Username` | `Password`

- `ADMIN:` sinoo | 123456
- `CUSTOMER:` teo | cus123

# Documentation

- Link Plan: `<https://docs.google.com/spreadsheets/d/14FsP_WT7bO9Px5cJIJGaz0Ljs5mbC_g9_CklYtxpvKM/edit?usp=sharing>`

- Link Dữ liệu mẫu: `https://docs.google.com/spreadsheets/d/1O18eoNwREFU0ARyQGcHxTNt9ueVI0rz5opADQSRVpv4/edit?usp=drive_link`

- Link SRC: `<https://drive.google.com/drive/folders/1iz-iIZITxwT4mafGzPmvLm0ycVzTC_sE?usp=drive_link>`

# Công việc các thành viên

## `1. Leader: Anh Khoa - HTTT2211026`

### `---Thiết lập dự án---`

- Thiết kế database
- Setup, khởi tạo dự án và môi trường chạy dự án
- Tìm source template: Admin và Customer
- Quy định route: Admin và Customer
- Cài đặt Middleware: Chặn xác thực User trước khi thực hiện chức năng
- `Quản lý` source code với `Github`
- Quản lý `Plan` và `Deadline`
- Lên nội dung cho thuyết trình

### `---Code Admin side---`

- `Module`: Thanh toán POS, Đơn hàng, khách hàng có kết hợp ajax

### `---Code Customer side---`

- `Module`: Thanh toán, Giỏ hàng, Đơn hàng
- Cài đặt `session` để CRUD: Giỏ hàng
- Lọc sản phẩm bằng slug Category

## `2. Trường Nguyên - HTTT2211025`

### `---Nghiên cứu và triển khai công nghệ---`

- `Thiết kế database`
- Đưa ra giả pháp nhập hàng, bán hàng
- Logic luồng hoạt động
- Đổi mật khẩu
- Quên mật khẩu

### `---Code Admin side---`

- `Module`: Sản phẩm (CRUD có hình ảnh)

### `---Code Customer side---`

- Hoàn thiện chức năng lọc sản phẩm theo giá

### `---Kiểm thử---`

- Test toàn bộ chức năng website

### `---Hỗ trợ kỹ thuật cho việc báo cáo---`

## `3. Thành Đạt - HTTT2211003`

### `---Tối ưu source code---`

- Dọn tài nguyên rác
- Điều khiển merge luồng code

### `---Thiết kế và làm mịn UI---`

- Thiết kế logo, Banner, Icon website
- Chọn màu chủ đạo cho website
- Thiết kế Slide báo cáo

### `---Code Admin side---`

- `Module`: Danh mục (CRUD có hình ảnh), Dashboard

### `---Code Customer side---`

- Đưa ra giải pháp và chỉnh sửa: Trang chủ, sản phẩm,
- Chỉnh sửa UI tĩnh: Liên hệ

## `4. Như Ý - HTTT2211015`

### `---Thiết lập dự án---`

- `Thiết kế database`
- Nhập và tạo Seeder (dữ liệu mẫu): Sản phẩm, danh mục, hình ảnh
- Hiển thị danh mục trang chủ
- Làm phần seeder product

### `---Code Customer side---`

- `Module`: Đăng ký, Profile khách hàng

### `---Kiểm thử---`

- Test toàn bộ chức năng website

## `5. Thành Phát - HTTT2211004`

### `---Tìm kiếm tài nguyên cho dự án---`

- Lấy Hình ảnh + Nội dung
- Nhập và tạo Seeder (dữ liệu mẫu): Sản phẩm, danh mục

### `---Thiết kế và làm mịn UI---`

- Cài đặt và tạo UI 404 not found: Khi truy cập ngoài route
- Duyệt và cài đặt modal slider trang chủ
- Hiện ra các sản phẩm liên quan và sản phẩm được bán chạy nhất
- Cài đặt phần duyệt sản phẩm bằng tag không load lại trang
- Thêm nút facebook
- Fix lỗi: Active và Hover của danh mục

## Như Ý note

1. Cài đặt môi trường

- Cài đặt Laragon.
- Tìm và chọn template thích hợp cho dự án.
- Tạo 1 thư mục mới. Nếu dự án được Clone từ GitHub thì chuyển dự án đến thư mục vừa tạo.
- Mở thư mục dự án trong VS Code, chạy lệnh: cmd -> code

2. Cài đặt cơ sở dữ liệu

- Mở Laragon. Chọn Start All, các dịch vụ Apache, MySQL, PHP sẽ được khởi động. Trên thanh công cụ chọn Database -> Open để truy cập vào phpMyAdmin.
- Tạo cơ sở dữ liệu mới: Database -> create new -> Đặt tên database giống tên trên file .env

3. Kết nối cơ sở dữ liệu:

- Cài đặt môi trường: copy file .env.example -> .env
- Trong file .env cập nhật các thông tin để kết nối cơ sở dữ liệu:
    DB_HOST: 127.0.0.1
    DB_PORT: 3306
    DB_DATABASE:clapshop ( Tên database đã tạo )
    DB_USERNAME: root ( Tên người dùng mặc định của MySQL (root) )
    DB_PASSWORD: ( Mật khẩu để trống nếu dùng Laragon mặc định )

- Trong VS Code , mở terminal -> Git Bash. Chạy các lệnh:

- php artisan migrate hoặc php artisan migrate:fresh ( Tạo bảng )
- php artisan make:seender ( Tạo seender )
- php artisan db:seed ( Chèn dữ liệu mẫu vào cơ sở dữ liệu )

4. Cài đặt các phụ thuộc

- Cài đặt Composer-Setup.exe
- Trong VS Code, mở Terminal -> Git Bash
- Cài đặt dependencies -> chạy lệnh: Composer install

5. Chạy dịch vụ:

- Chạy lệnh: php artisan serve

## Tại sao cần CSRF?

- CSRF (Cross-Site Request Forgery) là một loại tấn công mà hacker lợi dụng người dùng đã đăng nhập vào hệ thống, sau đó tự động gửi yêu cầu đến server của bạn mà người dùng không biết. Hacker có thể thực hiện các hành động trái phép (như xóa tài khoản, chuyển tiền, v.v.).

- Laravel bảo vệ bạn khỏi loại tấn công này bằng cách sử dụng CSRF token. Token này là một chuỗi duy nhất được tạo cho mỗi phiên người dùng và chỉ hợp lệ với người dùng đó. Khi thực hiện các yêu cầu như POST, PUT, DELETE, Laravel kiểm tra token này để đảm bảo rằng yêu cầu đến từ một trang hợp lệ và không phải từ hacker.

- Do đó, khi gửi các yêu cầu thay đổi dữ liệu như DELETE hay POST, bạn cần gửi kèm CSRF token để đảm bảo tính bảo mật.

## Configuration

- BS4 - V4.1.1

### `Load file auto in lavarel`

```bash
  composer dump-autoload

## Kế sách cuối cùng - `Đạt`

## Bước 1
composer update
composer install

## Bước 2
php artisan config:clear

php artisan cache:clear

php artisan config:cache

php artisan route:clear

php artisan view:clear

```

### Note's Nguyên kĩ thuật `symbolic link` để thêm link cho nơi lưu trữ file

php artisan storage:link
