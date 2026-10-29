# Tài Lê MMO

Công cụ tạo giọng đọc cho Windows 10/11 64-bit.

## Tải và cài đặt

[Tải bộ cài mới nhất](https://github.com/Taikoljmjjk/voice-tai-le/releases/latest/download/Tai-Le-MMO-1.2.0-Setup.exe)

[Xem các bản phát hành](https://github.com/Taikoljmjjk/voice-tai-le/releases)

- Cài mới: chạy file Setup; bộ cài tự tải và kiểm tra SHA-256 của mô hình, Python và thư viện đi kèm.
- Đã có bản 1.1.0: đóng ứng dụng và chọn đúng thư mục đang dùng để nâng cấp, không cần tải lại mô hình.
- Chọn thư mục cài không dấu để dùng Kokoro. Thư mục phải có quyền ghi.
- Bản thu và cài đặt nằm trong `data` cạnh EXE; hãy sao lưu trước khi chuyển máy.

## Tự động cập nhật từ 1.2.0

Ứng dụng tự kiểm tra phiên bản và tải gói cập nhật khi khởi động. Khi bản mới đã được kiểm tra SHA-256, nhấn **Khởi động lại & cập nhật**. Có thể tắt kiểm tra tự động trong tab Cài đặt.

Gói cập nhật chỉ thay mã ứng dụng trong `resources/app`, giữ nguyên mô hình, bản thu và khóa API. Bản ứng dụng trước được lưu trong `data/updates/backups`. Nếu thay tệp hoặc khởi chạy gặp lỗi, bộ áp dụng cập nhật khôi phục mã ứng dụng trước đó.

Bản 1.1.0 chưa có tự cập nhật nên cần chạy bộ cài 1.2.0 một lần.


## Bản Thanh Voice Studio

[Tải Thanh-Voice-Studio-1.2.0-Setup.exe](https://github.com/Taikoljmjjk/voice-tai-le/releases/download/v1.2.0/Thanh-Voice-Studio-1.2.0-Setup.exe)

Bản Thanh Voice Studio giữ tên và thông tin nhà phát triển Lê Xuân Thanh — Trung tâm Dịch vụ tổng hợp xã Lê Lợi — 0926.251.358. Cài vào thư mục riêng với Tài Lê MMO. Đã dùng Thanh Voice 1.1.0: đóng ứng dụng rồi chạy bộ cài này và chọn đúng thư mục cũ để bật tự cập nhật.

Kênh Thanh Voice dùng `update-manifest-thanh-voice.json`, gói `Thanh-Voice-Studio-1.2.0-app.zip` và kiểm tra danh tính `thanh-voice-studio`. Kênh Tài Lê MMO tiếp tục dùng `update-manifest.json`; hai sản phẩm không đổi tên khi cập nhật. Chọn đường dẫn không dấu để dùng Kokoro.

## Tệp phát hành

- `Tai-Le-MMO-1.2.0-Setup.exe`: bộ cài nhỏ, tự tải dữ liệu cho lần cài mới.
- `Tai-Le-MMO-1.2.0-app.zip`: mã ứng dụng cho kênh cập nhật.
- `update-manifest.json`: phiên bản, kích thước, địa chỉ tải và SHA-256.
- `Tai-Le-MMO-1.1.0-Setup.exe.001` / `.002`: dữ liệu bộ cài đầy đủ, được Setup tự tải và ghép; không chạy trực tiếp các tệp này.
- `SHA256SUMS.txt`: mã kiểm tra tệp.

Bộ cài chưa ký số. Dịch vụ online cần Internet; AI33Pro/VIMIX dùng khóa API của người sử dụng. Thông tin bản quyền thư viện và mô hình được giữ trong bộ cài.

Nhà phát triển: **Tài Lê MMO — 0394342601**.
