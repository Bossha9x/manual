Ở góc bên trái màn hình, bạn sẽ nhìn thấy các tính năng mà mình có thể thực hiện được tại mục này. Cụ thể, như sau:


![Nội dung chính của kho hàng](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/kho-hang/img/Capture.PNG)

# Nội dung chính của từng mục xuất hiện trong Kho Hàng
| STT | Đề mục | Nội dung |
|-----|--------|----------|
| 1 | ![](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/kho-hang/img/1.PNG) | Thực hiện các thao tác liên quan đến việc thêm (hoặc xóa) phiếu xuất nhập kho, đồng thời hỗ trợ tìm kiếm phiếu xuất nhập kho nhanh chóng thông qua các trường thông tin theo ID, thời gian, loại, kiểu, khách hàng, người tạo... |
| 2 | ![](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/kho-hang/img/2.PNG) | Tương tự với mục xuất nhập kho tuy nhiên nếu ở mục xuất nhâp kho hỗ trợ quản lý theo phiếu xuất nhập kho (một phiếu có thể có nhiều sản phẩm) thì ở mục này, phần mềm hỗ trợ bạn quản lý xuất nhập kho theo sản phẩm |
| 3 | ![](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/kho-hang/img/3.PNG) | Hỗ trợ lập phiếu chuyển kho giữa các cửa hàng và theo dõi tình trạng hàng chuyển kho |
| 4 | ![](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/kho-hang/img/4.PNG) | Thực hiện thao tác kiểm kho, giúp bạn kiểm kê lại số lượng hàng hóa tồn kho thực tế so với số lượng tồn kho trên phần mềm, và cập nhật số lượng tồn kho thực thế lên phần mềm (bù trừ kiểm kho) | 
| 5 | ![](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/kho-hang/img/5.PNG) | Sự khác nhau giữa phiếu nháp và phiếu chính là phiếu nháp phải thông qua một bước duyệt. Việc này giúp người quản lý dễ dàng quản lý được công việc của nhân viên nhưng lại không muốn có sai sót ảnh hưởng đến tồn kho cửa hàng |
| 6 | ![](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/kho-hang/img/6.PNG) | Hỗ trợ bạn kiểm soát lượng tồn mong muốn trong kho theo sản phẩm, trong đó thông báo chính xác số lượng tồn hiện tại, tồn tối thiểu, tồn tối đa mong muốn của sản phẩm đó |
| 7 | ![](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/kho-hang/img/7.PNG) | Giúp bạn tiết kiệm thời gian trong việc tìm kiếm sản phẩm ở vị trí nào trong kho hàng (thường áp dụng với các kho hàng có diện tích lớn và người quản lý muốn tối ưu việc quản lý sản phẩm tồn kho của mình) |
| 8 | ![](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/kho-hang/img/8.PNG) | Phần mục này dựa theo những công thức cho trước để **gợi ý** cho bạn tình hình bán hàng sắp tới để tính toán số lượng hàng cần nhập sắp tới nhằm mục đích hỗ trợ tối ưu hóa việc kinh doanh của bạn |
| 9 | ![](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/kho-hang/img/9.PNG) | Thường dùng cho những doanh nghiệp nhượng quyền thương hiệu. Hỗ trợ kiểm soát việc xuất bán và xem tồn kho sản phẩm bán chéo giữa 2 doanh nghiệp với nhau | 

# Các khái niệm chính được sử dụng trong Kho Hàng

Các loại ID, bao gồm:

| STT | Các loại ID | Ý nghĩa |
|-----|-------------|---------|
| 1 | ID phiếu XNK | Mỗi phiếu XNK sẽ được hệ thống cấp cho 1 ID riêng|
| 2 | ID sản phẩm XNK | Trong mỗi phiếu XNK sẽ có 1 hoặc nhiều sản phẩm XNK, mỗi sản phẩm XNK đó được hệ thống cấp cho 1 ID riêng|
| 3 | ID phiếu yêu cầu XNK | Khi tạo 1 phiếu yêu cầu XNK, hệ thống sẽ gắn 1 ID riêng cho phiếu đó, không phải là ID của phiếu XNK|
| 4 | ID sản phẩm yêu cầu XNK | Trong mỗi phiếu yêu cầu XNK sẽ có 1 hoặc nhiều sản phẩm yêu cầu XNK, hệ thống sẽ gắn cho mỗi sản phẩm đó 1 ID riêng, không phải là ID sản phẩm XNK |
| 5 | ID phiếu kiểm kho | Khi bạn tạo 1 phiếu kiểm kho thì hệ thống sẽ cấp một ID riêng cho phiếu đó|
| 6 | ID sản phẩm kiểm kho | Trong mỗi phiếu kiểm kho có thể có 1 hoặc nhiều sản phẩm được kiểm kho, mối sản phẩm trong phiếu kiểm kho được hệ thống gắn cho 1 ID riêng|
| 7 | ID phiếu bảo hành | Khi khách hàng mang sản phẩm đến bạn để bảo hành hoặc sửa chữa, hệ thống sẽ sinh phiếu bảo hành và gắn ID riêng cho phiếu bảo hành đó|
| 8 | ID phiếu XNK bị xóa | Khi xóa 1 phiếu XNK trong danh sách phiếu XNK thì ID của phiếu XNK đó cũng chính là ID trong danh sách phiếu XNK bị xóa|

Loại XNK: bao gồm Xuất kho và Nhập kho

Kiểu XNK: bao gồm:

| STT | Kiểu Xuất nhập kho | Ý nghĩa |
|-----|--------------------|---------|
| 1 | [N] Nhà cung cấp | Nhập hàng từ nhà cung cấp, xuất trả lại hàng cho nhà cung cấp|
| 2 | [C] Chuyển kho | Chuyển hàng giữa các kho trong doanh nghiệp của bạn|
| 3 | [G] Giao hàng | Xuất bán online, nhập lại đơn hàng bị chuyển hoàn|
| 4 | [L] Bán lẻ | Xuất bán lẻ, Nhập lại trong trường hợp khách trả lại hàng|
| 5 | [B] Bán buôn | Xuất bán buôn, Nhập lại trong trường hợp khách trả lại hàng|
| 6 | [T] Hàng tặng kèm | Xuất hàng tặng kèm khi mua sản phẩm, Nhập lại trong trường hợp khách trả lại sản phẩm và hàng tặng kèm|
| 7 | [K] Bù trừ kiểm kho | Hệ thống tự động tạo các phiếu Xuất hoặc Nhập kho để bù trừ lại số lượng chênh lệch giữa tồn trên hệ thống và tồn thực tế khi kiểm kho|
| 8 | [#] Kiểu khác | Xuất nhập kho này không ghi nhận vào doanh thu|
| 9 | [BH] Bảo hành, [SC] Sửa chữa | Nhập hàng để bảo hành, sửa chữa, Xuất trả hàng cho khách|
| 10 | [TTBH] Trung tâm bảo hành | Bạn xuất hàng sang Trung tâm bảo hành để bảo hành, sửa chữa máy, và Nhập hàng từ Trung tâm bảo hành về kho của bạn khi quá trình bảo hành sửa chữa hoàn tất|
| 11 | [LKBH] Linh kiện bảo hành | Dùng để Xuất, nhập linh kiện phụ vụ cho việc bảo hành, sửa chữa|
 
 
