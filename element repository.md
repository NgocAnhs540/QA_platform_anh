# Định nghĩa

Element Repository là kho lưu trữ các Element trong dự án. Element Repository cho phép quản lý các thuộc tính của phần tử trong đó, bao gồm loại phần tử, name, xpath ...

Một Element có thể xuất hiện trong nhiều bước của các luồng nghiệp vụ khác nhau, khi đó Repository cho phép chia sẻ thuộc tính với các test case khác nhau cùng sử dụng Element này.

Trong quá trình phát triển phần mềm, các thuộc tính của phần tử có thể thay đổi để phù hợp hơn với mục đích sử dụng của người dùng. Khi đó, nhân viên kiểm thử sẽ phải rà soát các phần tử có thay đổi trong cấu hình test case của dự án và chỉnh sửa. Đối với các phần tử xuất hiện nhiều lần trong các test case sẽ gây khó khăn trong việc kiểm soát dữ liệu chưa/ đã chỉnh sửa dẫn đến bỏ sót.

Sử dụng Element Repository trong cấu hình test case giúp nhân viên kiểm thử chỉ cần chỉnh sửa một lần trong thư viện repository đối với mỗi phần tử, dữ liệu sẽ được tự động cập nhật vào cấu hình test case, từ đó giảm thời gian chỉnh sửa và ngăn chặn nguy cơ bỏ sót.

