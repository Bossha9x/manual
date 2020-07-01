# Nguyên nhân hủy đơn hàng

## Khách hủy
  - **Đặt nhầm sản phẩm:** Khách hàng đặt mua nhầm sản phẩm. Khách hàng muốn hủy bỏ đơn hàng để đặt lại.
  - **Phí vận chuyển cao:** Khách hàng không muốn đặt mua sản phẩm với mức phí mà doanh nghiệp báo.
  - **Không muốn chuyển khoản:** Khách hàng không muốn chuyển khoản thanh toán trước đơn hàng cho bạn khách hàng sợ rủi ro cao.
  - **Đơn trùng:** Khách hàng đặt hàng 02 lần/ đơn hàng. Nhân viên chăm sóc cần hủy bớt 01 đơn trùng.
  - **Đã mua tại quầy:** Khách hàng đã đặt hàng online, tuy nhiên lại đến cửa hàng mua hàng. Nhân viên chăm sóc cần hủy bỏ đơn hàng đã được đặt trước đó.
  - **Khách không muốn mua nữa:** Khách hàng không muốn đặt mua đơn hàng đó nữa.
  - **Không chờ giao hàng được:** Do thời gian giao vận của bạn vượt quá thời gian cho phép nhận hàng của khách hàng.
  - **Lý do khác:** Những nguyên nhân khách quan, chủ quan khác ngoài những nguyên nhân trên.

--> Khi đó đơn hàng sẽ ở trạng thái **Khách hủy**

## Hệ thống hủy
  - **Không gọi được khách:** Sau thời gian chờ tối đa, nhân viên chăm sóc ghi chú không xác nhận đơn hàng được với khách hàng, hệ thống tự động hủy bỏ đơn hàng. 
  - **Hết hàng:** Hệ thống tự động hủy bỏ đơn hàng khi sản phẩm trong đơn hàng hết hàng tồn kho.
  - **Lý do khác:** Những nguyên nhân khách quan, chủ quan khác ngoài những nguyên nhân trên.
  
--> Khi đó đơn hàng sẽ ở trạng thái **Hệ thống hủy**

###  Hãng vẫn chuyển hủy
 Hãng vận chuyển không giao được đơn hàng cho khách hàng, hãng vận chuyển gửi trả đơn hàng về doanh nghiệp. Bạn cần xác nhận động thời hủy bỏ đơn hàng. 

--> Khi đó đơn hàng sẽ ở trạng thái **Hãng vận chuyển hủy**
