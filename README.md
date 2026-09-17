# Mini-Go-Pos
Sự chuyển đổi số trong ngành bán lẻ đặt ra yêu cầu cấp thiết về các ứng dụng quản lý
điểm bán hàng có khả năng vận hành chính xác, đồng bộ hóa dữ liệu nhanh chóng và tối
ưu hóa trải nghiệm người dùng. Đáp ứng nhu cầu thực tiễn đó, ứng dụng quản lý siêu thị
quy mô vừa và nhỏ đươc phát triển hoàn toàn trên nền tảng ngôn ngữ C++. 

Mục tiêu cốt lõi của hệ thống là tự động hóa quy trình quản lý giao dịch, loại bỏ rủi ro sai sót từ các
thao tác thủ công và bảo chứng tính toàn vẹn tuyệt đối cho cơ sở dữ liệu lưu trữ. Ứng
dụng vận hành dựa trên kiến trúc MVC-lite, thiết lập ranh giới độc lập giữa tầng giao
diện người dùng (GUI) và tầng xử lý logic. 

Nền tảng kiến trúc này áp đặt một luồng xử lý dữ liệu khép kín và nghiêm ngặt: tiếp nhận thông tin, 
kiểm chứng tính hợp lệ , kết xuấtlên bộ nhớ tạm và đồng bộ hóa bền vững xuống hệ thống tệp tin kèm theo cơ chế lưu vết
nhật ký tự động theo thời gian thực. Hệ thống cung cấp một chu trình quản lý toàn diện,bao quát từ khâu nạp dữ liệu ban đầu, kiểm soát phiên làm việc (Mở/Kết ca), đến phân hệ xử lý giao dịch thương mại (Nhập kho, Xuất kho, Bán hàng) và hệ thống sổ ghi chú. Đặc
biệt, cấu trúc mã nguồn khai thác triệt để bốn đặc tính cốt lõi của Lập trình Hướng đối tượng bao gồm: Đóng gói, Kế thừa và Đa hình, Trừu tượng.
- Đóng gói: Mọi thao tác kiểm duyệt, tính toán và lưu trữ phải đi qua các phương
thức chuẩn hóa của lớp điều khiển nhằm đảm bảo an toàn bộ nhớ.
- Kế thừa: Cấu trúc mã nguồn thiết lập một lớp nền Transaction chứa các thuộc tính
và phương thức quản lý mảng dữ liệu tạm, làm nền tảng mở rộng trực tiếp cho các
phân hệ giao dịch cụ thể bao gồm Invoice, Import, và Export.5
- Đa hình: Cơ chế lưu trữ đa hình cho phép hệ thống tự động định tuyến và xuất dữ
liệu vào các tệp đích tương ứng thông qua một lệnh gọi kích hoạt duy nhất từ
người dùng.
- Trừu tượng: Phần mềm che giấu toàn bộ độ phức tạp của thuật toán xử lý cấp thấp
mang lại trải nghiệm tương tác liền mạch, đơn giản hóa cho người dùng cuối tại
tầng giao diện.
Cách tiếp cận này không chỉ giải quyết trọn vẹn các yêu cầu nghiệp vụ hiện tại mà còn
thiết lập một bộ khung phần mềm linh hoạt, có tính mở rộng cao và tuân thủ các tiêu
chuẩn kỹ thuật phần mềm hiện đại.

<img width="863" height="469" alt="image" src="https://github.com/user-attachments/assets/988459a8-4f11-4e77-a96e-abfd29c8a27d" />
