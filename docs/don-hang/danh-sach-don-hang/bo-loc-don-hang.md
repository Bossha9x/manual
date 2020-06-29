# Bộ lọc đơn hàng

Bộ lọc đơn hàng giúp bạn tìm kiếm nhanh, chính xác đơn hàng. Giao diện làm việc của Bộ lọc đơn hàng được ẩn đi. Khi doanh nghiệp muốn sử dụng bộ lọc đầy đủ, chỉ cần bấm nút vào chữ "**Tìm kiếm**"  để hiển thị bộ lọc.

Bộ lọc đầy đủ có giao diện như sau:

![Giao diện của bộ lọc đầy đủ](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/don-hang/img/bo-loc-don-hang-1.png)

## Nhóm lọc theo Thông tin đơn hàng

- **Doanh nghiệp:** Đối với tài khoản quản trị nhiều doanh nghiệp thì cần sử dụng trường lọc này.
- **ID:** Mỗi đơn hàng được tạo ra sẽ được gắn với 01 ID (để phân biệt với những đơn hàng khác). 
- **IDs:** Cho phép người dùng tìm nhiều ID đơn hàng cùng 1 lúc, Ví dụ: 113245, 113256,...
- **ID website tích hợp:** Là ID đơn hàng của những đơn hàng được đồng bộ từ các website của khách hàng về hệ thống.
- **Sản phẩm:** Lọc theo tên sản phẩm trong đơn hàng
- **Danh mục sản phẩm:** Lọc theo danh mục sản phẩm trong đơn hàng 
- **IMEI:** Lọc theo số IMEI của sản phẩm (áp dụng đối với sản phẩm có thuộc tính IMEI như điện thoại, máy tính bảng, đồ điện tử...)
- **Loại đơn :** Hình thức mua hàng của khách hàng, bao gồm: 
  - Chuyển hàng: Khách hàng chọn hình thức nhận hàng tại nhà (doanh nghiệp vận chuyển hàng cho khách hàng).
  - Đặt trước: Khách hàng đã thanh toán trước một phần giá trị đơn hàng (nhằm mục đích muốn doanh nghiệp giữ hàng (chắc chắn chuyển hàng) cho khách hàng.
  - Mua tại quầy: Khách hàng đến tại cửa hàng của doanh nghiệp, mua hàng và thanh toán trực tiếp.
  - Mua nhanh: Áp dụng với những đơn hàng...
  - Dùng thử: Khách hàng muốn dùng thử, trải nghiệm về sản phẩm trước khi mua (áp dụng với những sản phẩm công nghệ, gia dụng, điện tử, điện lạnh,...)
  - Đổi quà: Là loại đơn hàng sử dụng tính năng đổi điểm tích lũy sang quà tặng
  - Xin báo giá: Loại đơn xin báo giá sản phẩm
- **Loại giá bán:** Lọc theo đơn hàng bán theo giá bán lẻ hoặc bán buôn.
- **Kênh bán:** Nguồn gốc đơn hàng, bao gồm: 
  - Website: Khách hàng đặt hàng trực tiếp từ website
  - Admin: Doanh nghiệp tạo đơn hàng trực tiếp từ hệ thống Nhanh.vn
  - Nguồn tích hợp: Đơn hàng từ các sàn TMĐT (Vật giá, Shopee, Lazada, Sendo, Tiki, Adayroi), tích hợp từ API, Facebook, Instagram, zalo
- **Nguồn đơn hàng:** Lọc theo các nguồn đơn hàng mà doanh nghiệp đã thêm lên hệ thống.
- **Ghi chú:** Ghi chú, mô tả thêm của khách hàng về đơn hàng
- **Ghi chú CSKH:** Ghi chú, mô tả thêm của nhân viên chăm sóc khách hàng về đơn hàng
- **Người tạo đơn:** Người tạo đơn hàng. Có thể là khách hàng hoặc nhân viên của doanh nghiệp
- **Đặc điểm**: Lọc đơn hàng theo các đặc điểm (Đã gửi vận chuyển, Chưa gửi vận chuyển, Có chuyển khoản, Chưa chuyển khoản, Có tiền đặt cọc, Không có tiền đặt cọc,...).
## Nhóm theo Thông tin khách hàng

- **Khách hàng:** Lọc theo tên khách đặt mua hàng
- **Cửa hàng:** Lọc theo kho/cửa hàng của doanh nghiệp
- **Thành phố, Quận huyện:** Lọc theo địa chỉ người nhận trong đơn hàng (địa chỉ khách hàng)
- **Tạo từ ngày/ Tạo đến ngày:** Lọc theo khoảng thời gian tạo đơn hàng
- **Xác nhận từ ngày/ Xác nhận đến này**: Lọc theo khoảng thời gian xác nhận đơn hàng
- **Đóng gói từ ngày/ Đóng gói đến ngày**: Lọc theo khoảng thời gian đóng gói đơn hàng
- **Gửi hàng từ ngày/ Gửi hàng đến ngày**: Lọc theo khoảng thời gian đơn hàng được gửi sang hãng vận chuyển.
- **Giao hàng từ ngày/ Giao hàng đến ngày**: Lọc theo khoảng thời gian đơn hàng được giao thành công
- **Người In:** Lọc theo tên người in phiếu gửi cho đơn hàng
- **NVBH:** Lọc theo tên nhân viên bán hàng.

## Nhóm theo Thông tin vận chuyển
- **Hãng vận chuyển:** Lọc đơn hàng theo các hãng vận chuyển hoặc đơn hàng do doanh nghiệp tự vận chuyển.
- **Trạng thái:** Lọc theo các trạng thái của đơn hàng (Mới, Đang chuyển, Thành công...), doanh nghiệp có thể xem thêm ý nghĩa của các trạng thái đơn hàng [tại đây](https://manual.nhanh.vn/don-hang/danh-sach-don-hang#trang-thai-don-hang).
- **Mã vận đơn:** Lọc theo mã vận đơn của đơn hàng, mã này do mỗi hãng vận chuyển quy định
- **ID Biên bản bàn giao:** Lọc theo ID của biên bản bàn giao vận đơn
- **Loại chuyển hàng:** Lọc theo kiểu chuyển hàng: Chuyển hàng tận nhà, Đổi sản phẩm, Khách trả lại hàng
  - Chuyển hàng tận nhà: Loại đơn này dùng để ghi nhận việc doanh nghiệp giao hàng cho khách.
  - Đổi sản phẩm: Loại đơn này dùng khi người mua đã gửi trả lại hàng cũ/hàng lỗi cho người bán, đơn hàng này được dùng để ghi nhận việc người bán giao lại hàng mới cho khách hàng.
  - Hàng chuyển kho: Loại đơn này dùng khi người bán muốn chuyển sản phẩm sang kho khác 
- **Khách trả lại hàng:** Loại đơn này dùng để ghi nhận việc khách trả lại sản phẩm đã mua.
- **Phương thức thanh toán:** Lọc theo phương thức thanh toán: Thanh toán tại nhà, thanh toán tại quầy, qua cổng thanh toán...
- **Người tạo:** Lọc theo tên người tạo
- **CSKH:** Lọc đơn hàng có hoặc không có nhân viên chăm sóc khách hàng và tên nhân viên đó.

## Nhóm theo Thông tin thanh toán 
- **Trạng thái bàn giao:** Tình trạng xử lý đơn hàng giữa hãng vận chuyển và doanh nghiệp
  - Đã bàn giao: Doanh nghiệp đã bàn giao đơn hàng cho hãng vận chuyển.
  - Chưa bàn giao: Doanh nghiệp chưa bán giao đơn hàng cho hãng vận chuyển.
  - Đã bàn giao chuyển hoàn: Hãng vận chuyển chưa bàn giao và chuyển hoàn lại đơn hàng cho doanh nghiệp.
  - Chưa bàn giao chuyển hoàn: Hãng vận chuyển đã bàn giao và chuyển hoàn đơn hàng cho doanh nghiệp.
  - Đã cho vào tour: 

- **Chuyển tiền:** Lọc đơn hàng theo trạng thái thanh toán, đã được Nhanh.vn thanh toán tiền thu hộ cho doanh nghiệp hay chưa, bao gồm:
  - Đã chuyển tiền: Đơn hàng đã được Nhanh.vn thanh toán tiền thu hộ cho doanh nghiệp
  - Chưa chuyển tiền: Đơn hàng chưa được Nhanh.vn thanh toán tiền thu hộ cho doanh nghiệp
  - Đã duyệt chuyển tiền: Đơn hàng đã được Nhanh.vn đối soát để thanh toán
  - Đang duyệt chuyển tiền: Đơn hàng đang chờ được Nhanh.vn đối soát để thanh toán
- **Thanh toán từ ngày/ Thanh toán đến ngày:** Lọc ngày thanh toán đơn hàng
- **Chiết khấu vận chuyển:** Lọc đơn hàng có hoặc không có chiết khấu
- **Mã Coupon:** Mã coupon của đơn hàng có coupon
- **Thu của khách:** Lọc đơn hàng có hoặc không có phí thu của khách
- **Tổng thu hộ:** Lọc theo số tiền thu hộ trên đơn hàng, lớn hơn, nhỏ hơn hoặc bằng 1 giá trị nào đó (ví dụ: lọc đơn hàng có tiền thu hộ hơn hơn 1000.000 VNĐ)
- **Lý do hủy hàng:** Lọc theo lý do hủy đơn hàng, do hết hàng hoặc lý do khác.
