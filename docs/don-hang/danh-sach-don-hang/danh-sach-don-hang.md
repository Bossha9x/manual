# Danh sách đơn hàng

Danh sách đơn hàng là nơi tập hợp tất cả các đơn đặt hàng của bạn. Danh sách này được chia thành nhiều tab, mỗi tab tương ứng với khâu trong quá trình xử lý đơn hàng, tạo thành một luồng làm việc hoàn chỉnh, giúp bạn quản lý đơn hàng từ lúc được tạo mới cho tới khi đơn hàng thành công.

Bạn truy cập trực tiếp vào module Đơn hàng / Danh sách đơn hàng hoặc truy cập [tại đây](https://new.nhanh.vn/order/manage/index).

![Giao diện làm việc của Danh sách đơn hàng](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/don-hang/img/danh-sach-don-hang-3.png)

## Các thành phần của Danh sách đơn hàng 

### Bộ lọc danh sách đơn hàng (Tìm kiếm)
Bộ lọc đơn hàng giúp bạn tìm kiếm chính xác được những trạng thái, kiểu đơn hàng, thành công hay thất bại, .....

Hệ thống Nhanh.vn cung cấp một bộ lọc đầy đủ, các trường lọc được nhóm theo những nhóm lọc linh hoạt: theo thông tin đơn hàng, theo thông tin khách hàng, theo thông tin thanh toán, theo thời gian xử lý của đơn hàng,...

Xem thêm chi tiết về Bộ lọc [tại đây](https://manual.nhanh.vn/don-hang/danh-sach-don-hang#bo-loc-don-hang).

### Các nút thao tác
- Nút **Thêm mới** bao gồm các lựa chọn:
  - Thêm mới đơn hàng: Thêm mới đơn hàng trực tiếp. Dùng khi doanh nghiệp muốn thêm từng đơn hàng một. Xem hướng dẫn [tại đây](hhttps://manual.nhanh.vn/don-hang/quy-trinh-xu-ly-don-hang/them-don-hang#them-le-tung-don-hang).
  - Import đơn hàng từ Excel: Cho phép doanh nghiệp tạo nhiều đơn hàng cùng lúc bằng cách tải file Excel. Xem hướng dẫn [tại đây](https://manual.nhanh.vn/don-hang/quy-trinh-xu-ly-don-hang/them-don-hang#import-don-hang-bang-excel).
  - Import trạng thái đơn hàng từ Excel: Cho phép doanh nghiệp thay trạng thái của nhiều đơn hàng cùng lúc bằng cách tải file Excel chưa thông tin và trạng thái của các đơn hàng lên hệ thống. Xem hướng dẫn [tại đây](https://manual.nhanh.vn/don-hang/quy-trinh-xu-ly-don-hang/them-don-hang#import-trang-thai-don-hang-bang-excel).
- Nút **Thao tác** bao gồm các lựa chọn:
  - In phiếu gửi các đơn đã chọn: Phiếu gửi là phiếu chứa thông tin được dán lên đơn hàng, doanh nghiệp tích chọn các đơn muốn in phiếu gửi, rồi bấm nút vào lựa chọn này để in.
  - In nhãn các đơn đã chọn: Nhãn gửi là một dạng khác của phiếu gửi (chứa ít thông tin hơn), doanh nghiệp bấm nút lựa chọn này để in nhãn gửi đơn.
  - Xuất Excel trang hiện tại: Tính năng này cho phép người dùng xuất danh sách đơn hàng tại trang hiện tại về máy tính dưới dạng file Excel.
  - Xuất Excel trang hiện tại (bản đầy đủ): Tính năng này cho phép người dùng xuất toàn bộ danh sách đơn hàng về máy tính cá nhân dưới dạng file Excel.
  - Gửi các đơn đã chọn sang hãng vận chuyển: Tính này cho phép bạn gửi các đơn đã chọn sang hãng vận chuyển.
  - Thêm đơn vào biên bản bàn giao: Tính này cho phép bạn thêm các đơn đã chọn vào biên bản bàn giao.
  - Gộp các đơn đã chọn: Nhiều khách hàng đặt nhiều đơn trong cùng một thời điểm hay đặt nhiều đơn hàng nhỏ lẻ, doanh nghiệp nên gộp thành 01 đơn duy nhất để tiết kiệm thời gian xử lý đơn hàng cũng như chi phí vận chuyển đơn hàng cho khách hàng.
  - Gửi các đơn đã chọn sang hãng vận chuyển: Doanh nghiệp tích chọn các đơn muốn gửi sang hãng vận chuyển, sau đó bấm nút lựa chọn này để gửi đơn.
  - Cập nhật hãng vận chuyển: Dùng để cập nhật những thay đổi của đơn hàng cho hãng vận chuyển.
  - Đổi kho hàng: Tính này này cho phép bạn được đổi kho để xuất bán sản phẩm.
  
  
  
  ## Thông tin đơn hàng
  
 
  ![](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/don-hang/img/danh-sach-don-hang-1.png)
  
- **Nút tích chọn** ![Giao diện làm việc](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/don-hang/img/in-dong-goi-2.png): Cho phép thao tác chọn ID các đơn hàng để thực hiện các nghiệp vụ khác, ví dụ như In nhiều đơn hàng,...
- **ID:** Mỗi đơn hàng có 01 ID, nhằm mục đích phân biệt với các đơn hàng khác. Phần ID tổng hợp luôn thông tin thời gian đặt hàng và loại đơn hàng. Khi bấm nút vào ID đơn hàng, hệ thống sẽ chuyển sang giao diện [Chi tiết đơn hàng](https://manual.nhanh.vn/don-hang/danh-sach-don-hang#chi-tiet-don-hang).
- **Khách hàng:** Hiển thị thông tin khách hàng đặt hàng bao gồm: Họ tên, Số điện thoại, Địa chỉ. Khi bấm nút vào số điện thoại, hệ thống sẽ lọc ra toàn bộ các đơn hàng của khách hàng đó.
- **Sản phẩm:** Hiển thị danh sách sản phẩm khách hàng đã đặt hàng.
- **Giá:** Tổng giá trị của đơn hàng.
- **Số lượng:** Tổng số lượng sản phẩm trong đơn hàng.
- **Vận chuyển:** Hiển thị các thông tin vận chuyển của đơn hàng: Ngày nhận hàng, Phí vận chuyển, Phí thu tiền hộ, Phí thu của khách, Hãng vận chuyển. Tìm hiểu thêm [tại đây](linlk).
- **Thanh toán:** Hiển thị số tiền khách đã thanh toán trước cho đơn hàng (do khuyến mại giảm giá hoặc do khách hàng đã chuyển khoản.
- **Tổng thu:** Là tổng thu của đơn hàng sau khi trừ đi chiết khấu khuyến mại.
- **Ghi chú:** Hiển thị những ghi chú, mô tả của khách hàng/ nhân viên chăm sóc khách hàng về đơn hàng. Cho phép bấm nút để sửa ngay tại biểu tượng ![Giao diện làm việc](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/don-hang/img/danh-sach-don-hang-2.png).
- **Trạng thái:** Cho phép doanh nghiệp biết được tình trạng của 01 đơn hàng. Xem thêm các trạng thái đơn hàng [tại đây](https://manual.nhanh.vn/don-hang/danh-sach-don-hang#trang-thai-don-hang). Bên dưới trạng thái đơn hàng là nút thao tác nhanh  ![Giao diện làm việc](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/don-hang/img/in-dong-goi-3.png), tùy vào trạng thái đơn hàng sẽ có các thao tác khác nhau.
