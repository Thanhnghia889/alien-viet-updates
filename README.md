# Alien Việt — bản cài Android

Công cụ dịch Anh → Việt khi chơi Alien Shooter World. Có nút nổi, dịch toàn màn hình hoặc tô vùng, kết quả hiện trong bảng riêng. Bản thử cần Android 8 trở lên, Google Play services và Internet. Đây là công cụ độc lập, không liên kết với Sigma Team.

**[Tải APK mới nhất](https://github.com/Thanhnghia889/alien-viet-updates/releases/latest)**

## Cài và cập nhật

1. Mở trang bản mới nhất, tải tệp `AlienViet-*.apk`, rồi xác nhận cài đặt trên Android.
2. Nếu đã cài 0.1.0, cài chồng 0.2.0 một lần để nhận chức năng cập nhật trong app. Giữ app cũ, không cần gỡ.
3. Các bản sau: mở Alien Việt → **Kiểm tra cập nhật** → **Tải cập nhật**. Cấp quyền cho Alien Việt cài bản mới khi được hỏi, sau đó xác nhận trong trình cài đặt Android.

App cũng tự kiểm tra khi mở, tối đa một lần/6 giờ. Tệp APK vẫn được tải qua Internet, nhưng được tải trực tiếp trong app; không cần quay lại GitHub mỗi lần. Android yêu cầu xác nhận cài và ứng dụng không tự cài âm thầm. Cập nhật cùng chữ ký giữ dữ liệu.

## Dữ liệu và giới hạn

Ảnh chỉ xử lý trên máy. Văn bản OCR gửi đến MyMemory để dịch online, có hạn mức miễn phí khoảng 5.000 ký tự/ngày theo nhà cung cấp. OCR lần đầu cần tải mô hình từ Google Play. Chất lượng dịch máy có thể sai; từ điển game đang được hoàn thiện. Bản thử đã qua build/lint/unit test; chưa kiểm tra thao tác trên điện thoại/game thật.

Kho này công khai **APK, thông tin cập nhật và ghi chú phát hành**. Mã nguồn được giữ riêng tư. App kiểm tra SHA-256, tên gói, phiên bản và chữ ký trước khi mở trình cài đặt. Không có khóa ký hoặc token GitHub trong kho này.

Địa chỉ metadata dành cho app: [update.json](https://github.com/Thanhnghia889/alien-viet-updates/releases/latest/download/update.json).
