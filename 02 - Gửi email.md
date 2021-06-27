## Mục lục
- [[#Chọn đối tượng người nhận|Chọn đối tượng người nhận]]
- [[#Lọc danh sách người nhận|Lọc danh sách người nhận]]
- [[#Tạo và quản lý Mailing Contact - Danh sách liên hệ mail|Tạo và quản lý Mailing Contact - Danh sách liên hệ mail]]
	- [[#Cách 1: Tạo từ giao diện mailings|Cách 1: Tạo từ giao diện mailings]]
	- [[#Cách 2: Tạo từ giao diện CRM|Cách 2: Tạo từ giao diện CRM]]
- [[#Tạo và quản lý Mailing list - danh sách gửi mail|Tạo và quản lý Mailing list - danh sách gửi mail]]
- [[#Tạo và quản lý Email templates|Tạo và quản lý Email templates]]


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
![](Screen-shot/Convert%20to%20mail%20contacts.png)

![](Screen-shot/Conver%20emails%20contacts.png)

Tại đây, chúng ta có thể thêm các Mailing List - danh sách gửi mail, mà chúng ta muốn các bản ghi này được thêm vào. Hoặc có thể để trống và chỉ chuyển đổi thông tin các cơ hội này thành những `Mailing contacts`

Nhấn `Convert`

Hoặc trong trường hợp ta chỉ cần convert 1 cơ hội duy nhất, ta có thể nhấn vào thẻ Kanban của cơ hội đó và nhấn `Convert lead to email contact`
![](Screen-shot/Convert%20lead%20to%20email%20contact.png)
## Tạo và quản lý Mailing list - danh sách gửi mail
Chọn `Mailing` --> Chọn `Mailing list`
![](Screen-shot/Giao%20diện%20mailing%20list.png)

Mailing lists là các danh sách chứa các liên hệ (`mailing contact`), Một `Mailing list` bao gồm tên của mailing list đó và danh sách 
![](Screen-shot/Mailing%20lists.png)

Nhấn vào `Tạo`, sau đó nhập tên của Mailing list vào. Chọn `Tạo` để hoàn tất.

![](Screen-shot/Tạo%20mailing%20list.png)

Lúc này mailing list này vẫn chưa có bất kì `Mailing contacts` nào, vì vậy để thêm vào, ta quay lại phần `Mailing list contacts`, chọn vào bản ghi mong muốn, và thêm mailing list vừa tạo vào phần `Danh sách mailing`, sau đó nhấn Lưu.

![](Screen-shot/Danh%20sách%20email%20khong%20có%20contact.png)
![](Screen-shot/Chọn%20bản%20ghi%20để%20thêm%20vào.png)
![](Screen-shot/Thêm%20danh%20sách%20mailing.png)
![](Screen-shot/Danh%20sách%20mailing%20được%20cập%20nhật.png)

Như vậy ta vừa cập nhật thêm 1 bản ghi cho mailing list (danh sách mail) "Danh sách người nhận mail". Xem cách thêm nhiều bản ghi vào trong mailing list ở phần [tạo mailing contacts từ giao diện CRM](02%20-%20Gửi%20email.md#Cách%202%20Tạo%20từ%20giao%20diện%20CRM)  

## Tạo và quản lý Email templates
*Yêu cầu: tài khoản thực hiện hành động phải là tài khoản có các quyền Admin về Settings**

Đầu tiên ta cần phải bật "Developers mode" - Chế độ phát triển

Chọn module `Thiết lập`, sau đó kéo xuống đến khi thấy phần `Developer Tools`. Sau đó nhấn `Kích họat chế độ phát triển`.
![](Screen-shot/Bật%20developer%20mode.png)

Sau đó, nếu thành công, ta sẽ thấy biểu tượng có hình con bọ hiện ra ở thanh navigation
![](Screen-shot/Developer%20mode%20được%20bật.png)

Tiếp theo, vẫn ở module `Thiết lập`, chọn `Kỹ thuật`, ở trong mục `Emails`, chọn `các mẫu`.

![](Screen-shot/Truy%20cập%20email%20templates.png)

Sau đó chọn `Tạo`, và chúng ta sẽ có giao diện của phần tạo email template

![](Screen-shot/Email%20template.png)

Chú thích giao diện:
- **`1`**: Tên của template

- **`2`**: Model/Đối tượng mà template này áp dụng lên (ví dụ: `Cơ hội`, `Liên Hệ`, ...)

- **`3`**: Nội dung email template, bao gồm Subject và Body

- **`4`**: Cấu hình thư điện tử, sử dụng để cấu hình các thông tin như email người gửi, email người nhận, email CC, ...
![](Screen-shot/Cấu%20hình%20thư.png)

- **`5`**: Thiết lập nâng cao, thông thường chúng ta chỉ sử dụng nó nếu như ta cần cân bằng tải cho nhiều mail server. Còn nếu không, ta có thể không quan tâm tới điều chỉnh này

- **`6`**: Bộ tạo placehodler động, đây là công cụ để cá nhân hóa email. Sau khi chọn `Áp dụng cho`, thì ta có thể chọn trường thông tin cần thiết để lấy biến placeholder, sau đó ghi vào trong mail body
![](Screen-shot/Placeholder.png)

Ở hình dưới là ví dụ về cách sử dụng place holder trong mail body
![](Screen-shot/Mail%20body.png)