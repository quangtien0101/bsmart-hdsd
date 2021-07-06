## Mục lục:
- [[#Cách sử dụng|Cách sử dụng]]
	- [[#Làm việc với biểu đồ|Làm việc với biểu đồ]]
	- [[#Làm việc với bảng tính|Làm việc với bảng tính]]
- [[#Kết|Kết]]

## Giao diện phần báo cáo

Để truy cập vào phần báo cáo, chọn module CRM --> `CRM` --> `Reporting Pipeline` 
![](Screen-shot/Select%20reporting.png)

Chú thích giao diện:
![](Screen-shot/Chú%20thích%20giao%20diện.png)

- **`1`**: Thước đo - Measures. Là những dữ liệu ta muốn thêm vào để xem trong phần báo cáo
- **`2`**: Các loại biểu đồ. Bao gồm những loại như **Đồ thị cột, Đồ thị đường, Biểu đồ dạng bánh**
- **`3`**: Bao gồm bộ lọc, nhóm theo, phạm vị thời gian, dùng để điều chỉnh dữ liệu được hiển thị trong phần báo cáo
- **`4`**: Các chế độ xem. Bao gồm Xem biểu đồ, Xem bảng tính, Xem dạng danh sách
- **`5`**: Phần dữ liệu được biểu diễn dựa trên các điều chỉnh của các phần `1`,`2`,`3`,`4`

## Cách sử dụng

### Làm việc với biểu đồ
*Lưu ý: Giống như khi quản lý các cơ hội, việc chọn ra pipeline đúng mục đích rất quan trọng vì nếu không, sẽ ảnh hưởng tới những con số thống kê. Vì thế hãy kiểm tra lại lựa chọn `Công Ty` trước khi thực hiện các hành động*
![](Screen-shot/multi%20companies%20selection.png)

Giả sử, chúng ta muốn có thống kê về số các cơ hội

Ở `Thước đo`, chọn `Số Bản ghi`
![](Screen-shot/Chọn%20số%20bản%20ghi.png)

Lúc này, chú ý tới biểu đồ hiện tại, trục tung biểu diễn `Số bản ghi`, còn trục hoàng biểu diễn `Level Hiện Tại`. Điều đó đồng nghĩa  với biểu đồ hiện tại đang biểu diễn "Số cơ hội tại các level khách nhau"

![](Screen-shot/analyze%20axis.png)

Ta có thể chuyển đổi đồ thị sang đồ thị hình bánh
![](Screen-shot/Pie%20chart.png)


>Với `Thước Đo`, ta có thể điều chỉnh giá trị **trục tung**, ta cũng có thể điều chỉnh giá trị **trục hoành** bằng cách sử dụng `nhóm theo` 

Giả sử chúng ta cần thống kê về số cơ hội của các nhân viên. Như vậy ta cần thay đổi tham chiếu của các cơ hội từ `level/giai đoạn` sang `nhân viên`.

Vào phần `Nhóm theo`, chọn `Nhân viên kinh doanh`. Lúc này biểu đồ chuyển từ "*Số cơ hội tại các level khách nhau*" thành "*Số cơ hội của các nhân viên khác nhau*"

![](Screen-shot/Nhân%20viên%20kinh%20doanh%20theo%20cơ%20hội.png)

Một bước xa hơn, giả sử ta muốn tìm "*Số cơ hội mới của mỗi nhân viên dựa theo các tháng vừa qua*". 
Lúc này, ta đang có sẵn số cơ hội dựa theo nhân viên. Cái ta cần là thêm 1 biến tham chiếu "thời gian" để ứng với số cơ hội.

Vào `Nhóm theo` --> Chọn thêm `Ngày Tạo` --> `Tháng`
![](Screen-shot/Nhóm%20theo%20ngày%20tạo.png)

Hiện tại, các cột biểu diễn tháng đang được xếp chồng với nhau. Để tách chúng ra chọn vào biểu tượng `Chồng` như hình ở dưới
![](Screen-shot/bỏ%20cột%20chồng.png)

Và cũng giống như khi làm việc với quản lý cơ hội, ta có thể lưu tất cả những điều chỉnh `Nhóm theo`, `Bộ Lọc`, `Thước Đo` vào phần `Yêu thích` để có thể tái sử dụng sau này một cách nhanh chóng

![](Screen-shot/yêu%20thích.png)

### Làm việc với bảng tính
Tuy phần biểu đồ cho chúng ta báo cáo một cách trực quan nhưng nó **không hỗ trợ** việc xuất file. Đó là lúc ta chuyển sang chế độ `xem bảng tính - View Pivot`.

![](Screen-shot/view%20pivot.png)

***Đặc biệt chú ý***, những tùy chỉnh ở phần `Thước đo` khi làm việc với `xem biểu đồ - view graph` không mang theo qua `xem bảng tính - view pivot`. Như ở hình trên, `Thước đo` đang được để ở `Doanh thu theo tỉ lệ`.

Vì vậy chỉnh lại phần `Thước đo` thành `Số bản ghi` và bỏ chọn `Doanh thu theo tỉ lệ`

![](Screen-shot/measurement%20fix.png)

Lúc này ta có thể loại bỏ đi các tháng ở dưới tên nhân viên vì nó thừa thãi bằng cách nhấn vào dấu `-` ở đầu tên của mỗi nhân viên.
![](Screen-shot/trim%20down.png)
Sau cùng khi bảng tính đã gọn, chọn vào biểu tượng `Tải xuống xls` để xuất bảng tính này về máy tính 
![](Screen-shot/Export%20report.png)

## Kết 
Làm việc với phần báo cáo đòi hỏi người thực hiện cần một chút luyện tập vì đây là một công cụ rất đa năng nhưng cũng khá khó sử dụng. Dẫu vậy, hi vọng phần hướng dẫn trên với việc sử dụng một ví dụ cụ thể giúp ích cho người đọc trong việc thành thạo phần báo cáo này.