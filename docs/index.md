# Welcome to Hyperledger
## Hyperledger là gì?

**Hyperledger (hoặc dự án Hyperledger)** là dự án mã nguồn mở được tạo ra để thúc đẩy công nghệ blockchain xuyên suốt ngành công nghiệp. Được ra đời vào tháng 12/2015 bởi Linux Foundation và được hỗ trợ bởi các công ty lớn như IBM, Intel và SAP giúp phát triển cộng tác của sổ cái phân tán dựa trên blockchain.

Hyperledger là một sự hợp tác toàn cầu của các nhà lãnh đạo trong ngân hàng, tài chính, Internet of Things, sản xuất, chuỗi cung ứng, và công nghệ. Nhằm tạo ra các khung blockchain sổ kế toán mở và tiêu chuẩn hóa và các cơ sở mã để tạo ra kết quả kinh doanh hữu hình.

**Linux Foundation** là một tổ chức phi lợi nhuận cho phép đổi mới hàng loạt thông qua mã nguồn mở, lưu trữ Hyperledger. Linux Foundation cũng cho phép cộng đồng các nhà phát triển trên toàn thế giới làm việc cùng nhau và chia sẻ ý tưởng, cơ sở hạ tầng và mã code.

## Các dự án của Hyperledger

### Hyperledger Sawtooth

Hyperledger Sawtooth là một bộ khối chuỗi mô-đun được phát triển bởi Intel, sử dụng thuật toán đồng thuận mới có tên là Proof of Elapsed Time (PoeT).Nhằm mục tiêu xác nhận các quần thể phân phối lớn với mức tiêu thụ tài nguyên tối thiểu để xây dựng, triển khai và chạy các sổ cái được phân phối. Sawtooth hỗ trợ các hợp đồng thông minh Ethereum thông qua “seth” (một bộ xử lý giao dịch Sawtooth tích hợp EVW Hyperledger Burrow). Ngoài hỗ trợ Solidity, Sawtooth bao gồm các SDK cho Python, Go, Javascript, Rust, Java và C ++.

### Hyperledger Fabric

Hyperledger Fabric là một cơ sở hạ tầng blockchain được phép, ban đầu được đóng góp bởi IBM và Digital Asset, cung cấp kiến ​​trúc mô đun với phân định vai trò giữa các nút trong cơ sở hạ tầng, thực hiện Hợp đồng thông minh (gọi là “chaincode” trong Fabric) và sự đồng thuận có thể cấu hình và dịch vụ thành viên. Mạng lưới Fabric bao gồm “Nút ngang hàng”, thực thi mã chuỗi, dữ liệu sổ kế toán truy cập, xác nhận giao dịch và giao diện với các ứng dụng. “Các nút của trình đặt hàng” đảm bảo tính nhất quán của blockchain và phân phối các giao dịch được xác nhận cho các đồng nghiệp của mạng và dịch vụ MSP, thường được thực hiện dưới dạng Cơ quan cấp chứng chỉ, quản lý chứng chỉ X.509 được sử dụng để xác thực danh tính và vai trò của thành viên.

Fabric chủ yếu dùng để tích hợp các dự án, trong đó yêu cầu Công nghệ Ledger phân tán (DLT), không cung cấp dịch vụ nào cho người dùng ngoài SDK cho Node.js, Java và Go (thông qua Hyperledger Composer, hoặc nguyên bản từ v1.1) out-of-the-box. Do đó, nó có khả năng linh hoạt hơn các đối thủ cạnh tranh chỉ hỗ trợ một ngôn ngữ hợp đồng thông minh đã đóng.

### Hyperledger Iroha

Hyperledger Iroha bắt nguồn từ một số nhà phát triển ở Nhật Bản đã xây dựng công nghệ blockchain của riêng họ cho một vài trường hợp sử dụng di động. Behlendorf cho biết: “Iroha được thực hiện bằng C ++, có thể có hiệu suất cao hơn đối với dữ liệu nhỏ và các trường hợp sử dụng tập trung”.  Được phát triển bởi Soramitsu, Iroha phân phối theo mô đun dễ sử dụng với các thuật toán dịch vụ đặt hàng và đồng thuận độc đáo của riêng mình, mô hình quyền dựa trên vai trò phong phú và hỗ trợ đa chữ ký.

### Hyperledger Burrow

Hyperledger Burrow được phát hành vào tháng 12/ 2014, Burrow cung cấp một máy khách blockchain kiểu mô-đun với một thông dịch viên hợp đồng thông minh được phép được xây dựng một phần cho đặc tả của Ethereum Virtual Machine (EVM). Burrow được hỗ trợ bởi Monax và Intel và được viết bằng ngôn ngữ lập trình Solidity.

### Hyperledger Indy 

Hyperledger Indy là một sổ kế toán phân tán, được xây dựng theo mục đích cho bản sắc phi tập trung. Nó cung cấp các công cụ, thư viện và các thành phần tái sử dụng để tạo và sử dụng các nhận dạng kỹ thuật số độc lập bắt nguồn từ các blockchain hoặc các sổ cái khác được phân phối cho khả năng tương tác, hỗ trợ danh tính độc lập trên sổ cái phân tán. Indy được phát triển bởi Sovrin Foundation. Trong bản Experian hack, Behlendorf cho biết phần mềm blockchain của Indy dựa trên việc giảm thiểu dữ liệu. Các công ty không phải lưu trữ nhiều dữ liệu cá nhân. Họ có thể lưu một con trỏ vào danh tính.

## Ưu điểm của Hyperledger

### Tính ẩn danh

Các transaction trên hyperledger đều được lưu trên các chanel (kênh) riêng biệt mà chỉ những người tham gia vào kênh đó mới có thể xem và sử dụng các giao dịch trên kênh.

### Mạng cấp phép

Mạng Hyperledger được thiết lập giữa những người tham gia hữu danh (các tổ chức, doanh ngiệp) chứ không phải là người dùng ẩn danh như trên mạng Ethereum hoặc Bitcoin. Hyperledger thiết lập sự tin cậy phi tập trung giữa các người dùng hữu danh dựa trên công nghệ Blockchain

### Dễ dàng bắt đầu (chưa chính xác)

Không giống như các mạng lưới Blockchain khác sử dụng ngôn ngữ riêng của chúng để viết smart contract, mạng Hyperledger cho phép viết smart contract bằng các ngôn ngữ quen thuộc như Golang, Nodejs và Java.

