## Quản lý Child Repository/ Element

Sau khi thêm mới một Element Repository, tiến hành thêm Child Repository của Element Repository đó hoặc trực tiếp thêm mới Element, tuỳ thuộc vào kho trữ mà bạn muốn xây dựng.

### Xem chi tiết 

Click vào Repository người dùng muốn thao tác, hệ thống hiển thị màn hình Element Repository Library cùng với các element được tạo trong thư viện.  

![qle1](/test-framework-api/guest/doc-file/doc-file/4ed73fd9-0908-4ad6-8def-31947c8c1161/cele1.png)


| Label | Chức năng |
| ------ | ------ |
| ![clab1](/test-framework-api/guest/doc-file/doc-file/4a51c4a2-849b-4f26-a517-c8e7c4dd1355/clab1.png) | Đường dẫn từ thư viện Element Repository đến các Repository, Child Repository, là màn hình người dùng đang thao tác |
| ELEMENT REPOSITORY NAME | Tên thư mục con của Repository | 
| DESCRIPTION| Mô tả của thư mục con | 
| OWNER | Người tạo thư mục con | 
| STATUS | Trạng thái Element Repository:Active Deactive Element Repository chỉ dùng được khi trạng thái là Active| 
| CREATE DATE | Ngày tạo thư mục con | 
| ![3cham](/test-framework-api/guest/doc-file/doc-file/e9a232d7-73eb-4938-ac58-af13faec857b/3cham.png) | Menu chỉnh sửa/ xoá Element Repository | 
| ![clab2](/test-framework-api/guest/doc-file/doc-file/6ed5e955-0fca-424f-841a-b85ffcfd6ea8/clab2.png) | Định dạng của Element (button, menu, input…) Màn hình sẽ hiển thị toàn bộ Element được tạo trong repository với lựa chọn là All Template Người dùng có thể lựa chọn 1 template bất kì tuỳ vào mục đích sử dụng | 
| ![clab3](/test-framework-api/guest/doc-file/doc-file/daf08aab-9aee-4537-885c-559d36c3b85f/clab3.png) | Tên Element: Nên đặt tên theo chức năng hoặc tên của Element trên giao diện hệ thống/ ứng dụng được test | 
| ![clab4](/test-framework-api/guest/doc-file/doc-file/e239737d-d551-49e3-b67d-b47da149a80b/clab4.png) | Tạo mới Child Element Repository | 
| ![clab5](/test-framework-api/guest/doc-file/doc-file/9399cc8c-3276-4224-8be7-aaed9ddbfb48/clab5.png) | Tạo mới Element | 

### Tạo mới Child Repository

Trên màn hình Repository, Click “+CREATE ELEMENT REPOSITORY”, thực hiện tương tự tạo mới Element Repository

### Tạo mới Element

Bước 1: Click “+NEW ELEMENT”

![qle2](/test-framework-api/guest/doc-file/doc-file/69f049c4-ae33-4488-94f5-01ef1c75437a/qle2.png)

*Hệ thống hiển thị màn hình Create Element*

![qle3](/test-framework-api/guest/doc-file/doc-file/811e1044-6f5e-4f2b-9cb4-2c25e6694ef9/qle3.png)

Bước 2:  Nhập thông tin cần thiết của Element

-	Element Template: Các template của Element đã được tạo ở Project Type
-	Name: Tên Element – nên đặt theo chức năng/ tên của element hiển thị trên giao diện hệ thống/ ứng dụng được test
-	Xpath: Địa chỉ của Element trên giao diện của hệ thống/ ứng dụng được test
-	Id: Id của element (nếu có)
-	Name: Tên của element – cấu phần của element do developer đặt (nếu có)

Các template có sẵn có thể áp dụng cho Element trong Repository

![qle4](/test-framework-api/guest/doc-file/doc-file/387de894-9cf8-4bab-b15a-69bfc9fcbc2d/qle4.png)

![qle5](/test-framework-api/guest/doc-file/doc-file/cca3c3c3-fd11-403d-9fe3-08b86c10cb32/qle5.png)

Có thể tìm Xpath của phần tử dựa trên vị trí xung quanh một phần tử khác đã xác định trên hệ thống: 
-	Below of: Bên dưới
-	Middle of: Ở giữa
-	Above of: Ở trên
-	Right of: Bên phải
-	Center of: Trung tâm
-	Left of: Bên trái

![qle6](/test-framework-api/guest/doc-file/doc-file/cfa2c9b0-6b46-453a-a681-78507c3c5696/qle6.png)

-	Description: Mô tả của Element
-	Status: Trạng thái của Element Active/ Deactive

Click ![qle7](/test-framework-api/guest/doc-file/doc-file/c787c1f3-bf3e-4235-9544-68ee70e5fc50/qle7.png)  để thay đổi Repository của Element

Bước 3: Click “OK”, hệ thống thông báo Create successful và quay lại màn hình thư viện Element Repository, đã bổ sung thêm Element vừa tạo. 

![qle8](/test-framework-api/guest/doc-file/doc-file/8f78d927-7c2f-47cd-a249-6842a1a5cfdc/qle8.png)

*Màn hình Thư viện Element Repository “Login” với Child Repository “Thêm mới” và các Element*

### Chỉnh sửa Element

Bước 1: Tại màn hình Thư viện Element Repository, Click vào “![3cham](/test-framework-api/guest/doc-file/doc-file/e9a232d7-73eb-4938-ac58-af13faec857b/3cham.png)” ở Element muốn chỉnh sửa, chọn “Edit”, hệ thống hiển thị màn hình Edit Element

![qle9](/test-framework-api/guest/doc-file/doc-file/52d7d98f-f207-42b3-b752-02dc14b2b3e3/qle9.png)

Bước 2: Nhập thông tin cần chỉnh sửa

![qle10](/test-framework-api/guest/doc-file/doc-file/539b72a5-79d6-454d-b12c-727a1a3929d4/qle10.png)

Bước 3: Click “OK” để cập nhật thông tin vừa chỉnh sửa

Hệ thống thông báo Edit successful, điều hướng quay lại màn hình Repository đang thao tác.

### Xóa Element

Bước 1: Tại màn hình Thư viện Element Repository, Click vào “![3cham](/test-framework-api/guest/doc-file/doc-file/e9a232d7-73eb-4938-ac58-af13faec857b/3cham.png) ” ở Element muốn xoá, chọn “Delete”

![qle11](/test-framework-api/guest/doc-file/doc-file/aa6a0556-2d7c-4761-b499-2c03a4001da6/qle11.png)

Bước 2: Chọn “Delete” để xoá Element, hệ thống hiển thị popup xác nhận xoá

![qle12](/test-framework-api/guest/doc-file/doc-file/a7e368c7-1108-490c-9dd9-477bfc7d7e52/qle12.png)

Bước 3: Xác nhận thao tác:

- Click “DELETE” để xác nhận xoá, hệ thống thông báo Delete successful, danh sách Element được cập nhật đã loại bỏ Element vừa thao tác xoá.
  
- Hành động xoá không thể hoàn tác, nếu chưa xác định có nên xoá Element này hay không, người dùng nhấn ‘CANCEL” để huỷ.

### Tạo bản sao Element

Bước 1: Tại màn hình Thư viện Element Repository, Click vào “![3cham](/test-framework-api/guest/doc-file/doc-file/e9a232d7-73eb-4938-ac58-af13faec857b/3cham.png)” ở Element muốn tạo bản sao, chọn “Duplicate"

![qle13](/test-framework-api/guest/doc-file/doc-file/538fc2ff-3084-4095-bd80-882cbeaf8f4f/qle13.png)

Bước 2: Nhập thông tin tương tự chỉnh sửa Element

![qle14](/test-framework-api/guest/doc-file/doc-file/54f04aa0-b2b6-40d7-a39c-23207d16f463/qle14.png)

Bước 3: Click “OK”, hệ thống thông báo Duplicated successful.



