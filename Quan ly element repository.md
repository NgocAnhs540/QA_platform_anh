## Quản lý Element Repository

### Màn hình danh sách element repository

![ds1](/test-framework-api/guest/doc-file/doc-file/6b594236-071d-407a-b846-533055fadc72/ds1.png)

*Màn hình Element Repository Library*


| Label | Chức năng |
| ------ | ------ |
| ![lab1](/test-framework-api/guest/doc-file/doc-file/490acc87-972d-4b69-9396-9038c39c135c/lab1.png) | Dùng để hiển thị/ ẩn công cụ lọc, tìm kiếm element repository |
| ![lab2](/test-framework-api/guest/doc-file/doc-file/e99cb3a6-61fe-4c33-abc6-99c10a3dbf48/lab2.png) | Tìm kiếm Element repository theo tên | 
| ![lab3](/test-framework-api/guest/doc-file/doc-file/c505f371-eb26-4e80-903e-1ed6cd89c722/lab3.png) | Button Search: Tìm kiếm | 
| ![lab4](/test-framework-api/guest/doc-file/doc-file/b7e23f86-0bd7-4b3b-962b-404c123dabbf/lab4.png) | Bỏ lọc tiêu chí tìm kiếm | 
| ELEMENT REPOSITORY NAME | Tên Element Repository | 
| DESCRIPTION | Mô tả của Element Repository  | 
| OWNER | Người tạo Element Repository | 
| STATUS | Trạng thái Element Repository:Active/Deactive. Element Repository chỉ dùng được khi trạng thái là Active| 
| CREATE DATE | Ngày tạo | 
| ![lab5](/test-framework-api/guest/doc-file/doc-file/d78b7423-6a32-429e-8fa3-53e6831befd8/lab5.png) | Tạo mới Element repository | 
| ![lab6](/test-framework-api/guest/doc-file/doc-file/e9a232d7-73eb-4938-ac58-af13faec857b/3cham.png) | Menu chỉnh sửa/ xoá Element Repository | 

### Tạo mới Element Repository

Bước 1: Trên màn hình Element Repository Library, click “+NEW ELEMENT REPOSITORY” để thêm mới

Hệ thống điều hướng đến màn hình CREATE ELEMENT REPOSITORY, cho phép người dùng nhập thông tin của Element Repository muốn thêm mới

Bước 2: Nhập đầy đủ các thông tin của Repository

Bước 3: Click “OK”, hệ thống thông báo tạo mới thành công.

![ele1](/test-framework-api/guest/doc-file/doc-file/39055bd3-1948-44b5-a9d5-3e8038199027/ele1.png)

*Màn hình Create Element Repository*

### Chỉnh sửa Element Repository

Bước 1: Trên màn hình Element Repository Library, Click vào biểu tượng ![3cham](/test-framework-api/guest/doc-file/doc-file/e9a232d7-73eb-4938-ac58-af13faec857b/3cham.png) ở cuối Repository cần chỉnh sửa

Bước 2: Chọn “Edit”, hệ thống hiển thị màn hình Edit Element Repository

Bước 3: Thực hiện chỉnh sửa thông tin Repository

Bước 4: Click OK, hệ thống thông báo Edited successful, quay về màn hình Repository Library, cập nhật thông tin đã chỉnh sửa trên danh sách.

![ele2](/test-framework-api/guest/doc-file/doc-file/69b5889e-1e48-43d2-bae3-b9bbb108fd06/ele2.png)

*Màn hình Edit Element Repository*

### Xoá Element Repository

Bước 1: Trên màn hình Element Repository Library, Click vào biểu tượng ![3cham](/test-framework-api/guest/doc-file/doc-file/e9a232d7-73eb-4938-ac58-af13faec857b/3cham.png) ở cuối Repository muốn xoá

![ele3](/test-framework-api/guest/doc-file/doc-file/d997349b-73c3-45ff-9047-c27838dd94ae/ele3.png)

Bước 2: Chọn “Delete”, hệ thống hiển thị popup xác nhận xoá

![ele4](/test-framework-api/guest/doc-file/doc-file/ac4e4336-19eb-4aea-b1ae-81146bb9ba74/ele4.png)

Bước 3: Xác nhận “DELETE”

Nếu trong Repository có chứa Element, hệ thống hiển thị thông báo như sau, và hành động xoá không thành công

![ele5](/test-framework-api/guest/doc-file/doc-file/95870639-6fc5-4d03-a532-949c02b9766a/ele5.png)

Nếu trong Repository không chứa Element, hệ thống thông báo Delete successful, điều hướng về màn hình Repository Library, danh sách Repository không còn chứa Repository đã xoá.

### Delete Element

Bước 1: Trên màn hình Element Repository Library, Click vào biểu tượng ![3cham](/test-framework-api/guest/doc-file/doc-file/e9a232d7-73eb-4938-ac58-af13faec857b/3cham.png) ở cuối Repository muốn xoá element

![ele6](/test-framework-api/guest/doc-file/doc-file/7fd66b7b-77ea-4379-b3ba-5613d1062fda/ele6.png)

Bước 2: Chọn “Delete all element” để xoá toàn bộ element trong repository đó, hệ thống hiển thị popup xác nhận xoá toàn bộ element trong repository

![ele7](/test-framework-api/guest/doc-file/doc-file/21ff2c45-faf2-468c-ac66-314e8749e048/ele7.png)

Bước 3: Xác nhận “DELETE”, hệ thống hiển thị thông báo Delete successful, trên danh sách Repository vẫn còn repository vừa thao tác, các element thuộc repository đó bị xoá, các element thuộc child repository thì vẫn được giữ nguyên.





