# Thẻ khách hàng

* Thẻ khách hàng (hay còn gọi là Loyalty Card, VIP Card, Member Card...) là công cụ để định danh thông tin khách hàng.
* Thẻ khách hàng gồm 2 thông tin chính, là mã thẻ và thông tin khách hàng. Một thẻ được gắn với một khách hàng cụ thể.
* Mã thẻ giúp tìm kiếm khách hàng nhanh hơn, thông tin trên thẻ cũng giúp khách hàng thường xuyên nhớ tới thương hiệu của bạn hơn.

![Thẻ khách hàng của MediaMart - nguồn: Internet](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/khach-hang/img/the-khach-hang-01a.jpg)

Tình huống sử dụng thực tế:

* Phát hành thẻ: Tạo mã thẻ và in thẻ khách hàng.
* Khi khách có nhu cầu làm thẻ khách hàng, cửa hàng đưa cho khách 1 mã thẻ, xin thông tin khách hàng, và nhập thông tin khách hàng cho thẻ.
* Khi khách tới mua hàng, thu ngân xin thông tin thẻ khách hàng, và có thể dùng đầu đọc mã vạch hoặc tự gõ vào ô mã thẻ trên các trang thêm hóa đơn bán lẻ, thêm đơn hàng... để tìm kiếm thông tin khách hàng, hệ thống sẽ hiện ra đầy đủ thông tin của khách hàng trên các trang đang được thao tác (Họ tên, ngày sinh, cấp độ/nhóm khách hàng, số điểm tích lũy, có đang được áp dụng khuyến mại nào không...)

## Phát hành thẻ

* Bạn truy cập Khách hàng / Thẻ khách hàng / Tab Phát hành thẻ/ [Thêm mới](https://nhanh.vn/customer/batch/index?tab=add). Có 2 cách thêm mới đợt phát hành thẻ khách hàng:
1. Thêm trực tiếp: Nhập tên đợt phát hành thẻ, số lượng thẻ phát hành ==> Hệ thống tự động sinh mã thẻ
2. Import Excel: Chuyển sang tab Import hoặc truy cập vào đây, tải file mẫu về, nhập liệu, sau đó import lên hệ thống. ==> với cách này, hệ thống không tự sinh mã thẻ (Cấu trúc mã thẻ bạn có thể tùy chỉnh theo ý muốn)

Sau khi thêm mới, các đợt phát hành thẻ sẽ xuất hiện tại Danh sách đợt phát hành thẻ khách hàng.

![](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/khach-hang/img/phat-hanh-the-01a.jpg)

Sau khi tạo xong mã thẻ, bạn có thể:

- Gắn khách hàng vào thẻ, như vậy khi in thẻ có thể in luôn thông tin khách hàng trên thẻ, sau đó gửi thẻ cho khách hàng
- In thẻ luôn ==> trên thẻ sẽ không có thông tin khách hàng. In xong bạn gửi thẻ cho khách, khách đến mua hàng thì gắn khách vào thẻ.

## Gắn thông tin khách hàng

**Trường hợp 1:** Gắn khách vào thẻ trước, rồi gửi thẻ cho khách hàng
       
 - Tại Danh sách đợt phát hành thẻ, nhập chuột vào số lượng mã thẻ

 ![](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/khach-hang/img/phat-hanh-the-01b.jpg)

- Nhấn nút ![](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/khach-hang/img/nut1.jpg) tại từng mã thẻ, chọn Thêm khách hàng. Sau đó nhập các thông tin cần thiết của khách hàng.

**Trường hợp 2:** Gửi thẻ cho khách hàng trước, khách đến mua hàng thì gắn khách vào thẻ

- Khách đển mua hàng và đưa thẻ, nhân viên truy cập vào Khách hàng / Thẻ khách hàng / [Thêm mới](https://nhanh.vn/customer/code/addbycode)
- Nhân viên dùng đầu đọc mã vạch để quét mã thẻ, sau đó nhấn nút Chuyển sang form nhập thông tin khách hàng. Lưu ý phải nhập/quét đúng mã thẻ thì mới có thể thao tác được tiếp.
- Nhập thông tin khách hàng, nhấn Lưu để hoàn tất.

Sau khi gắn khách hàng vào thẻ, danh sách thẻ sẽ hiển thị đầy đủ thông tin khách hàng như sau:

![](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/khach-hang/img/phat-hanh-the-01c.jpg)

## Đổi thẻ khách hàng

* Các tình huống có thể cần tới chức năng đổi thẻ:
  * Khách hàng làm mất thẻ
  * Nếu bạn in mỗi cấp độ khách hàng (VIP / Vàng / Bạc) một loại thẻ khác nhau, khi khách nâng hạng cần đổi thẻ.
* Các thao tác để đổi thẻ khách hàng:
Bạn truy cập vào trang chi tiết khách hàng sau đó nhấn vào icon ![](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/img/but-chi.jpg) để đổi mã thẻ

![Đổi mã thẻ khách hàng](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/khach-hang/img/doi-the-khach-hang-1a.jpg)
  
