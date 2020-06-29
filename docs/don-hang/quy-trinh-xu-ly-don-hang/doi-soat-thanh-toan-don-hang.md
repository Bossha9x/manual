# Đối soát và thanh toán đơn hàng
## Thanh toán COD
### 1. Thanh toán COD đơn hàng gửi qua Nhanh.vn
Với đơn hàng gửi qua hệ thống Nhanh.vn, trạng thái do các hãng vận chuyển cập nhật, thì việc đối soát đơn hàng sẽ do Nhanh thực hiện.

Khi đơn hàng giao Thành công hoặc Chuyển hoàn về, hãng vận chuyển đối soát với Nhanh.

Nhanh sẽ check các thông tin về khối lượng, tiền cần thu, cước vận chuyển (xem có phí vượt cân, có đúng với giá cước theo hợp đồng không) => Khớp các giá trị trên sẽ chốt đối soát với hãng vận chuyển, sau đó Nhanh sẽ chuyển lại tiền này cho doanh nghiệp.

Doanh nghiệp có thể kiểm tra danh sách các đơn hàng và số tiền đối soát [tại đây](https://new.nhanh.vn/order/payment/index).

![Giao diện làm việc của Đối soát COD](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/don-hang/img/doi-soat-%20don-hang%20-1.png)

- Đã thanh toán: Các khoản đối soát từ Nhanh thanh toán cho doanh nghiệp theo ngày, lịch đối soát doanh nghiệp vui lòng tham khảo [tại đây](https://nhanh.vn/huong-dan-van-chuyen). Doanh nghiệp có thể click vào chi tiết từng đợt thanh toán để kiểm tra các đơn hàng được đối soát trong lần đó.

- Đơn hàng đã thanh toán: Thông tin các đơn hàng đã được đối soát từ Nhanh bao gồm: ID đơn hàng, hãng vận chuyển, trạng thái đơn hàng, cước vận chuyển, chi phí phát sinh, tổng thanh toán đơn hàng.

Khi nhận được khoản đối soát từ Nhanh, doanh nghiệp kiểm tra thông tin đợt đối soát, khoản tiền đối soát, danh sách đơn hàng được đối soát, sau đó ấn nút “Xác nhận” để xác nhận đã nhận được tiền đối soát.

Với doanh nghiệp sử dụng module Kế toán, sau khi doanh nghiệp ấn nút “Xác nhận”, hệ thống sẽ tự sinh các bút toán đối soát cho đơn hàng, chi tiết về hạch toán đơn hàng tự động doanh nghiệp vui lòng tham khảo [tại đây](link).

### 2. Đối với đơn hàng gửi qua hãng Ahmove
Đơn gửi hãng Ahamove khi giao đơn cho shipper thì doanh nghiệp đã được bên hãng vận chuyển trả tiền cho giá trị đơn hàng cộng với phí thu của khách trạng thái do các hãng vận chuyển cập nhật.

Đối với doanh nghiệp dùng tính năng kế toán khi đơn hàng thành công cần thao tác tạo phiếu thu cho đơn hàng.

Tham khảo hướng dẫn [tại đây](link).

Đối với doanh nghiệp không dùng tính năng kế toán không cần tạo thêm thao tác gì.

## II. Đối soát tự vận chuyển 
**Thanh toán đối soát đơn tự vận chuyển**

Tình huống:

- Đơn hàng có giá trị 200.000 VNĐ

- Phí vận chuyển: 15.000 VNĐ

- Phí ship báo khách: 30.000 VNĐ

![](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/don-hang/img/doi-soat-don-hang-4.png)

Khi đơn hàng thành công, doanh nghiệp tự đổi trạng thái thành công cho đơn hàng.

Khi có file excel đối soát đơn hàng của hãng vận chuyển, doanh nghiệp làm đối soát đơn hàng cho các đơn trên Nhanh.vn như sau:

**Bước 1: Truy cập vào module Đơn hàng / Thao tác / Thêm đối soát đơn tự vận chuyển, hoặc truy cập [tại đây](https://new.nhanh.vn/order/manage/payment).**

![](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/don-hang/img/doi-soat-don-hang-7.png)

Hoặc anh/chị truy cập vào module đơn hàng/ Đối soát l Thanh toán/ Đối soát tự vận chuyển/ Thêm đối soát.

![](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/don-hang/img/doi-soat-don-hang-5.png)

![](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/don-hang/img/doi-soat-don-hang-6.png)

**Bước 2: Tải file import về rồi điền các thông tin, sau đó lưu file excel lại.**
- ID đơn hàng: ID trên Nhanh.vn của đơn hàng muốn đối soát.

- Phí vận chuyển: Cước phí vận chuyển mà hãng vận chuyển báo.

- Phí thu của khách: Phí vận chuyển mà khách phải chịu.

- Tổng thu: Tổng tiền thu của người nhận hàng.

![](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/don-hang/img/doi-soat-don-hang-8.png)

**Bước 3: Chọn tài khoản nhận tiền (với doanh nghiệp dùng kế toán), ngày đối soát, và điền ghi chú (nếu có).**

**Bước 4: Tải file Import đã nhập liệu lên hệ thống và theo dõi tiến độ import đến khi đạt 100%.**

Sau khi upload thành công (hay thất bại) hệ thống sẽ thông báo tới doanh nghiệp. Trường hợp thành công, doanh nghiệp kiểm tra lại chi tiết đối soát vừa Import tại Đối soát tự vận chuyển [tại đây](https://new.nhanh.vn/order/manage/payment).

Các bút toán hệ thống sẽ tự sinh sau khi import file đối soát, doanh nghiệp tham khảo [Tại đây](link).

Khi đơn hàng Thành công: Hệ thống tự tạo các hạch toán:

- Phiếu xuất ghi nhận giá vốn của sản phẩm - hạch toán Nợ 632, Có 1561, gắn theo chứng từ ID phiếu Xuất giao hàng.

- Phiếu bán hàng ghi nhận giá trị của đơn hàng (hiện chưa bao gồm phí thu của khách) là 200.000 - hạch toán Nợ 131, Có 5111, gắn theo chứng từ ID phiếu Xuất giao hàng.

Khi đối soát đơn hàng: Hệ thống tự tạo các hạch toán:

- Phiếu thu Nợ 131, Có 711 = Phí thu của khách (phí vận chuyển doanh nghiệp sẽ tính theo khách hàng), gắn theo ID chứng từ đơn hàng, đối tượng là khách hàng.

=> Công nợ khách hàng = Giá trị đơn hàng + phí thu của khách = 200.000 + 30.000 = 230.000

- Phiếu Báo có (Nộp tiền) hạch toán tiền khách thanh toán: Nợ 1121, Có 131 = Số tiền cần thanh toán còn lại của khách hàng (230.000), gắn theo ID chứng từ đơn hàng và đối tượng là khách hàng.

- Phiếu Báo nợ (Rút tiền) hạch toán chi tiền thanh toán phí vận chuyển: Nợ 811, Có 1121 = Số tiền doanh nghiệp thanh toán tiền vận chuyển, không gắn đối tượng.

## III. Chiếu khấu cước
Với các đơn hàng gửi qua Nhanh, doanh nghiệp được hưởng chiết khấu theo quy định tại quy định [tại đây](link).

Tại đây doanh nghiệp sẽ kiểm tra được thông tin các khoản chiết khấu theo từng tháng:

- Tổng số đơn: Tổng đơn doanh nghiệp đã gửi qua Nhanh trong tháng, bao gồm tất cả các hãng vận chuyển đang kết nối với Nhanh

- % chiết khấu: tỉ lệ chiết khấu theo quy định của từng hãng vận chuyển

- Số tiền được chiết khẩu: tổng số tiền doanh nghiệp được chiết khấu trong đợt này
