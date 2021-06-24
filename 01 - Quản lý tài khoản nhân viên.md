## Tạo tài khoản

### Cách 1: Tạo tài khoản qua giao diện Contacts/Employees

*Yêu cầu: tài khoản thực hiện phải được cấp đủ quyền admin của module và các quyền cùa settings *

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
![](Screen-shot/Truy%20cập%20quản%20lý%2s0user.png)