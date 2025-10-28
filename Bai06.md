**Tên:**

Đặt hàng

**Actor:**

Khách hàng (Primary)

Hệ thống giao đồ ăn (Secondary)

Nhà hàng (Secondary)

**Mục tiêu:**

Khách hàng thực hiện đặt món ăn từ nhà hàng thông qua ứng dụng để được giao đến địa chỉ mong muốn.

**Luồng chính:**

Khách hàng đăng nhập vào ứng dụng.

Khách hàng tìm kiếm và chọn món ăn từ danh sách nhà hàng.

Hệ thống hiển thị chi tiết món ăn và giá.

Khách hàng thêm món ăn vào giỏ hàng.

Khách hàng kiểm tra giỏ hàng và nhấn “Đặt hàng”.

Hệ thống yêu cầu xác nhận địa chỉ giao hàng và phương thức thanh toán.

Khách hàng xác nhận đặt hàng.

Hệ thống gửi đơn hàng đến nhà hàng.

Nhà hàng xác nhận đơn và bắt đầu chuẩn bị món.

Hệ thống cập nhật trạng thái đơn hàng cho khách hàng.

**Luồng lỗi:**

Lỗi 1: Hệ thống không kết nối được đến máy chủ → thông báo “Không thể đặt hàng lúc này, vui lòng thử lại sau.”

Lỗi 2: Nhà hàng hết món → thông báo “Món ăn bạn chọn hiện đã hết hàng.”

Lỗi 3: Thanh toán thất bại → hiển thị thông báo và yêu cầu chọn lại phương thức thanh toán khác.
