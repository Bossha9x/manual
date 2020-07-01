# Sản phẩm IMEI
IMEI (International Mobile Equipment Identity) là số nhận dạng thiết bị di động quốc tế, dùng để phân biệt từng thiết bị di động.

Không thể có hai thiết bị di động cùng mang một số IMEI, vì vậy sản phẩm IMEI là sản phẩm có tính chất đặc biệt, quá trình nhập liệu cho sản phẩm IMEI khác biệt so với sản phẩm thông thường. Sản phẩm IMEI được xây dựng theo một phương pháp quản lý riêng.

Các nghiệp vụ cần thực hiện khi doanh nghiệp kinh doanh sản phẩm IMEI như sau:

- Tạo sản phẩm IMEI
- Nhập IMEI
- Quản lý danh sách IMEI
- Theo dõi lịch sử IMEI
## Tình huống sử dụng
- Bạn kinh doanh điện thoại, nhập về 50 chiếc iPhone từ nhà cung cấp A
==> cần phải ghi lại IMEI từng máy - để tránh lẫn với Iphone nhập từ nhà cung cấp B với giá nhập khác

- Bán iPhone cho khách
==> cần phải ghi lại IMEI để check trong trường hợp khách đổi/trả/bảo hành có đúng máy do cửa hàng bán ra hay không, còn bảo hành hay không

- Giá bán 1 dòng điện thoại luôn có xu hướng ngày càng rẻ, giá nhập cũng ngày càng rẻ
==> cần ưu tiên những IMEI nhập trước bán trước, nhập sau bán sau (cần theo dõi lịch sử IMEI), tính giá vốn đích danh theo từng IMEI.
## Quy trình quản lý sản phẩm theo IMEI trên phần mềm Nhanh.vn
### Tạo sản phẩm IMEI
Tương tự như tạo sản phẩm thông thường trên, tuy nhiên ở trường Loại sản phẩm, bạn chọn Sảm phẩm IMEI.
Đặc biệt lưu ý: Với loại sản phẩm IMEI thì KHÔNG nhập số lượng khi tạo sản phẩm.
Số lượng sản phẩm sẽ tương ứng với số IMEI mà bạn nhập vào ở bước Nhập nhà cung cấp.
### Nhập IMEI
Nhập IMEI tại bước Nhập sản phẩm từ nhà cung cấp, quy trình như sau:
Nhập tên sản phẩm ==> nhập IMEI ==> mỗi IMEI tương ứng với số lượng là 1 sản phẩm

![](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/san-pham/img/sp-ynghia-imei-1.png)

Xem chi tiết hướng dẫn nhập sản phẩm từ nhà cung cấp tại [đây](https://manual.nhanh.vn/kho-hang/nhap-hang).
### Danh sách IMEI
Sau khi nhập IMEI lên phần mềm, bạn truy cập lần lượt vào Sản phẩm / IMEI / Danh sách IMEI, hoặc truy cập tại đây để quản lý các IMEI.
Giao diện làm việc của danh sách IMEI như sau:
Ảnh ![]()
#### *Bộ lọc: Cho phép bạn thực hiện thao tác lọc danh sách IMEI theo nhiều tiêu chí khác nhau

#### Thông tin trong Danh sách IMEI: *Có một số lưu ý:

* Trạng thái của IMEI được hệ thống tự động cập nhật theo các thao tác bán hàng, chuyển hàng, bảo hành...
* Kích hoạt IMEI dùng để đánh dấu là đã kích hoạt bảo hành trên hãng rồi, không dùng để tính ngày bắt đầu bảo hành.
* Trạng thái Kích hoạt giúp bạn phân biệt được các IMEI nào đã bán ra rồi + đã lên web của hãng kích hoạt rồi. Còn những IMEI bán rồi chưa kích hoạt thì cần làm thao tác này.
### Theo dõi lịch sử IMEI.
Bạn truy cập lần lượt  Sản phẩm / IMEI / Lịch sử IMEI hoặc truy cập tại [đây]()
Lịch sử IMEI là module cho phép bạn quản lý toàn bộ hành động đối với 1 sản phẩm được gắn 1 IMEI cụ thể.
**Ví dụ thực tế:**
- Khách hàng mang 1 chiếc iPhone đến bảo hành, sửa chữa, doanh nghiệp cần check xem IMEI đó nhập từ nhà cung cấp nào, giá bao nhiêu, còn bảo hành hay không, đã từng bảo hành/sửa chữa trước đó hay chưa, nếu rồi thì do máy bị lỗi gì...
Để truy cập module này, bạn lần lượt thao tác vào Sản phẩm / IMEI / Lịch sử IMEI, hoặc truy cập tại đây.
Giao diện làm việc của module này như sau:
Ảnh ![]()
**Bộ lọc** 
Bộ lọc cho phép bạn tìm kiếm các hành đồng với sản phẩm IMEI, với những tiêu chí sau:

* Từ ngày - Đến ngày: Lọc theo khoảng thời gian diễn ra hành động với sản phẩm IMEI.
* Doanh nghiệp: Cho phép chọn doanh nghiệp đang thao tác trên hệ thống.
* ID: Cho phép lọc theo ID của hành động với sản phẩm IMEI.
* ID sản phẩm: Cho phép lọc theo ID của sản phẩm được gắn IMEI.
* ID hóa đơn: Cho phép lọc theo ID của hóa đơn liên quan đến sản phẩm IMEI đó.
* Số IMEI: Cho phép lọc theo số IMEI.
* IMEI ID: Cho phép lọc theo ID của IMEI, mỗi IMEI sẽ được hệ thống gắn cho 1 ID nhất định.
* Loại: Cho phép lọc theo loại, bao gồm: Hóa đơn, Hóa đơn khách hàng .
* Hành động: Cho phép lọc theo hành động liên quan đến sản phẩm IMEI đó, bao gồm: Tạo mới, Nhân viên bán hàng lập phiếu, Bán hàng, Đổi IMEI trong hóa đơn...
**Bảng danh sách lịch sử IMEI** 
Bảng danh sách này cung cấp toàn bộ các hành động với sản phẩm IMEI. Bạn có thể click vào nút Hành động sau đó chọn xuất Excel bảng danh sách này để lưu trữ về máy tính.
Bảng danh sách bao gồm các cột:
* ID: Là ID của hành động với sản phẩm IMEI
* Hành động: Tên của hành động với sản phẩm IMEI
* Loại: Loại hành động với sản phẩm IMEI, kèm theo ID của loại hành động đó. Ví dụ: Hành động: Nhập nhà cung cấp; Loại: Hóa đơn (ID hóa đơn: 11078600)
* IMEI: Số IMEI của được gắn cho sản phẩm
* Mã sản phẩm, Sản phẩm: Là mã và tên của sản phẩm được gắn IMEI
* Nhà cung cấp, Nhân viên BH, Người tạo: Tên của nhà cung cấp, Nhân viên bán hàng và Người tạo hành động với sản phẩm IMEI đó.
