# Thêm sản phẩm
* Mỗi khi doanh nghiệp/shop có những mặt hàng mới về cần quản lý thông tin dữ liệu chúng ta sẽ thao tác trên module sản phẩm để thêm mới sản phẩm.
* Một sản phẩm là một mặt hàng , Thêm mới sản phẩm là bước quan trọng để có thể hành động với các nghiệp vụ khác như bán hàng, xuất nhập kho của doanh nghiệp đó.
# Có hai cách thêm sản phẩ
* Cách 1: Thêm mới từng sản phẩm, khi doanh nghiệp có ít sản phẩm cần thêm.
* Cách 2: Thêm mới hàng loạt bằng file excel, khi doanh nghiệp có nhiều sản phẩm.
# Thao tác
Để sử dụng tính năng Thêm mới sản phẩm bạn thao tác theo các bước sau:
## Thêm mới từng sản phẩm
Truy cập lần lượt vào Sản phẩm / nhấn Thêm mới / , hoặc truy cập tại [đây](https://new.nhanh.vn/product/item/add).

![](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/san-pham/img/sp-themsp-formdongian.png)

* Thông tin cơ bản: Nhập Tên, ảnh, mã sản phẩm, danh mục, giá nhập, giá bán, giá buôn, tồn đầu...
* Thuộc tính và sản phẩm con: Nhập các thuộc tính cho sản phẩm. khi muốn tạo các sản phẩm con theo thuộc tính . 

:warning: Lưu ý : nếu tạo sản phẩm con thì bạn KHÔNG nhập số lượng sản phẩm ở tab Thông tin cơ bản, mà nhập số lượng cho từng sản phẩm con. 
Xem thêm cách tạo thuộc tính tại [đây](https://manual.nhanh.vn/san-pham/them-san-pham/tao-thuoc-tinh-cho-san-pham).
* Bảo hành và vận chuyển: Nhập các thông tin cần thiết trong trường hợp doanh nghiệp có dùng module Bảo hành sửa chữa và Dịch vụ vận chuyển của Nhanh.vn
* Website: Nhập các thông tin cần thiết trong trường hợp có sử dụng website do Nhanh.vn cung cấp.

**Video hướng dẫn thêm sản phẩm**

## Import sản phẩm bằng file Excel
Truy cập lần lượt vào Sản phẩm / nhấn Nhập từ Excel  hoặc truy cập tại [đây](https://new.nhanh.vn/product/item/add?tab=excel).
### Bước 1: Chọn ngành hàng
* Chung: Dùng để Import những sản phẩm không cần phân chia thuộc tính như : mỹ phẩm, đồ gia dụng, công nghệ...
* Nhà bếp: Dùng để Import những sản phẩm là đồ dùng nhà bếp.
* Thời trang: Dùng để Import những sản phẩm có thuộc tính, các sản phẩm thời trang như: quần áo, giày dép, mũ nón,...

#### Import nhập mới: Nhập mới (lần đầu) sản phẩm mới vào hệ thống.
* Cập nhật sản phẩm (thay đổi thông tin những sản phẩm đã có trên hệ thống).
* Cập nhật thuộc tính sản phẩm (định nghĩa cha con): Với trường hợp này, file Excel Import Sẽ cần điền thêm cột "Mã sản phẩm cha" trong file Import.
* Cập nhật khác: Những cập nhật về thông tin sản phẩm như: thêm ảnh sản phẩm, thêm ảnh thuộc tính, phân thuộc tính (tạo thêm sản phẩm con), thay đổi giá ...

![](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/san-pham/img/sp-themsp-excel-1.png)
 
### Bước 2: Tải file Excel mẫu
### Bước 3: Nhập liệu vào file Import
* Mở file Import, mẫu file Excel gồm 2 sheet : Ghi chú (hướng dẫn tạo dữ liệu) và Sản phẩm (thực hiện thao tác nhập dữ liệu):
  * Đối với nghành hàng thời trang (ngành hàng phức tạp nhất), doanh nghiệp cần tìm hiểu các ghi chú về file để nhập liệu chuẩn xác.
  * Nhập liệu sản phẩm, thông tin liên quan đến sản phẩm vào file Import. Phụ thuộc vào mức độ sử dụng chi tiết hay không của doanh nghiệp mà doanh nghiệp tùy chọn nhập liệp tại những trường nào. 
  * Những mục không nên bỏ qua gồm: Tên sản phẩm, Mã sản phẩm, Giá nhập, Giá bán (Giá bán lẻ, Giá bán buôn), Thuộc tính sản phẩm, ...
**Giao diện của file sau khi nhập liệu vào file như sau:**

![](https://github.com/nhanhapi/manual/blob/master/docs/san-pham/img/sp-themsp-excel-2.png)

Sau khi nhập liệu đầy đủ thông tin, doanh nghiệp Lưu file lại sau đó có thể kiểm tra ở phần [Danh sách sản phẩm](https://new.nhanh.vn/product/item/index)

![](https://github.com/nhanhapi/manual/blob/master/docs/san-pham/img/sp-themsp-dssp-new.png)

### Bước 4: Import file lên hệ thống
* Tại giao diện làm việc của Import sản phẩm, bạn rà soát lại các trường thông tin như chọn ngành hàng, chọn cửa hàng, loại import (thêm mới / cập nhật). sau đó
  * Chọn file excel vừa nhập liệu đầy đủ thông tin sản phẩm
  * Click vào nút Import để tiến hàng tải dữ liệu lên hệ thống.
  * Sau khi tải xong, hệ thống cảnh báo nghiệp vụ Import thành công hay thất bại
  * Xác nhận Import sản phẩm thành công, bạn kiểm tra Danh sách sản phẩm vừa Import tại trang [Danh sách sản phẩm](https://new.nhanh.vn/product/item/index)

**Video hướng dẫn import sản phẩm bằng file Excel:**

**:exclamation:Một số lưu ý khi Import sản phẩm ngành hàng Thời trang**

Không bắt buộc nhập Tên các sản phẩm chứa màu sắc, size số, hệ thống hỗ trợ tự sinh thêm các sản phẩm con theo các thuộc tính (màu, size) đã nhập ở trường sản phẩm cha. 

- Trường hợp 1: 

Điền màu vào cột [M] và size vào cột [S]. Hệ thống tự động tạo ra các sản phẩm con theo số tổ hợp của 2 cột [M] và [S].

Ví dụ: Sản phẩm "Áo T45" điền cột [M] có 3 màu, cột [S] có 2 size thì hệ thống tự sinh thêm 6 sản phẩm con có tên theo dạng "Áo T45 màu ... size ...".

- Trường hợp 2: 

Điền màu và size vào cột [M-S] (dùng khi sản phẩm mỗi màu có các size khác nhau). Điền theo dạng Mã màu - Mã các size; lần lượt cho tất cả các màu sản phẩm, hệ thống tự động tạo ra các sản phẩm con tương ứng với thông tin đã điền.

**Sau khi import lần đầu để hệ thống sinh thêm các sản phẩm con thì mới nên thực hiện cập nhật ảnh sản phẩm vào hệ thống. Quy trình như sau:**

 :heavy_check_mark: Bước 1: Vào phần Danh sách sản phẩm để Export danh sách sản phẩm mới (có cả các dòng sp con).
 
 :heavy_check_mark: Bước 2: Copy các cột tên sản phẩm và mã sản phẩm vào mẫu file import, điền thêm tên đầy đủ file ảnh (tên+đuôi file) vào cột Ảnh.
 
 :heavy_check_mark: Bước 3: Upload file ảnh trước khi import (có thể upload nhiều file một lúc).
 
 :heavy_check_mark: Bước 4: Chọn kiểu import "Cập nhật thông tin", chọn file import mới điền và click Import.

---
**:pushpin: Một số các lưu ý**
- Những trường thông tin có dấu "![](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/san-pham/img/sao.png)" *có nghĩa là **bắt buộc** phải nhập* . **Điều kiện tối thiểu: Tên sản phẩm, Loại sản phẩm.**
- Nên có mã sản phẩm hoặc mã vạch sản phẩm (tự động sinh trên hệ thống hoặc doanh nghiệp tự tạo mã riêng), mã sản phẩm nên có cả chữ cái và chữ số, được hiểu là thông tin định danh thứ 2 của sản phẩm sau "Tên".
- Nếu điền tồn đầu, **phải** khái báo ô giá nhập.
- Danh mục có thể đc tạo nhanh ngay trong lúc tạo mới sản phẩm, sản phẩm  rất nên được phân loại theo danh mục.
- Thêm mới sản phẩm nên khai báo chi tiết thì quá trình tìm kiếm, tra cứu thông tin càng trở nên đơn giản hơn.
- Nên thêm ảnh sản phẩm sau khi tạo thông tin.
---
**:question: Một số câu hỏi thường gặp**
* Sau khi thêm mới xong , nhưng muốn thêm các sản phẩm con thì sao ?

  Thao tác chia lại thuộc tính hoặc Import cập nhật lại thông tin sản phẩm cha con ( nếu đã có sẵn các sản phẩm cha con ).
* Muốn thêm các thuộc tính khác để hiển thị khi thêm mới sản phẩm có được không ?

  Thao tác ở phần thuộc tính > thêm mới thuộc tính cần thiết


