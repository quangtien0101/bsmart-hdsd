# Gửi email cho cơ hội thông qua giao diện CRM

Truy cập module `Bsmart` --> chọn `CRM` --> chọn `My Pipeline` --> Chọn vào biểu tượng List View

![](Screen-shot/List%20view%20cơ%20hội.png)

Sau đó sử dụng bộ lọc để chọn ra các cơ hội mong muốn, theo ví dụ ở dưới ta sẽ chọn ra những `cơ hội` đang thuộc `level 4`. Tiếp theo đánh dấu các cơ hội, nhấn vào `Hành động`, chọn `Gửi mail`

![](Screen-shot/Hành%20động%20gửi%20email.png)

Sau đó chúng ta sẽ có giao diện gửi email 
![](Screen-shot/Giao%20diện%20gửi%20email.png)
Chú thích giao diện:
- **`1`**: Địa chỉ người gửi
- **`2`**: Chủ đề (Subject) của email
- **`3` và `4`**: Nếu trong trường hợp chúng ta muốn email này thuộc về một chiến dịch gửi mail (`Email campaign`) thì nhập tên chiến dịch đó vào (số 3) và soạn tên của email để lưu trong chiến dịch (số 4).*** Còn nếu không, để trống***
- **`5`**: Nội dung email
- **`6`**: Trong trường hợp có sẵn email templates, lựa chọn template cần thiết và chỉnh sửa nội dung email nếu cần

# Gửi email thông qua giao diện Mailing

Truy cập module `Bsmart` --> chọn `Mailing` --> chọn `Mailing`

![](Screen-shot/Truy%20cập%20mailings.png)

Tại đây, ta có giao diện Kanban về các mailing và trạng thái của chúng
Nhấn vào nút `Tạo`, để vào giao diện tạo 1 mailing mới. Mailing cũng có thể được xem như một email, nhưng chỉ có các mailing mới có thể được xem và quản lý ở giao diện `Mailing` này

![](Screen-shot/Giao%20diện%20tạo%20maling.png)
Chú thích giao diện:
- **`1`**: Chủ đề (Subject) của email
- **`2`**: Đối tượng người nhận (xem thêm ở [Chọn đối tượng người nhận](#Chọn%20đối%20tượng%20người%20nhận))
- **`3`**: Danh sách người nhận đã qua bộ lọc (xem thêm ở [Lọc danh sách người nhận](02%20-%20Gửi%20email.md#Lọc%20danh%20sách%20người%20nhận))
- **`4`**: Trong trường hợp có sẵn email templates, lựa chọn template cần thiết và chỉnh sửa nội dung email nếu cần
- **`5`**: Nội dung email

Sau khi hoàn thành soạn thảo email
- Nhấn `Gửi` để server đưa email vào hàng chờ để xử lý gửi đi

- hoặc nhấn `Ấn định (thời gian)` để chọn ngày gửi, khi tới thời hạn, server sẽ đưa mailing này vào hàng chờ để xử lý gửi đi

- hoặc nhấn `Kiểm thử`, và nhập email nhận để kiểm tra tính khả dụng của mailing (gửi được, nội dung được bảo toàn, ...)
![](Screen-shot/Kiểm%20thử.png)

- Hoặc nhấn `Lưu` để lưu lại mailing này và gửi sau, những mailings này nằm ở cột Nháp
![](Screen-shot/Cột%20nháp.png)

## Chọn đối tượng người nhận
![](Screen-shot/Đối%20tượng%20người%20nhận.png)

Chúng ta có các đối tượng sau:
- `Danh bạ`: là bao gồm các bản ghi trong phần contacts (`Customer`, `Employees`, `Companies`)

- `Mailing Contact`: là bao gồm các bản ghi về người nhận được quản lý bởi `mailing` (xem thêm ở [Tạo và quản lý Mailing Contact](02%20-%20Gửi%20email.md#Tạo%20và%20quản%20lý%20Mailing%20Contact))

- `Tiềm năng/Cơ hội`: bao gồm các bản ghi ở trong `CRM` như cơ hội

- `Danh sách Mailing`: bao gồm các danh sách người nhận đã được tạo và quản lý bởi `Mailing` (xem thêm ở [Tạo và quản lý Mailing list](02%20-%20Gửi%20email.md#Tạo%20và%20quản%20lý%20Mailing%20list))

## Lọc danh sách người nhận
Sau khi nhấn vào nút hiện bản ghi, chúng ta giao diện list view cùng với bộ lọc. Như ví dụ dưới, chọn ra những bản ghi được tạo vào tháng 6

![](Screen-shot/Chọn%20records%20tạo%20vào%20tháng%206.png)
Sau khi nhấn `chọn`, trong trường hợp này, hãy chỉnh lại luật áp dụng cho các bộ lọc từ `Bất kì` thành `Tát Cả`.

![](Screen-shot/Chọn%20luật%20áp%20dụng.png)
Và như vậy ta đã thành công lọc danh sách người nhận xuống còn 3.

## Tạo và quản lý Mailing Contact - Danh sách liên hệ mail
Khái niệm `Mailing contact` dùng để lưu trữ các bản ghi chủ yếu để ***dễ dàng tái sử dụng cho việc gửi mailing sau này***. Bản ghi này chủ yếu lưu tên và email của một người.

### Cách 1: Tạo từ giao diện mailings
Chọn `Mailing` --> Chọn `Mailing List Contacts`
![](Screen-shot/Truy%20cập%20mailing%20list%20contacts.png)

Nhấn `Tạo`, sau đó chúng ta sẽ có giao diện thêm mailing contacts
![](Screen-shot/Giao%20diện%20mailing%20contacts.png)

Chú thích giao diện:
- **`1`**: Tên của bản ghi này
- **`2`**: Email của bản ghi
- **`3`**: Danh sách mailing, là danh sách các Mailing list mà bản ghi này thuộc về. Có thể để trống

Sau khi điền đủ thông tin cần thiết, nhấn `Lưu`

### Cách 2: Tạo từ giao diện CRM
Truy cập module `Bsmart` --> chọn `CRM` --> chọn `My Pipeline` --> Chọn vào biểu tượng List View

![](Screen-shot/List%20view%20cơ%20hội.png)

Sau đó sử dụng bộ lọc để chọn ra các `cơ hội` mong muốn. Nhấn vào `Hành động` --> `Convert to mail contacts`
![](Convert%20to%20mail%20contacts.png)

![](Pasted%20image%2020210625163248.png)

Tại đây, chúng ta có thể thêm các Mailing List - danh sách gửi mail, mà chúng ta muốn các bản ghi này được thêm vào. Hoặc có thể để trống và chỉ chuyển đổi thông tin các cơ hội này thành những `Mailing contacts`

Nhấn `Convert`

## Tạo và quản lý Mailing list - danh sách gửi mail


## Tạo và quản lý Email templates
