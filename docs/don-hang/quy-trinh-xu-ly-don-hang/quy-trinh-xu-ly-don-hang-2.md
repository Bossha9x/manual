# Quy trình xử lý đơn hàng

Quy trình xử lý đơn hàng của Nhanh.vn được mô tả theo sơ đồ sau:

![](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/don-hang/img/quy-trinh-xu-ly-DH-1.jpg)

## Thêm đơn hàng 
- Khách hàng đặt hàng trên website do Nhanh.vn cung cấp, hoặc website được tích hợp API của Nhanh, thì thông tin đơn hàng sẽ được chuyển đến phần mềm quản lý bán hàng Nhanh.vn.
- Khách đặt hàng tại các nguồn khác, nhân viên của cửa hàng sẽ kiểm tra tình trang sản phẩm còn tồn trong kho hay không. Nếu còn hàng, nhân viên sẽ nhập thông tin đơn hàng lên hệ thống. Trong cả 2 trường hợp đặt hàng trên website và từ nguồn khác, nếu hết hàng, nhân viên sẽ thông báo để khách hàng chọn sản phẩm khác. Xem thêm hướng dẫn sử dụng module Thêm đơn hàng [tại đây](https://manual.nhanh.vn/don-hang/quy-trinh-xu-ly-don-hang/them-don-hang).
- Ngoài ra, doanh nghiệp cũng có thể thêm nhanh nhiều đơn hàng cùng lúc với tính năng [Import đơn hàng](https://new.nhanh.vn/order/manage/import).
Những đơn hàng khi được tạo trên hệ thống sẽ có trạng thái là "Mới".

## Xác nhận đơn hàng

Sau khi có danh sách đơn hàng, nhân viên sẽ gọi điện cho khách hàng để xác nhận đơn hàng đó. Thao tác như sau:

- Tại danh sách đơn hàng, nhân viên bấm nút trạng thái đơn hàng "Mới", hệ thống sẽ chuyển đơn hàng sang trạng thái "Đang xác nhận". Do đó trong trường hợp có nhiều nhân viên cùng xác nhận đơn hàng thì cũng không thể xảy ra việc xác nhận trùng đơn hàng.
- Nếu khách hàng đồng ý lấy hàng, nhân viên sẽ chuyển trạng thái đơn hàng đó sang "Đã xác nhận". Có 2 tùy chọn là "Lưu" và "Lưu và in", nhân viên bấm nút "Lưu và In" thì đơn hàng đó sẽ tiếp tục chuyển sang trạng thái "Đang đóng gói sản phẩm".
- Nếu khách hàng không đồng ý lấy hàng, nhân viên chuyển trạng thái đơn hàng sang "Khách hủy" và lựa chọn lý do hủy đơn hàng.
- Doanh nghiệp có thể xem thêm hướng dẫn khâu xác nhận đơn hàng tại đây.

## In hàng và đóng gói

- Với những đơn hàng đang ở trạng thái "Đang đóng gói sản phẩm", nhân viên kho sẽ tiến hành nhặt hàng cho những đơn đó, đóng gói và dán phiểu gửi (đã in ở bước 2) vào đơn hàng.
- Với những đơn hàng ở trạng thái "Đã xác nhận", nhân viên cũng có thể bấm nút để in phiếu gửi (có thể chọn nhiều đơn hàng để in cùng lúc).
- Doanh nghiệp có thể xem thêm hướng dẫn khâu nhặt hàng và đóng gói [tại đây](https://manual.nhanh.vn/don-hang/quy-trinh-xu-ly-don-hang/in-va-dong-goi-don-hang).

## Cho đơn hàng vào biên bản bàn giao
- Doanh nghiệp phân loại các đơn hàng theo hãng vận chuyển, sau đó tạo biên bản bàn giao cho từng hãng. Xem hướng dẫn tạo biên bản bàn giao vận đơn [tại đây](https://manual.nhanh.vn/don-hang/quy-trinh-xu-ly-don-hang/bien-ban-ban-giao-don-hang-cho-hang-van-chuyen).

## Vận chuyển
- Sau khi đơn hàng đã được đóng gói và dán phiếu gửi thành công, nhân viên tiến hành gửi những đơn đó sang cho hãng vận chuyển. Doanh nghiệp có thể xem thêm hướng dẫn khâu vận chuyên [tại đây](link).
- Sau khi gửi đơn hàng sang hãng vận chuyển, bưu tá sẽ đến địa chỉ cửa hàng để lấy hàng và chuyển đi. Trong quá trình vận chuyển, doanh nghiệp có thể bấm nút vào đơn hàng để xem lịch trình chi tiết của đơn hàng.
- Nếu đơn hàng được chuyển thành công đến tay người nhận, đơn hàng được chuyển sang trạng thái "Thành công". Hệ thống tự động tạo phiếu xuất nhập kho và trừ số tồn của sản phẩm, cập nhật số tồn hiển thị trên web (đối với website do Nhanh cung cấp và website được tích hợp API của Nhanh), ghi nhận doanh thu cho doanh nghiệp. Với đơn hàng sử dụng hình thức giao hàng thu tiền hộ, Nhanh.vn sẽ đối soát và thanh toán lại tiền thu hộ cho doanh nghiệp.
- Nếu đơn hàng không đến được tay người nhận, hãng vận chuyển sẽ chuyển hoàn lại về cho doanh nghiệp.
- Doanh nghiệp cũng có thể xem thêm về quy trình vận hành của hãng vận chuyển [tại đây](link).

Quy trình vận chuyển của Nhanh.vn có 3 tab riêng để quản lý trạng thái đơn hàng, đó là "Vượt cân", "Giao hàng thất bại" và "Xác nhận chuyển hoàn" giúp doanh nghiệp quản lý đơn hàng ngay cả trong quá trình vận chuyển.

### Vượt cân

Tab này thống kê những đơn hàng đang chuyển có khối lượng thực tế lớn hơn so với khối lượng mà doanh nghiệp đã khai báo. Người dùng bấm nút vào tab ![](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/don-hang/img/quy-trinh-xu-ly-DH-2.jpg)  hoặc truy cập [tại đây](https://new.nhanh.vn/order/manage/index?features=17).

### Giao hàng thất bại

Tab này thống kê những đơn hàng có trạng thái "Thất bại" trong danh sách đơn hàng. Người dùng bấm nút vào tab ![](link) hoặc truy cập [tại đây](https://new.nhanh.vn/order/manage/index?status=61). Đối với các đơn hàng thất bại, doanh nghiệp có thể khiếu nại bằng cách bấm nút thao tác nhanh ![](link) và chọn Khiếu nại.

### Xác nhận chuyển hoàn

Tab này thống kê những đơn hàng đã giao thất bại và đang chuyển hoàn về cho doanh nghiệp, người dùng bấm nút vào tab ![](link) hoặc truy cập [tại đây](https://new.nhanh.vn/order/manage/index?status=71).

## Đối soát, thanh toán COD, chiết khấu
### Nhanh.vn đối soát với hãng vận chuyển

Hãng vận chuyển sẽ tiền hành đối soát với Nhanh một ngày sau khi đơn Thành công hoặc Chuyển hoàn.

Lịch trình Hãng vận chuyển đối soát cho Nhanh.vn:
[]() | **Viettel Post** | **Giaohangnhanh** | **Giaohangtietkiem** | **Vietnam Post**
------------ | ------------- | ------------- | ------------- | -------------
Ngày trả đối soát | Thứ 2, 4, 6 | Thứ 2, 4, 6 | Thứ 2, 4, 6 | Thứ 2, 3, 4, 5, 6

### Nhanh.vn đối soát và thanh toán COD với khách hàng

Để nhận được tiền thu hộ (COD), doanh nghiệp cần khai báo tài khoản nhận tiền [tại đây](https://new.nhanh.vn/store/paymentaccount/addbankacc).
Một ngày sau khi nhận đối soát từ Hãng vận chuyển, Nhanh sẽ thanh toán tiền hàng cho doanh nghiệp theo lịch:

[]() | **Khách doanh nghiệp** | **Khách lẻ**
------------ | ------------- | -------------
[]() | **Nhận qua tài khoản ngân hàng** | **Nhận qua tài khoản ngân hàng**
Vietnam Post | Thứ 2, 3, 4, 5, 6 | Thứ 2, 3, 5
Viettel Post | Thứ 2, 3, 5 | Thứ 2, 3, 5
Giaohangtietkiem | Thứ 2, 3, 5 | Thứ 2, 3, 5
Giaohangnhanh | Thứ 2, 3, 5 | Thứ 2, 3, 5

### Chiết khấu phí vận chuyển
Doanh nghiệp tham khảo [tại đây](link)

## Xử lý đơn hàng hoàn - Nhân viên kho
Trên Nhanh.vn - khi lịch trình của hãng vận chuyển cập nhật về là "Đã chuyển hoàn" thì Nhanh.vn vẫn để trạng thái đơn hàng là "Đang chuyển hoàn".

Khi bưu tá mang hàng sang cửa hàng => Nhân viên kho thêm biên bản bàn giao - loại nhận hàng chuyển hoàn https://nhanh.vn/shipping/handover/add

=> Tít mã vạch đơn hàng / gõ bằng tay từng ID đơn hàng

Khi đó - đơn hàng tự động đổi trạng thái sang "Đã chuyển hoàn" - Trạng thái tồn kho của sản phẩm không còn "Đang chuyển" nữa - Tức là hàng đã về kho - nằm trong phần số tồn.

## Cập nhật trạng thái đơn hàng "Tự vận chuyển"

Nếu bạn đưa hàng cho shiper - số lượng ít - và shiper trả tiền hàng mỗi ngày thì khi shiper về nộp tiền hàng => Vào biên bản của ngày hôm trước => tích và đổi trạng thái 1 loạt đơn hàng sang “Thành công”  hoặc “Đã chuyển hoàn”

Nếu như bạn đưa hàng cho hãng vận chuyển, số lượng nhiều - tiền COD trả lộn xộn không theo ngày gửi hàng => Import cập nhật trạng thái đơn hàng [tại đây](https://new.nhanh.vn/order/manage/importstatus).

Hoặc vào danh sách đơn hàng - lọc nhiều ID đơn hàng cùng lúc tại ô “IDs”, mỗi ID cách nhau 1 dấu phẩy, sau đó cũng select và đổi trang thái đơn hàng sang “Thành công” - công viêc này dành cho kế toán.

Lưu ý với hãng vận chuyển thì kế toán không cập nhật trạng thái “Đã chuyển hoàn” dựa vào file đối soát phí vận chuyển của hãng , mà nên để nhân viên kho tự đổi trạng thái khi nhận được hàng, như vậy sẽ không bị mất hàng.

Với đơn tự vận chuyển, thì chấp nhận việc “Thành công” đồng nghĩa với “Đã thanh toán”

Lời khuyên: Chỉ nhân viên kho được quyền phân quyền đổi trạng thái đơn hàng

Nhân viên chăm sóc chỉ cần phân quyền “Xác nhận đơn hàng“ nếu muốn đổi đơn hàng mới đặt sang “Khách hủy” hoặc “Hệ thống hủy”.

Bạn có thể tham khảo video hướng dẫn theo dõi và xử lí đơn hàng tại đây:
{% youtube src="link" %}{% endyoutube %}
