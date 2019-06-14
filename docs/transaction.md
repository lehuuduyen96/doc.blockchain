# Transaction

Transaction là giao dịch chuyển đổi từ bên A sang bên B , Giao dịch có thể bao gồm contract, chữ ký, tiền ảo.
 

## Đặc điểm 

* `Broadcast` - Giúp các note có thể đảy dữ liệu mới cho các note khác .
* `Sync` - Giúp note mới tạo có thể kéo đầy đủ dữ liệu mới về .
* `Private key` - Tạo ra khóa chính cho 1 ví, tượng trưng 1 người sử dụng, Private key không thể cho mọi người biết .
* `Public key` - Khóa công khai được tạo ra từ khóa chính, Public key có thể  cho mọi người biết .
* `Address` - Là địa chỉ của ví, đóng vai trò cần có để thực thiện giao dịch. 

## Sync
    Khi mốt máy tính muốn tham gia mạng blockchain thì cần phải được đồng bộ dữ liệu
    với tất cả máy tính trong mạng (note). Note sẽ thực hiện quá trình kéo dữ liệu 
    các note xung quanh và so sanh với chính mình và so sánh để lấy kết quá giống nhiều 
    nhất
## Broadcast
    Khi một giao dịch được thêm vào hàng đợi trước khi vào block, note sẽ tự động đẩy 
    dữ liệu sang các note khác .
## Wallet 
    Wallet được tạo ra bao gồm các thành phần: 
* Private key
* Public key
* Address