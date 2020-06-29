# Chuyển kho

Khi quản lý nhiều cửa hàng và muốn chuyển hàng từ cửa hàng này sang cửa hàng khác, bạn dùng tính năng Chuyển kho.

Ví dụ: Bạn có 2 kho, muốn chuyển bớt 3 chiếc 'Quần HM 001 - Đen ZZZ ' từ kho Thái Hà sang kho Chùa Bộc, quy trình như sau:
## Bước 1: Kho A tạo phiếu chuyển kho [tại đây](https://new.nhanh.vn/inventory/transfer/add)
![](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/kho-hang/img/tao-phieu-ck1.jpg)

- Điền thông và ấn nút "Lưu" hoặc "Lưu và In"

## Hệ thống sẽ sinh ra:
- 1 phiếu Xuất [chuyển kho] từ kho Thái Hà --> kho Chùa Bộc. Số tồn ở kho A giảm 3, tuy nhiên số tồn ở kho Chùa Bộc chưa tăng. 3 sản phẩm này ở trạng thái Đang chuyển kho
![](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/kho-hang/img/phieu-yeu-cau-ck1.jpg)

- 1 phiếu yêu cầu Xuất [chuyển kho].

## Bước 2: Sau khi nhận được hàng, Kho Chùa Bộc cần xác nhận phiếu này (Tại [Sắp chuyển đến](https://new.nhanh.vn/inventory/transfer/draft?tab=waitingConfirm))

![](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/kho-hang/img/phieu-xac-nhan-ck3.png)

## Bước 3: Sau khi xác nhận phiếu, hệ thống sẽ chuyển sang giao diện xác nhận chuyển kho. Điền số lượng hàng xác nhận chuyển kho và ấn nút Lưu hoặc Lưu và In
![](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/kho-hang/img/xac-nhan-ck1.png)

## Bước 4: hệ thống tự tạo 1 phiếu Nhập [chuyển kho] để tăng số tồn ở của kho Chùa Bộc thêm 3.
![](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/kho-hang/img/phieu-ck-tu-A-sang-B.jpg)
Bạn có thể tham khảo video hướng dẫn sử dụng tại đây:

