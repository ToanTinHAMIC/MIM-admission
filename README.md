# Mô tả trang web

## Mô tả chung
- Trang được viết theo hướng một trang báo cung cấp thông tin về tuyển sinh và các hoạt động.
- Trang viết theo hướng SPA.
- Nội dung trang cung cấp được các thông tin về quy chế tuyển sinh, chương trình đào tạo, các hoạt động trong quá trình tuyển sinh (các bài báo).
- Trang được chia ra thành trang người dùng (trang thông tin), trang người viết và đăng bài, trang người quản trị.
- Trang người dùng được tối ưu về mặt giao diện và trải nghiệm người dùng với các thiết kế đẹp mắt và dễ sử dụng.
- Trang người quản trị và người viết bài được giản lược tối đa về giao diện người dùng nhưng đảm bảo được tính dễ tương tác, dễ sử dụng đồng thời sử dụng một đường link khác với link công khai cho người dùng để quản lý và duy trì tính bảo mật.

## Thành phần các trang
### 1. Trang người dùng
![Phác họa trang người dùng](/assets/images/userdemo.jpg "Trang người dùng")
- Phần thanh điều hướng mở ra các nội dung khác nhau hoặc dẫn đến trang chủ của Khoa, của trường
- Phần tin tức
  - Nằm chính giữa khung màn hình có các bài đăng với mỗi bài đăng gồm tiêu đề và mô tả ngắn.
  - Khi bấm vào bài đăng sẽ hiện ra toàn bộ bài đăng, có nút thoát ra.
  - Các bài đăng được sắp xếp theo thứ tự thời gian đăng bài từ mới nhất đến cũ nhất.
  - Bài đăng được cấu trúc chỉ gồm chữ, ảnh (có thể có bảng) để hỗ trợ tốt hơn quá trình lưu trữ (Theo hướng notebook (ipynb), có nút thêm đoạn văn hoặc thêm hình ảnh).
  - Cuối bài viết có thể có đường dẫn đến file văn bản thông báo đầy đủ.
- Phần các tin tức quan trọng
  - Nằm ở lề phải của khung màn hình liệt kê một số tin tức, thông báo quan trọng (mới nhất).
  - Chia thành hai mục là thông báo tuyển sinh và tin tức nổi trội (thông báo tuyển sinh nằm bên trên).
  - Khi bấm vào cũng mở tin tức như tin bình thường.
- Phần chatbot hỏi đáp hỗ trợ
  - Nằm ở lề trái của khung màn hình có thể bật tắt.
  - Hỏi đáp từng câu hỏi đơn lẻ.
- Các đường dẫn đến trang web, fanpage của Khoa, Trường nằm ở các vị trí khác.
### 2. Trang người viết bài
- Đăng nhập dựa trên tên tài khoản và mật khẩu do người quản trị cung cấp.
- Trang giúp người dùng viết bài đăng và quản trị bài đăng của cá nhân bao gồm viết thêm, sửa, xóa, thêm vào phần các tin tức quan trọng.
- Định hướng có thể viết bài đăng như ipynb tức có thể thêm mục để viết đoạn văn hoặc thêm mục để tải ảnh lên hoặc tạo bảng.
### 3. Trang người quản trị
- Đăng nhập dựa trên tên tài khoản và mật khẩu được định sẵn.
- Quản lý người đăng bài, tạo mới, xóa tài khoản người đăng bài trong đó chỉ yêu cầu thông tin về tên tài khoản và mật khẩu, không yêu cầu về thông tin cá nhân, sửa thông tin tài khoản người viết bài.
- Quản lý bài đăng, xóa bài đăng, thêm hoặc loại bỏ khỏi phần các tin tức quan trọng.
