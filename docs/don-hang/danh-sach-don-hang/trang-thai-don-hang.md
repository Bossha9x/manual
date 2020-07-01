# Trạng thái đơn hàng

**Trạng thái** | **Ý nghĩa**
------------ | -------------
![](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/don-hang/img/trang-thai-DH-1.png) | Đơn hàng khách hàng đã đặt hàng chưa qua xử lý
![](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/don-hang/img/trang-thai-DH-2.png) | Đơn hàng đang được chờ nhân viên viên xác nhận 
![](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/don-hang/img/trang-thai-DH-3.png) | Đơn hàng đang được nhân viên Chăm sóc khách hàng (gọi điện thoại) xác nhận với khách hàng
![](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/don-hang/img/trang-thai-DH-4.png) | Đơn hàng đã được xác nhận thành công (khách hàng có mua hàng)
![](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/don-hang/img/trang-thai-DH-7.png) | Đơn hàng đang được nhặt hàng và đóng gói sản phẩm
![](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/don-hang/img/trang-thai-DH-6.png) | Đơn hàng được chuyển từ cửa hàng hết sản phẩm khách đặt sang cửa hàng còn tồn .
![](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/don-hang/img/trang-thai-DH-8.png) | Đơn hàng đã bắn sang hãng vận chuyển, chờ hãng vận chuyển tiếp nhận thông tin và nhận hàng.
![](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/don-hang/img/trang-thai-DH-9.png) | Đơn hàng đang được chuyển đi cho khách hàng.
![](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/don-hang/img/trang-thai-DH-10.png) | Đơn hàng đã được giao thành công cho khách hàng.
![](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/don-hang/img/trang-thai-DH-11.png) | Đơn hàng chưa giao được cho khách hàng. (Có thể vì khách hàng bận, đi vắng, khách hẹn lại thời điểm khác giao hàng...)
![](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/don-hang/img/trang-thai-DH-12.png) | Khách hàng hủy không lấy hàng nữa
![](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/don-hang/img/trang-thai-DH-13.png) | Đơn hàng đã bị hệ thống hủy tự động
![](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/don-hang/img/trang-thai-DH-14.png) | Đơn hàng đã bị hãng vận chuyển hủy
![](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/don-hang/img/trang-thai-DH-5.png) | Sản phẩm của khách đặt đã hết hàng.
![](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/don-hang/img/trang-thai-DH-15.png) | Những đơn hàng khách hàng hủy không muốn lấy sản phẩm nữa sẽ được hoàn trả về cho doanh nghiệp
![](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/don-hang/img/trang-thai-DH-16.png) | Sau khi làm biên bản chuyển hoàn (hãng vận chuyển bàn giao lại hàng hóa cho doanh nghiệp), đơn hàng sẽ tự động chuyển sang trạng thái đã chuyển hoàn



**Lưu ý:** 

Trên lịch trình của hãng vận chuyển, có thể hãng vận chuyển báo đã chuyển hoàn cho doanh nghiệp tuy nhiên trên hệ thống Nhanh.vn vẫn để ở trạng thái "Đang chuyển hoàn". Để tránh thất thoát hàng hóa qua quá trình vận chuyển. Khi doanh nghiệp nhận được sản phẩm thực tế hoàn lại từ hãng vận chuyển, doanh nghiệp cần đổi trạng thái thành "Đã chuyển hoàn" bằng cách: 
- Cách 1: Lập biên bản chuyển hoàn (biên bản bàn giao hàng hóa từ hãng vận chuyển -> doanh nghiệp).
- Cách 2: Cập nhật trạng thái "Đã chuyển hoàn" trên hệ thống. Đồng thời với thao tác đó, hệ thống tự động trừ đi số lượng sản phẩm "Đang tạm giữ" (để chuyển hàng) nhập lại vào kho/ cửa hàng đã xuất ra (số lượng nhập lại được tính vào trạng thái "Có thể bán").
