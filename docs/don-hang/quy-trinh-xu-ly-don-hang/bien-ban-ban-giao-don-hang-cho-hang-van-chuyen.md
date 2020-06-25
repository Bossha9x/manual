# Biên bản bàn giao đơn hàng cho hãng vận chuyển

Nếu bạn có sản lượng đơn hàng nhiều (khoảng trên 50 đơn) thì nên dùng Biên bản bàn giao vận đơn để:
- Nhặt hàng trong kho nhanh hơn bằng bảng tổng hợp sản phẩm
- Gửi nhiều đơn sang hãng vận chuyển cùng lúc
- Bưu tá kí và xác nhận việc lấy hàng (lấy bao nhiêu đơn, số đơn, ngày giờ lấy hàng)
- Doanh nghiệp xác nhận việc nhận lại hàng do hãng vận chuyển chuyển hoàn.

## Danh sách Biên bản bàn giao vận đơn
Biên bản bàn giao vận đơn dùng để xác nhận một trong hai trường hợp sau : 

- Bạn đã gửi hàng sang cho hãng vận chuyển chưa?
- Bạn đã nhận lại hàng do hãng vận chuyển chuyển hoàn chưa?
Để làm việc tại đây, bạn truy cập vào Đơn hàng / Biên bản bàn giao vận đơn, hoặc truy cập [tại đây](link).

Giao diện làm việc của Danh sách biên bản bàn giao vận đơn như sau:

![Giao diện làm việc của Danh sách biên bản bàn giao](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/don-hang/img/bien-ban-ban-giao-1.png)

## Bộ lọc 

![Giao diện làm việc của bộ lọc](link)

Trong đó:
- **ID:** Lọc ID của Biên bản bàn giao. 
- **ID đơn đặt hàng:** Lọc theo ID của đơn đặt hàng (đã được xác nhận, đóng gói và chuyển qua hãng vận chuyển) được bắn qua từ module Đơn hàng.
- **Cửa hàng:** Lọc theo địa điểm kho hàng/cửa hàng bàn giao hàng hóa giữa 02 bên: doanh nghiệp và hãng vận chuyển.
- **Hãng vận chuyển:** Lọc theo hãng vận chuyển tiếp nhận đơn hàng.
- **Loại:** Loại bàn giao của đơn hàng : Gửi hàng (Từ doanh nghiệp tới hãng vận chuyển) hay Chuyển hoàn (Từ hãng vận chuyển tới doanh nghiệp).
- **Miêu tả:** Lọc theo đoạn ghi chú, mô tả trong biên bản bàn giao vận đơn
- **Nhân viên vận chuyển:** Lọc theo nhân viên vận chuyển tiếp nhận đơn hàng.
- **Từ ngày - Đến ngày:** Lọc những biên bản bàn giao được bàn giao trong một khoảng thời gian nhất định.
- **Người tạo:** Lọc theo người tạo biên bản bàn giao.

*(Đang cập nhật) - Ver2 chưa có bộ lọc*

### Các nút thao tác nhanh ![ biên bản bàn giao](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/img/them-moi.jpg) ![ biên bản bàn giao](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/img/thao-tac.jpg)


- Nút Thêm mới cho phép doanh nghiệp tạo/thêm mới một biên bản bàn giao vận đơn.
- Nút Thao tác gồm các tùy chọn Xuất Excel danh sách biên bản bàn giao vận đơn ở trang hiện tại hoặc tất cả các trang để lưu trữ.

### Thông tin trong Biên bản bàn giao vận đơn

![](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/don-hang/img/bien-ban-ban-giao-2.png)

- ![doi-soat-don-hang ](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/don-hang/img/bien-ban-ban-giao-4.png): Hiển thị ID của biên bản bàn giao vận đơn (do hệ thống tự sinh, khi click vào sẽ chuyển đến trang chi tiết biên bản bàn giao vận đơn) và ô chọn ![doi-soat-don-hang ](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/don-hang/img/bien-ban-ban-giao-4.png) cho phép doanh nghiệp tích chọn một hay nhiều biên bản để thao tác.
- **Hãng vận chuyển:** Hiển thị tên hãng vận chuyển và số lần in biên bản bàn giao. Nếu đơn hàng tự vận chuyển thì sẽ hiện chữ "Tự vận chuyển"
- **Kho:** Kho hàng / Cửa hàng lập biên bản bàn giao.
- **Loại:** Gửi hàng chuyển đi và Nhận hàng hoàn về.
  - Gửi hàng: Dùng để xác nhận việc doanh nghiệp đã giao hàng cho hãng vận chuyển để giao đi cho khách hàng.
  - Chuyển hoàn: Dùng để xác nhận việc doanh nghiệp đã nhận lại hàng hoàn từ hãng vận chuyển.
- **Số đơn:** Mục này cho biết số  đơn hàng có trong biên bản bàn giao. 
- **Ghi chú:** Hiển thị tất cả những mô tả, ghi chú thêm về biên bản bàn giao.
- **Người tạo:** Hiển thị người tạo biên bản bàn giao
- **Nút thao tác nhanh:** ![bien-ban-ban-giao](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/don-hang/img/bien-ban-ban-giao-3.png) gồm các tùy chọn:
  - In biên bản với giao diện đầy đủ (có kèm theo sản phẩm) và rút gọn
  - Thêm đơn hàng vào biên bản: Dùng để thêm đơn vào biên bản bàn giao cho hãng vận chuyển khi hãng vận chuyển đang nhận hoặc chưa đến nhận bàn giao.(Không dùng trong trường hợp đã lấy hàng).
  - Xóa biên bản bàn giao vận đơn.
  
  ## Thêm biên bản bàn giao vận đơn
Thêm biên bản bàn giao vận đơn giúp bạn thực hiện nghiệp vụ thêm biên bản bàn giao đơn hàng cho hãng vận chuyển.

Sau khi doanh nghiệp gửi đơn qua bên hãng vận chuyển, nhân viên hãng vận chuyển sẽ qua trực tiếp kho / cửa hàng bàn giao đơn hàng để tiếp nhận đơn hàng. Hai bên cần tiến hành xác lập biên bản bàn giao để xác thực quá trình bàn giao. 

Để làm việc tại đây, bạn truy cập vào Đơn hàng / Biên bản bàn giao vận đơn, sau đó click vào nút thêm mới hoặc truy cập [tại đây](link).

### QUY TRÌNH LẬP BIÊN BẢN BÀN GIAO VẬN ĐƠN
**Bước 1:** Truy cập vào [Thêm biên bản bàn giao vận đơn](link)

**Bước 2:** Nhập liệu thông tin

Điền đầy đủ thông tin vào các trường đánh dấu **(*)**


![](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/don-hang/img/bien-ban-ban-%20giao-5.png)


Trong đó:

- **Cửa hàng:** Chọn kho/cửa hàng xuất hàng cho hãng vận chuyển
- **Hãng vận chuyển:** Chọn hãng vận chuyển đã bắn (gửi) vận đơn sang.
- **Loại:** Chọn loại Gửi hàng
- **ID đơn đặt hàng:** Nhập ID đơn hàng đã bắn sang hãng vận chuyển.
- **Mô tả:** Hiển thị thông tin ghi chú thêm về đơn hàng hay thời gian giao hàng.

**Bước 3:** Lưu biên bản bàn giao vận đơn

Doanh nghiệp có thể in biên bản bàn giao với 2 tùy chọn là In biên bản đầy đủ và In biên bản rút gọn. Đồng thời với bước in, hệ thống sẽ lưu biên bản bàn giao hàng hóa vào Danh sách biên bản bàn giao vận đơn [tại đây](link).

Bước 4: Gửi và in biên bản bàn giao vận đơn

Doanh nghiệp click vào nút ![biên bản vận chuyển](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/don-hang/img/bien-ban-ban-giao-6.png) để xác nhận gửi vận đơn qua hãng vận chuyển lần nữa, sau đó ấn nút in biên bản. Hai bên cùng ký xác nhận bàn giao vận đơn hàng hóa.

**Lưu ý:**
- Tất cả các đơn hàng đã bắn sang hãng vận chuyển không được quyền sửa hoặc xóa cho đến khi hãng vận chuyển cập nhật trạng thái.
- Trong trường hợp muốn thay đổi vận đơn cần tạo đơn mới lại để gửi hãng vận chuyển và hủy đơn cũ bị lỗi. 
- Đối với những đơn hàng sai kho, hoặc khác hãng vận chuyển, hệ thống sẽ chặn và hiển thị thông báo chi tiết cho người dùng.
