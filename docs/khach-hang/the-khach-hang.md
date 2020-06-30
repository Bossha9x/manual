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

* Bạn  truy cập Khách hàng / Thẻ khách hàng / Tab Phát hành thẻ/ click [Thêm mới](https://nhanh.vn/customer/batch/index?tab=add). Có 2 cách thêm mới đợt phát hành thẻ khách hàng:
1. Thêm trực tiếp: Nhập tên đợt phát hành thẻ, số lượng thẻ phát hành, click Lưu ==> Hệ thống tự động sinh mã thẻ
2. Import Excel: Chuyển sang tab Import hoặc truy cập vào đây, tải file mẫu về, nhập liệu, sau đó import lên hệ thống. ==> với cách này, hệ thống không tự sinh mã thẻ mà doanh nghiệp có thể tùy chỉnh được mã thẻ khách hàng theo ý muốn.

Sau khi thêm mới, các đợt phát hành thẻ sẽ xuất hiện tại Danh sách đợt phát hành thẻ khách hàng.


![](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/khach-hang/img/danh-sach-dot-phat-hanh-the-1.jpg)


Tình huống sử dụng thực tế:
- Doanh nghiệp Xuất Excel danh sách mã thẻ khách hàng trong 1 đợt, sau đó gửi file Excel cho bên in ấn để họ in thẻ.

## Gắn thông tin khách hàng

**Trường hợp 1:** Gắn khách vào thẻ trước, rồi gửi thẻ cho khách hàng
       
 - Tại Danh sách đợt phát hành thẻ, click vào số lượng mã thẻ
 
 
 ![](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/khach-hang/img/danh-sach-dot-phat-hanh-the-2-.jpg)


- Click nút ![](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/khach-hang/img/nut1.jpg) tại từng mã thẻ, chọn Thêm khách hàng. Sau đó nhập các thông tin cần thiết của khách hàng, click Lưu để hoàn tất thao tác.

**Trường hợp 2:** Gửi thẻ cho khách hàng trước, khách đến mua hàng thì gắn khách vào thẻ

- Khách đển mua hàng và đưa thẻ, nhân viên truy cập vào Khách hàng / Thẻ khách hàng / click Thêm mới, hoặc truy cập [tại đây](https://new.nhanh.vn/customer/code/addbycode)
- Nhân viên dùng đầu đọc mã vạch để quét mã thẻ, sau đó click Chuyển sang form nhập thông tin khách hàng. Lưu ý phải nhập/quét đúng mã thẻ thì mới có thể thao tác được tiếp.
- Nhập thông tin khách hàng, click Lưu để hoàn tất.

Sau khi gắn khách hàng vào thẻ, danh sách thẻ sẽ hiển thị đầy đủ thông tin khách hàng như sau:


![](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/khach-hang/img/thong-tin-the-khach-hang.jpg?token=AQAV53SJX5PZPA2TY7AHIXS66GJ6W)

## Đổi thẻ khách hàng

* Các tình huống có thể cần tới chức năng đổi thẻ:
  * Khách hàng làm mất thẻ
  * Nếu bạn in mỗi cấp độ khách hàng (VIP / Vàng / Bạc) một loại thẻ khác nhau, khi khách nâng hạng cần đổi thẻ.
* Các thao tác để đổi thẻ khách hàng:
  * Đang cập nhật
  
