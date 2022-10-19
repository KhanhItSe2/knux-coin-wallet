Hướng dẫn khởi chạy:
	1. Mở cmd trong folder đã nộp.
	2. Gõ npm install
	3. Gõ npm start
	4. Mở browser và truy cập URL: "http://localhost:8080/"

Import data:	
	- Sau khi khởi chạy trang web sẽ tự tạo database trong MongoDB Compass
	- Gắn URI: "mongodb://0.0.0.0:27017/knux-coin" vào khung New Connection -> Connect
	- Sẽ có DBS là knux-coin: accounts(tài khoản), transactions(lịch sử giao dịch), users (profile user)
	- Vào từng collection và import tương ứng tên file trong folder 'database' để cập nhật dữ liệu

Thông tin đăng nhập: 

Admin:
	Tài khoản: admin 
	Mật khẩu: 123456

Người dùng:
	User 1 - approved (đã xác minh) 
		Tài khoản: 1645164248
		Mật khẩu: 123456 

	User 3 - approved (đã xác minh)
		Tài khoản: 7916232825 
		Mật khẩu: 123456 
	
	User 6 - unapproved (chưa xác minh)
		Tài khoản: 1538643355 
		Mật khẩu: 123456 

	User 2 - locked (bị khóa do đăng nhập sai nhiều lần)
		Tài khoản: 6544558237 
		Mật khẩu: 123456 

	User 5  - disabled (bị vô hiệu hóa)
		Tài khoản: 9615864202 
		Mật khẩu: 123456

	User 7 - waiting (yêu cầu cập nhật CMND)
		Tài khoản: 14179983  
		Mật khẩu: 123456 
	