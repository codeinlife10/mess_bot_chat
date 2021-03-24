1. Install FLask - micro web framework hỗ trợ các thành phần tiện ích mở rộng cho ứng dụng như tích hợp cơ sở dữ liệu, xác thực biểu mẫu,xử lý upload, các công nghệ xác thực, template, email, RESTful...
pip install Flask
2. Use PyMessenger lib để tương tác giữa người dùng và bot  
pip install pymessenger
3. Đi tới https://developers.facebook.com/ để tạo nick cho facebook dev 
4. Tạo ứng dụng mới -> Chọn Quản lí tiện ích -> Messenger
5. Messenger Settings
6. Thêm page facebook 
7. Thay ACCESSS_TOKEN 
8. VERIFY_TOKEN là 1 string bất kì bạn sử dụng để authenticate
9. Tạo đường dẫn URL callback bằng heroku để chạy public 
    9.1. pip freeze > requirements.txt
    9.2. tạo file Procfile(optinal for greater control and flexibility)
    9.3. runtime.txt chứa python-(your--version)
