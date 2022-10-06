# Create-Fabrica-Crawler-LTS
*Note: 
- Phần mềm là file rar trong file được tải về.
- Kiểm tra chrome và chrome driver phải cùng bản và là bản mới nhất để tránh bị dính lỗi capcha của Creative Fabrica.
- Bản ổn định hiện tại: 0.2.2.

*Bản 1.0.0:
- Hướng dẫn sử dụng phần mềm và logo phần mềm.

*Bản 0.5.1:
- Cào nhiều sản phẩm theo các link chứa trong file exel.
- Kiểm tra và khóa các nút trong quá trình cào sản phẩm.

*Bản 0.4.2:
- Đổi tên các file trong thư mục zip theo tên của sản phẩm.
- Lưu lại các trường còn thiếu cho lần chạy tiếp theo.
- Bổ sung chức năng cho nút dừng tiến trình.

*Bản 0.3.1:
- Thêm tùy chọn tải sản phẩm lên Trello.
- Tự động phân loại list sẽ được tải lên Trello theo loại mime.
- Custome title thẻ, mô tả theo snippet variable bao gồm: {mime} =  loại tài nguyên của sản phẩm (svg hoặc png), {day} = ngày hiện tại, {month} = tháng hiện tại , {year} = 2 số cuối năm hiện tại, {autonumber} = số tự động tăng bắt đầu từ 1 và sẽ được reset khi sang ngày mới, {title} = tên sản phẩm, {tags} = các tag được lấy trong sản phẩm.

*Bản 0.2.2:
- Thêm các thông báo chuẩn đoán lỗi.
- Chỉnh sửa cơ chế lấy file zip kèm dữ liệu ảnh và phân loại mime.

*Bản 0.2.1:
- Thêm các thông báo chuẩn đoán lỗi.

*Bản 0.2.0:
- Sku được định nghĩa dùng snippet variable bào gồm:{mime} =  loại tài nguyên của sản phẩm (svg hoặc png), {day} = ngày hiện tại, {month} = tháng hiện tại , {year} = 2 số cuối năm hiện tại, {autonumber} = số tự động tăng bắt đầu từ 1 và sẽ được reset khi sang ngày mới.
- Tải và lấy ảnh từ file zip của sản phẩm, phân loại sản phẩm (png hoặc svg).
- Lưu file zip vào thư mục được chọn trước đó.
- Sản phẩm đã có ảnh (chưa chuyển đổi dung lượng và kích thước).
- Thêm khả năng tùy chỉnh desc cho sản phẩm

*Bản 0.1.0:
- Tạo giao diện chia theo tab contol
- Cào theo 1 link sản phẩm gồm các thông tin: Tên( theo fabrica), Tags (theo fabria hoặc tự định nghĩa), Giá và giá discount( tư định nghĩa), Sold individual và downloadable (mặc định).
- Tự động lưu thông tin trước đó.
- Đang nhập bằng tài khoản của công ty.
