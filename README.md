# practice_php_cakephp_congdv_202002
Bài tập thực hành về CakePHP - Quản lý shop bán hàng - CongDV - 202002

## Môi trường phát triển
- PHP 7.3
- CakePHP 3.+
- DB MYSQL 5.7 trở lên

## Nội dung

### Login
	Nhập thông tin user/password để thực hiện đăng nhập
	Password mã hóa MD5
### Đăng ký user
	Cần validate các trường user là duy nhất, địa chỉ email phải hợp lệ, số điện thoại chỉ được nhập số
### Lấy lại mật khẩu
	Tự động tạo mật khẩu mới rồi gửi mail thông tin mật khẩu
### Thay đổi thông tin cá nhân
	Chỉ được thay đổi thông tin của cá nhân
### Danh sách user
	Chỉ có thủ thư và admin có chức năng này
### Sửa thông tin cá nhân
	Admin có quyền đóng user, thay đổi thông tin số điện thoại, mật khẩu, địa chỉ của user thông thường, không được quyền thay đổi role của user
	Admin có thể thay đổi thông tin số điện thoại, mật khẩu, địa chỉ, role của tất cả các user, có quyền đóng user


### Danh mục sản phẩm
	Admin có quyền thực hiện
### Thêm danh mục sản phẩm
	Admin có quyền thực hiện
### Sửa danh mục sản phẩm
	Admin có quyền thực hiện
### Xóa danh mục sản phẩm
	Admin có quyền thực hiện
	Trường hợp thể loại sách đang có sách thì không được xóa

### Danh sách sản phẩm
	Tất cả mọi user đều có quyền
### Thêm sản phẩm, sửa sản phẩm, xóa sản phẩm
	Admin có quyền thực hiện
### Xem nội dung sản phẩm
	Tất cả mọi user đều có quyền


### Danh sách order
	Tất cả mọi user đều có quyền
### Xem nội dung order
	Tất cả mọi user đều có quyền

### Order sản phẩm
	Tất cả mọi người dùng đều có quyền mua sản phẩm, tuy nhiên cần kiểm tra sản phẩm có còn hay không?
	Sản phẩm được chọn mua sẽ nằm trong giỏ hàng để người dùng có thể xác nhận lại thông tin sản phẩm muốn mua.
	Người dùng cần nhập thông tin cá nhân như: Họ, tên, sđt, địa chỉ giao hàng, email... trước khi hoàn thành đơn hàng
	Khi đơn hàng được đặt hàng thành công thì hệ thống gửi mail tới địa chỉ email của người dùng và email của admin
### Duyệt đơn hàng
	Khi có đơn hàng mới thì cần được nhân viên bán hàng xác nhận trước khi hàng được giao
	Chỉ nhân viên bán hàng có quyền duyệt đơn hàng, có thể thực hiện duyệt hoặc từ chối đơn hàng, trường hợp duyệt, thì số lượng của sản phẩm phải trừ đi bằng số lượng được mua trong order.

## Tham khảo
	Book: https://book.cakephp.org/
	Coding convention: https://www.php-fig.org/psr/