# Giới thiệu đơn hàng

Nhanh.vn giúp bạn dễ dàng theo dõi và thực hiện các đơn hàng. Tất cả các đơn đặt hàng, hàng tồn kho, nhà cung cấp và dữ liệu khách hàng của bạn được đồng bộ hóa và tích hợp đầy đủ trên một hệ thống.

Đơn hàng là nơi quản lý tất cả các đơn hàng online, đơn đặt hàng trước, đơn cần vận chuyển (đơn gửi hãng vận chuyển, cần thu hộ tiền COD).

## So sánh ĐƠN HÀNG và BÁN HÀNG
**Bán hàng** | **Đơn hàng**
------------ | -------------
Người mua trực tiếp tại cửa hàng | Khách hàng không mua tại cửa hàng, có một bên thứ 3 giao hàng
Mua và nhận hàng trực tiếp | Cần có quá trình để hoàn thành đơn hàng, quản lý thêm "trạng thái đơn hàng"
Trừ tồn kho và ghi nhận doanh thu ngay sau khi tạo đơn | Sau khi đơn hàng "Thành công" hệ thống trừ tồn và ghi nhận doanh thu

## Một số khái niệm trong Đơn hàng

### Trạng thái đơn hàng
**Trạng thái** | **Ý nghĩa**
------------ | -------------
**Mới** | Trạng thái đơn hàng mới tạo
**Đang xác nhận / Đã xác nhận** | Trạng thái lúc gọi điện cho khách để xác nhận lại đơn hàng
**Đang đóng gói sản phẩm** | Trạng thái đơn hàng mới tạo
**Chờ đi nhận / Đang đi nhận / Đã nhận hàng** | Chờ đi nhận khi doanh nghiệp gửi sang hãng vận chuyển; Đang đi nhận, Đã nhận hàng hãng vận chuyển sẽ cập nhật trạng thái này khi đi và nhận hàng gửi từ doanh nghiệp
**Đang chuyển** | Hãng vận chuyển sẽ đổi sang trạng thái này hoặc doanh nghiệp tự đổi với đơn tự vận chuyển
**Thất bại** | Nếu hãng vận chuyển gửi hàng đến khách hàng nhưng vì một lý do nào đó khách không nhận hoặc không gửi được cho khách, hãng sẽ cập nhật về trạng thái này -> doanh nghiệp cần liên hệ lại với khách hàng để xem chuyển hàng về hay gửi lại cho khách
**Đang chuyển hoàn** | Khi khác hàng không nhận và doanh nghiệp xác nhận việc khách không nhận hàng, hãng sẽ cập nhật về trạng thái này và mang hàng về cho doanh nghiệp
**Đã chuyển hoàn** | Doanh nghiệp nhận lại hàng Đang chuyển hoàn và tự đổi sang trạng thái Đã chuyển hoàn
**Thành công** | Khi đơn hàng đã gửi cho khách thì hãng/doanh nghiệp cần đổi sang trạng thái thành công.

### Biên bản bàn giao
Khi có nhiều đơn hàng cần gửi cho hãng vận chuyển trong ngày, bạn nên dùng biên bản bàn giao để:
- Cho nhiều đơn hàng vào biên bản và bắn biên bản sang hãng vận chuyển cùng 1 thời điểm, giúp cho việc điều tin nhanh và tập trung hơn.
- In bảng tổng hợp số lượng sản phẩm để nhặt hàng và đóng gói nhanh hơn.
- In biên bản cho bưu tá kí xác nhận đã nhận tổng số đơn và bảng kê chi tiết, mà không cần kí nhận từng phiếu gửi giúp tiết kiệm giấy in, hạn chế thất thoát.

### Đối soát
Nhanh.vn sẽ đối soát các đơn hàng gửi qua hãng vận chuyển để gửi tiền cho doanh nghiệp.

### Khiếu nại 
Khi đơn hàng phát sinh các vấn đề như:

- Bưu tá chậm đến lấy hàng
- Muốn thay đổi thông tin đơn hàng, đổi tiền thu hộ (COD)
- Báo lưu đơn hàng tại kho, báo phát lại, báo hoàn hàng, báo hủy đơn hàng
- Yêu cầu cập nhật trạng thái đơn hàng....
- Thì bạn dùng tính năng Khiếu nại để báo Nhanh.vn xử lý các vấn đề này.

## Các hoạt động của đơn hàng 

### Tạo đơn hàng 

**Đơn hàng có thể được tạo từ các nguồn sau:**

- Khách gọi điện thoại đến doanh nghiệp để đặt hàng > Nhân viên tự tạo đơn hàng
  - Doanh nghiệp vào tạo đơn hàng trong hệ thống, điền đấy đủ các thông tin khách hàng, báo cho khách về phí vận chuyển (nếu có).
  - Doanh nghiệp import đơn hàng để tạo nhiều đơn hàng cùng lúc lên hệ thống.
  
![](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/don-hang/img/gioi-thieu-don-hang-3.png)
  
- Đơn hàng đồng bộ từ phần mềm quản lý fanpage https://vpage.nhanh.vn

![](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/don-hang/img/gioi-thieu-don-hang-2.png)

- Đơn hàng do người mua đặt hàng từ website bán hàng của doanh nghiệp do Nhanh.vn cung cấp

![](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/don-hang/img/gioi-thieu-don-hang-1.png)

- Đơn hàng nhận từ API đồng bộ giữa Nhanh.vn với các sàn TMĐT (Lazada.vn, Shopee.vn, Tiki.vn, Sendo.vn, Vatgia.com, Adayroi.com)
*Đang cập nhật ảnh*
![](link)

### Xử lý đơn hàng
**1. Quy trình đơn hàng**

Sau khi tạo đơn hàng, doanh nghiệp thực hiện các bước **Xác nhận đơn hàng > In hàng và đóng gói > Cho đơn hàng vào biên bản bàn giao > Vận chuyển > Đối soát (nếu có dùng hãng vận chuyển) và thanh toán** để hoàn thành xong đơn hàng thành công.

Doanh nghiệp xem thêm chi tiết [Quy trình xử lý đơn hàng](https://manual.nhanh.vn/don-hang/quy-trinh-xu-ly-don-hang)

**Lưu ý:** Quy trình xử lý đơn hàng hiện tại trên nhanh là:

- Doanh nghiệp tạo đơn.
- Gửi đơn sang hãng vận chuyển.
- Khi hãng vận chuyển thay đổi trạng thái -> Cập nhật lịch trình về Nhanh.
- Khi đơn hàng giao Thành công hoặc Chuyển hoàn về, hãng vận chuyển đối soát với Nhanh.
- Nhanh sẽ check các thông tin về khối lượng | tiền cần thu | giá cước (xem có phí vượt cân, có đúng với giá cước theo hợp đồng không) => Khớp các giá trị trên sẽ chốt đối soát với hãng vận chuyển, sau đó Nhanh sẽ chuyển lại tiền này cho doanh nghiệp.

Khi sử dụng vận chuyển trên Nhanh thì các bước 2,3,4 trên là do Nhanh làm, còn với doanh nghiệp Tự vận chuyển thì sẽ tự làm các bước đổi trạng thái, đối soát, chốt tiền.

**2. Xử lý đơn trùng** 

Tính năng này dùng để kiếm tra những đơn hàng của cùng một khách hàng. Từ đó doanh nghiệp có thể tiến hành gộp nhiều đơn thành một đơn cho khách hàng 
- Mặc định hệ thống sẽ lọc đơn trong 2 ngày gần nhất. Bạn có thể chọn lại khoảng ngày này.
Để gộp đơn hàng, doanh nghiệp thực hiện như sau:

**Bước 1:** Đơn hàng > Đơn trùng > Bấm chọn tổng số lượng đơn

![Giao diện làm việc của Đơn trùng](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/don-hang/img/gioi-thieu-don-hang-4.png)

**Bước 2:** Bấm chọn những đơn cần gộp > Bấm nút **Thao tác** > **Gộp các đơn đã chọn**

![](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/don-hang/img/gioi-thieu-don-hang-5.png)

**Bước 3:** Chọn đơn hàng cần lấy thông tin

![](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/don-hang/img/gioi-thieu-don-hang-6.png)

Đơn hàng sau khi đã được gộp

![](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/don-hang/img/gioi-thieu-don-hang-7.png)


**Lưu ý:** Chỉ thực hiện gộp đơn hàng đối với những đơn hàng cùng một khách hàng và hãng vận chuyển chưa lấy hàng

**3. Xử lý đổi trả đơn hàng**

Trường hợp khách hàng muốn trả hoặc đổi trả đơn hàng đã giao thành công thì doanh nghiệp thực hiện thao tác này.
Xem chi tiết các bước thực hiện [tại đây](https://manual.nhanh.vn/ban-hang/tra-hang).

**4. Xử lý sửa và đơn hàng**

Đối với những đơn hàng chưa giao thành công doanh nghiệp có thể hủy và sửa thông tin đơn hàng, thay đổi sản phẩm, số lượng,... trong phần [Khiếu nại](link) đơn hàng. 

## Để quản lý đơn hàng TỐT hơn, bạn cần?
- Luôn quản lý, theo dõi trạng thái, lịch trình của các đơn hàng
- Nắm được nguyên tắc xuất nhập kho, tồn của sản phẩm
- Lựa chọn được hãng vận chuyển uy tín và phù hợp
