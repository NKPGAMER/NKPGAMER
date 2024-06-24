# Wither Anti Cheat

**Wither Anti Cheat** là một plugin chống gian lận dành cho Minecraft Pocket Edition (PE) và Minecraft Bedrock Edition (BE). Plugin được thiết kế để bảo vệ máy chủ Minecraft của bạn khỏi các hành vi gian lận như sử dụng hack, cheat và các phương pháp không công bằng khác.

## Các tính năng chính

- ** Phát hiện, sử lý hack và cheat **
  1. **Anti Flying**: Ngăn chặn người chơi sử dụng hack bay.
  2. **Anti Teleport**: Ngăn chặn người chơi dịch chuyển tới vị trí khác.
  3. **Anti HightJump**: Ngăn chặn người chơi nhảy cao.
  4. **Anti Speed**: Ngặn chặn người chơi quá nhanh.
  
- **Quản lý các vụ nổ**:
  1. **Chặn toàn bộ vụ nổ**: Toàn bộ các vụ nổ sẽ không ảnh hưởng đến khối, người chơi.
  
  2. **Ngăn chặn TNT nổ hàng loạt**: Giới hạn các TNT trong thế giới. Tối đa mặc định là 3, nếu vượt quá 3 thì TNT khác sẽ không bị kích hoạt. Thay vào đó sẽ chờ đến khi số lượng TNT thấp hơn mới kích hoạt

- ** Giao diện người dùng **
  1. **Giao diện thành viên**
    Cung cấp giao diện mặc định cho toàn bộ người chơi
  Cho phép người chơi:
    - Tố cáo người chơi
    - Dịch chuyển đến các điểm dịch chuyển hoặc tạo các điểm dịch chuyển(nếu cho phép)
    - Sử dụng các tiện ích được hỗ trợ bởi Wither Anti Cheat
  
  2. **Giao diện người hỗ trợ**
    Giao diện này cho phép các người chơi được cấp quyền (đổi chế độ chơi, chỉnh thời gian,...). Nhưng vẫn bị hạn chế một vài tính năng nguy hiểm.
  Cho phép người chơi:
   # Sử dụng toàn bộ chức năng của **Giao diện người dùng**
   - Thay đổi thời gian
   - Thay đổi thời tiết
   - Lấy vật phẩm
   - Đổi chế độ chơi
   - Dịch chuyển tùy ý
  
  3. **Giao diện quản trị viên**
    Không bị hạn chế bởi bất kỳ chức năng nào.
  Cho phép:
   # Sử dụng toàn bộ chức năng.
   - Tạo điểm dịch chuyển cho tất cả người chơi.
   - Tạo văn bản nổi.
   - Quản lý người chơi.
   - Quản lý rankTag.
   - Tạo khu vực (có thể giới hạn quyền của mỗi khu vực)
    
- **Hệ thống cảnh báo và xử lý**: Cung cấp các cảnh báo chi tiết về hành vi nghi ngờ và có thể tự động xử lý các trường hợp để đảm bảo sự ổn định cho máy chủ.

## Hướng dẫn cài đặt
**Tải xuống**: Hãy tệp xuống từ trang Web chính thức của [Wither Anti Cheat](https://sites.google.com/view/wither-anti-cheat/wither-anti-cheat)

2. ** Thiết lập **
  1. Sau khi tải xuống hãy giải nén tệp [.zip]
  2. Mở thư mục và đi đến vị trí `.../scripts/$Data/`
  3. Mở tệp `Config.js`
  4. Sau đó hãy thay đổi `"YOUR_PASSWORD"` trong `"password": "YOUR_PASSWORD"` thành mật khẩu của bạn.
  5. Lưu lại.

**Nhập vào Minecraft**
 # Android 
  1. Sao chép thư mục gốc của Wither Anti Cheat
  2. Di chuyển đến `Android/data/com.mojang.minecraftpe/files/games/com.mojang/behavior_packs/`
  3. Dán thư mục vừa sao chép tại đó.
  
  * Nếu truy cập bị từ chối:
  - Nén thư mục gốc của Wither Anti Cheat thành tệp [.zip] sau đó đổi đuôi [.zip] thành [.mcpack]
  - Sử dụng ứng dụng có hỗ trợ nhập tệp [Đề xuất: "Zarchiver"] và nhập vào Minecraft;
 
 # IOS
  1. Sao chép thư mục gốc của Wither Anti Cheat
  2. 

## Hướng dẫn sử dụng

- **Bật và cấu hình plugin**: Sau khi cài đặt, bạn có thể cấu hình Wither Anti Cheat bằng cách chỉnh sửa các tùy chọn trong file cấu hình.

- **Quản lý cảnh báo và báo cáo**: Theo dõi và xử lý các cảnh báo được ghi lại để giữ cho máy chủ Minecraft của bạn sạch từ các hành vi gian lận.

## Đóng góp

Nếu bạn có ý tưởng hoặc phát hiện lỗi, xin vui lòng mở một issue trên GitHub hoặc đóng góp bằng cách gửi pull request. Chúng tôi rất hoan nghênh sự đóng góp của bạn để cải thiện plugin.

## Giấy phép

This project is licensed under the MIT License - see the LICENSE file for details.

Đây là một mẫu cơ bản giúp bạn bắt đầu với một tập tin README cho dự án "Wither Anti Cheat". Bạn có thể điều chỉnh và bổ sung thêm theo nhu cầu cụ thể của dự án của bạn.
