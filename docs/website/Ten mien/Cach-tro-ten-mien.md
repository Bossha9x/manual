# Cách trỏ tên miền

Sau khi mua tên miền, nhà cung cấp sẽ gửi đến người mua một email với các thông tin:

- Đường link trang quản trị tên miền
- Usename và mật khẩu đăng nhập vào trang quản trị tên miền.

![](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/website/img/cach-tro-ten-mien1.png)

Ví dụ: Doanh nghiệp mua tên miền "demo.vn" và muốn trỏ tên miền này về website của Nhanh

## Bước 1: Đăng nhập vào trang quản trị tên miền
## Bước 2: Chọn mục cấu hình DNS
- Click nút Thêm mới để thêm 2 giá trị sau (hoặc sửa 2 giá trị, nếu tên miền đã được sử dụng trước đó)

+ Giá trị 1: Tại ô Host, điền "@" ==> chọn Loại A ==> nhập địa chỉ **104.155.234.35** (là địa chỉ IP của Nhanh.vn)

+ Giá trị 2: Tại ô Host, điền "www" ==> chọn loại A ==> nhập địa chỉ **104.155.234.35** (là địa chỉ IP của Nhanh.vn)

![](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/website/img/cach-tro-ten-mien-2.PNG)

![](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/website/img/cach-tro-ten-mien-3.PNG)

Lưu ý: Với tên miền cấp 2, cấp 3, ví dụ store.demo.vn thì trường Name này nhập chữ store, nếu doanh nghiệp muốn trỏ tên là abc.store.demo.vn thì nhập chữ abc.store)

Đặc biệt lưu ý: Ngoài 2 giá trị @ và www thì không Thêm/ Sửa bất kì 1 giá trị nào khác nếu không hiểu cách hoạt động của nó.

Chú ý: Sau khi bạn trỏ tên miền, tùy vào hệ thống DNS của nhà cung cấp dịch vụ tên miền, có thể mất từ 5 phút tới 3 tiếng để tên miền có thể chuyển sang địa chỉ hosting vừa mới cập nhật.

Bạn có thể kiểm tra xem tên miền đã về địa chỉ IP hosting mới hay chưa bằng cách:

- Cách 1: Trên Windows bấm nút Windows + R, gõ cmd và nhấn Enter, gõ: ping địa chỉ tên miền xong nhấn Enter (VD: ping captot.vn)

- Cách 2: Vào trang https://ipinfo.info/html/ip_checker.php nhập địa chỉ tên miền của bạn xong nhấn nút Check. Khi dòng IP Address có giá trị 104.155.234.35 nghĩa là bạn tên miền đã được trỏ thành công về hosting của Nhanh.vn

Bạn nên kiểm tra cả tên miền chính (VD captot.vn) và bản ghi www (VD: www.captot.vn) để đảm bảo chắc chắn cả 2 tên miền đã trỏ thành công.

![](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/website/img/cach-tro-ten-mien-4.PNG)

## Bước 3. Đổi tên miền cho *.store.nhanh.vn
Truy cập vào Website / Cài đặt website / Ngôn ngữ hoặc tại đây để thay đổi tên miền của *.store.nhanh.vn thành tên miền của doanh nghiệp.

![](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/website/img/cach-tro-ten-mien-5.PNG)

Nhân viên Support cần test lại website tại tên miền của doanh nghiệp trước khi đưa vào hoạt động.

# Trỏ tên miền redirect
Khi bạn có nhiều tên miền (thường mua để giữ chỗ tên miền / bảo vệ thương hiệu tránh bị đối thủ mua mất) và muốn chạy chung 1 website: Bạn không nên chạy song song các tên miền này, sẽ dễ bị các Search Engine phạt lỗi "Trùng lặp nội dung", làm giảm thứ hạng tìm kiếm, cách tốt nhất trong tình huống này là bạn chỉ nên chạy 1 tên miền chính, các tên miền phụ này điều hướng về tên miền chính. Các trỏ redirect tên miền phụ như sau:

Ví dụ bạn có 2 tên miền: caphocsinh.vn, captot.vn và muốn khi người dùng truy cập vào caphocsinh.vn, sẽ tự động được điều hướng (redirect) sang trang captot.vn, thì làm như sau:

Vào trang quản trị tên miền caphocsinh.vn, thêm 2 giá trị sau:

![](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/website/img/cach-tro-ten-mien-6.PNG)

**Chú ý:** Với các tên miền đã trỏ loại URL Redirect thì không cần trỏ tên miền loại A nữa.

# Trỏ tên miền từ Google domain

Bước 1: Bạn hãy truy cập vào https://domains.google.com/ và đăng nhập với tài khoản Google

Bước 2: Khai báo IP của Nhanh.vn: Điền đoạn IP "104.155.234.35" vào ô Địa chỉ IPv4 sau đó click Thêm

![](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/website/img/cach-tro-ten-mien-7.PNG)

Bước 3: Thêm các giá trị DNS như hình

![](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/website/img/cach-tro-ten-mien-8.PNG)
