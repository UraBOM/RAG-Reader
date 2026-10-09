# Quyền riêng tư — RAG Reader Beta

- Project Map, quét thư mục và đọc tệp được thiết kế để chạy cục bộ trên máy người dùng. Người dùng chủ động chọn thư mục/file muốn truy cập.
- Ứng dụng dùng máy chủ HTTP cục bộ `127.0.0.1` và phiên truy cập riêng cho cửa sổ RAG Reader để giảm khả năng trang web khác đọc nội dung qua cổng cục bộ.
- Dữ liệu ứng dụng như ghi chú/tiến trình đọc có thể được lưu trong thư mục dữ liệu người dùng của Windows (`%APPDATA%\RAG Reader`).
- **Tính năng dịch trực tuyến:** khi người dùng yêu cầu dịch, văn bản cần dịch có thể được gửi qua Internet tới dịch vụ dịch bên thứ ba. Không dùng tính năng này với tài liệu bí mật nếu chưa được phép.
- Không đính kèm mã nguồn dự án, khóa API, dữ liệu nội bộ vào GitHub Issues công khai.

Bản Beta chưa trải qua kiểm toán bảo mật độc lập; không nên dùng như kho lưu trữ bí mật hoặc môi trường cách ly an toàn.
