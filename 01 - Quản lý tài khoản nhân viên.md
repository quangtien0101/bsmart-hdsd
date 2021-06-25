Nội dung:
- [[#Tạo tài khoản|Tạo tài khoản]]
	- [[#Cách 1: Tạo tài khoản qua giao diện Contacts/Employees|Cách 1: Tạo tài khoản qua giao diện Contacts/Employees]]
		- [[#Danh sách các phân quyền cần thiết cho nhân viên Admin|Danh sách các phân quyền cần thiết cho nhân viên Admin]]
		- [[#Danh sách các phân quyền cần thiết cho nhân viên bình thường|Danh sách các phân quyền cần thiết cho nhân viên bình thường]]
	- [[#Cách 2: Tạo tài khoản qua Settings|Cách 2: Tạo tài khoản qua Settings]]
		- [[#Tạo tài khoản Admin|Tạo tài khoản Admin]]
		- [[#Tạo tài khoản nhân viên bán hàng|Tạo tài khoản nhân viên bán hàng]]
		- [[#Liên kết tài khoản tạo với module Bsmart|Liên kết tài khoản tạo với module Bsmart]]

## Tạo tài khoản
*Yêu cầu: tài khoản thực hiện phải được cấp đủ quyền admin của module và các quyền cùa settings *

### Cách 1: Tạo tài khoản qua giao diện Contacts/Employees


Nhấn vào module `bsmart` --> Chọn thẻ `Contacts` --> Chọn `Employees`
![](Screen-shot/Truy%20cập%20giao%20diện%20employee.png)

Click vào nút `Tạo` để truy cập giao diện tạo tài khoản
![](Screen-shot/Giao%20diện%20tạo%20tài%20khoản%20nhân%20viên.png)

Các trường thông tin:
- `Tên` - bắt buộc: là tên hiển thị của nhân viên

- `Đăng nhập` - bắt buộc: là tên đăng nhập của nhân viên, có thể sử dụng email ở field này

- `Already existed`: dùng trong trường hợp liên kết 1 tài khoản sẵn có trên hệ thống để biến người đó thành nhân viên

- `Belonged saleteam`: dùng để thêm danh sách các sale team mà nhân viên đó thuộc về   

- `Email`: email của nhân viên, nhập đúng email nhân viên để họ có thể nhận được mail đăng nhập/cài mật khẩu

- `Nhóm` - bắt buộc: đây là danh sách các phân quyền của nhân viên

- `Allowed companies` - bắt buộc: danh sách các công ty/bộ phận mà nhân viên đó thuộc về (lưu ý: người thực hiện chỉ có thể thêm những công ty thuộc về danh sách `allowed companies` của mình)

- `Default company` - bắt buộc: trong trường hợp nhân viên thuộc về nhiều công ty/bộ phận khác nhau, khi đăng nhập vào họ sẽ mặc định thấy các khách hàng/cơ hội thuộc về `company` đó

#### Danh sách các phân quyền cần thiết cho nhân viên Admin
Nhấn vào nút `Thêm một dòng` ở `Nhóm`, sau đó thêm những quyền sau bằng cách đánh dấu vào các ô ở đầu dòng tương ứng
 
- `Bsmart Management / Admin`
- `Bán hàng / Người quản trị`
- `Loại người dùng / Người sử dụng nội bộ`
- `Quản trị / Thiết lập`
- `Quyền bổ sung / Đa công ty`
- `Email Marketing / Người dùng`

![](Screen-shot/Danh%20sách%20phân%20quyền.png)
Các quyền trên sẽ cho nhân viên khả năng truy cập vào tùy chỉnh của hệ thống. Tạo, sửa, xóa các tài khoản khác. Điều chỉnh email templates, ...

#### Danh sách các phân quyền cần thiết cho nhân viên bình thường
Nhấn vào nút `Thêm một dòng` ở `Nhóm`, sau đó thêm những quyền sau bằng cách đánh dấu vào các ô ở đầu dòng tương ứng
 
- `Bsmart Management / Saleperson`
- `Bán hàng / Người dùng: Tất cả tài liệu`
- `Loại người dùng / Người sử dụng nội bộ`
- `Quyền bổ sung / Đa công ty`
- `Email Marketing / Người dùng`

![](Screen-shot/Phân%20quyền%20tài%20khoản%20thường.png)
Những phân quyền này cho phép nhân viên truy cập và sửa các khách hàng/cơ hội trong cùng 1 công ty/bộ phận, sử dụng chiến dịch gửi email, ...

### Cách 2: Tạo tài khoản qua Settings
Nhấn vào module `Settings`, chọn `manage users`

![](Screen-shot/Truy%20cập%20quản%20lý%20user.png)

Nhấn vào nút `Tạo` để truy cập vào giao diện tạo tài khoản

![](Screen-shot/Giao%20diện%20tạo%20tài%20khoản%20Odoo.png)
Các trường thông tin:
- `Tên` - bắt buộc: là tên hiển thị của nhân viên

- `Email`: email của nhân viên, nhập đúng email nhân viên để họ có thể nhận được mail đăng nhập/cài mật khẩu

- `Công ty dược phép` - bắt buộc: danh sách các công ty/bộ phận mà nhân viên đó thuộc về (lưu ý: người thực hiện chỉ có thể thêm những công ty thuộc về danh sách `Công ty được phép` của mình)

- `Công ty mặc định` - bắt buộc: trong trường hợp nhân viên thuộc về nhiều công ty/bộ phận khác nhau, khi đăng nhập vào họ sẽ mặc định thấy các khách hàng/cơ hội thuộc về `company` đó

- `Loại người dùng`: luôn chọn `Người sử dụng nội bộ`
- `Bán hàng`: quyền truy cập về quản lý cơ hội, khách hàng
- `Marketing`: quyền truy cập về quản lý và sử dụng email marketing
- `Quản trị`: quyền dành cho admin, dùng để xem hoặc điều chỉnh các settings và user khác
- `Khác` - `Bsmart Management`: quyền truy cập và tùy chỉnh dành cho user ở module bsmart

#### Tạo tài khoản Admin
*Lưu ý: điều chỉnh Công ty/bộ phận (số 1, số 2) phù hợp với nhân viên*
![](Screen-shot/Tài%20khoản%20Admin.png)

#### Tạo tài khoản nhân viên bán hàng
*Lưu ý: điều chỉnh Công ty/bộ phận (số 1, số 2) phù hợp với nhân viên*
![](Screen-shot/Tài%20khoản%20nhân%20viên.png)

#### Liên kết tài khoản tạo với module Bsmart
Nhấn vào module `bsmart` --> Chọn thẻ `Contacts` --> Chọn `Employees` --> chọn `Tạo` (Giống ở [Cách 1](01%20-%20Quản%20lý%20tài%20khoản%20nhân%20viên.md#Cách%201%20Tạo%20tài%20khoản%20qua%20giao%20diện%20Contacts%20Employees))

Sau đó, chọn vào ô `already existed`, lúc này nhấn vào `Related user` và chọn vào tài khoản muốn liên kết. Lúc này, các thông tin sẽ tự điền vào và tiếp theo ta nhấn `Lưu`

![](Screen-shot/Liên%20kết%20tài%20khoản.png)