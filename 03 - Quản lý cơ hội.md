## Tạo cơ hội mới
Chọn module `bsmart CRM` --> `CRM` --> `My Pipeline`
![](Screen-shot/Truy%20cập%20CRM.png)

Lúc này ta sẽ có giao diện quản lý CRM.
![](Screen-shot/Pasted%20image%2020210629201224.png)

Chú thích giao diện:
- **`1`**: Danh sách các cơ hội được trình bày theo bảng Kanban hoặc dưới dạng danh sách

- **`2`**: Bộ lọc company. Bộ lọc này sẽ chọn theo danh sách `Allowed companies` (Xem thêm ở phần hướng dẫn [Tạo tài khoản](01%20-%20Quản%20lý%20tài%20khoản%20nhân%20viên.md#Cách%201%20Tạo%20tài%20khoản%20qua%20giao%20diện%20Contacts%20Employees))

- **`3`**: Thanh tìm kiếm và bộ lọc các cơ hội.    
### Cách 1: Tạo cơ hội thủ công
Nhấn vào nút `Tạo`, lúc này ta sẽ có giao diện tạo nhanh cơ hội
![](Screen-shot/Pasted%20image%2020210629205403.png)

Trường thông tin quan trọng nhất và bắt buộc ở đây là `Tên`, các trường thông tin còn lại có thể để trống nếu không cần thiết. Vì đây chỉ là giao diện tạo nhanh, nên nó không cung cấp cho ta chỉnh sửa các trường thông tin chi tiết khác.



Nhấn nút `Sửa` để có thể thêm các thông tin chi tiết khác qua giao diện đầy đủ của cơ hội hoặc nhấn `Thêm` để thêm luôn cơ hội này vào Level thấp nhất - `Level 1`.

Trong trường hợp ta chọn `Sửa`, sau khi hoàn thành nhập dữ liệu, chọn `Lưu`
![](Screen-shot/Giao%20diện%20cơ%20hội%20chi%20tiết.png)

Ở list view - xem dạng lưới, khi nhấn nút `Tạo`, ta sẽ vào thẳng giao diện chi tiết giống hình trên thay vì có giao diện tạo nhanh như ở bảng Kanban
![](Screen-shot/Giao%20diện%20list%20view.png)

### Cách 2: Import từ tập tin `.xlsx`

Chọn nút `Nhập` để bắt đầu quá trình nhập tập tin. Sau đó nhấn nút `Nạp tập tin` để chọn file từ máy tính. Lưu ý định dạng file phải là excel `.xls` hoặc `.xlsx`

![](Screen-shot/Import%20cơ%20hội.png)

Đảm bảo rằng `The first row contains the label of the column` được đánh dấu. Vì ở file nhập liệu chuẩn, dòng đầu tiên chứa tên của các trường thông tin thay vì dữ liệu.

Sau đó ghép các trường thông tin ứng với những cột tương ứng. Nếu như tên cột GIỐNG (không quan trọng viết hoa hay thường) với tên của một trường dữ liệu (data field), thì hệ thống sẽ tự động chọn trường dữ liệu cho cột đó.

***Lưu ý***: trường hợp mặc dù tên cột "khớp" với 1 trường thông tin nhất định mà hệ thống không tự nhận được
1. Kiểm tra khoảng trắng dư thừa ở tên cột. Xóa tất cả các khoảng trắng sau kí tự cuối
2. Kiểm tra lại "ngôn ngữ" ở `Tùy chỉnh cá nhân`, vì một số trường thông tin có chế độ song ngữ nên khi ở ngôn ngữ tiếng anh nó sẽ cố tìm tên cột giống với bản dịch tiếng anh đó thay vì bản dịch tiếng việt gốc 
3. Trong tường hợp hệ thống vẫn không tự nhận được, tiến hành chọn thủ công. Về sau hệ thống sẽ tự ghi nhớ tên cột đó ứng với trường thông tin bạn chọn ở những lần import excel sau này

Sau đó nhấn `Kiểm thử`, ta sẽ nhận được thông báo về những lỗi nếu có (dữ liệu không phù hợp, dữ liệu đã tồn tại ...)
Nếu nhận được thông báo `Mọi thứ dường như hợp lệ`. Tiến hành chọn `Nhập`.
![](Screen-shot/Test%20import.png)

Trong trường hợp ta muốn cập nhật file nhập, chọn `Nạp tập tin` và tải lên file mới.

## Chọn companies - công ty/bộ phận


## Lọc cơ hội - filter

## Nhóm các cơ hội - group by
