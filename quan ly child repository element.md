# Quản lý Child Repository/ Element

Sau khi thêm mới một Element Repository, tiến hành thêm Child Repository của Element Repository đó hoặc trực tiếp thêm mới Element, tuỳ thuộc vào kho trữ mà bạn muốn xây dựng.

### Xem chi tiết 

Click vào Repository người dùng muốn thao tác, hệ thống hiển thị màn hình Element Repository Library cùng với các element được tạo trong thư viện.  

![newrole1](https://user-images.githubusercontent.com/105435351/198692362-2950cb9c-d572-466f-a2fd-e08e88cd88bf.png)


| Label | Chức năng |
| ------ | ------ |
| ![Login](https://user-images.githubusercontent.com/105435351/196140896-9439dcdd-91bb-4877-a857-30caba8dc6c1.png) | Đường dẫn từ thư viện Element Repository đến các Repository, Child Repository, là màn hình người dùng đang thao tác |
| ELEMENT REPOSITORY NAME | Tên thư mục con của Repository | 
| DESCRIPTION| Mô tả của thư mục con | 
| OWNER | Người tạo thư mục con | 
| STATUS | Trạng thái Element Repository:Active Deactive Element Repository chỉ dùng được khi trạng thái là Active| 
| CREATE DATE | Ngày tạo thư mục con | 
| ![Menu chinh sua/soa](https://user-images.githubusercontent.com/105435351/196141921-e3900573-4e06-4aa2-865e-d208858485ab.png) | Menu chỉnh sửa/ xoá Element Repository | 
| ![Select a element template](https://user-images.githubusercontent.com/105435351/196141921-e3900573-4e06-4aa2-865e-d208858485ab.png) | Định dạng của Element (button, menu, input…) Màn hình sẽ hiển thị toàn bộ Element được tạo trong repository với lựa chọn là All Template Người dùng có thể lựa chọn 1 template bất kì tuỳ vào mục đích sử dụng | 
| ![Ten element](https://user-images.githubusercontent.com/105435351/196141921-e3900573-4e06-4aa2-865e-d208858485ab.png) | Tên Element: Nên đặt tên theo chức năng hoặc tên của Element trên giao diện hệ thống/ ứng dụng được test | 
| ![New element repository](https://user-images.githubusercontent.com/105435351/196141921-e3900573-4e06-4aa2-865e-d208858485ab.png) | Tạo mới Child Element Repository | 
| ![New element](https://user-images.githubusercontent.com/105435351/196141921-e3900573-4e06-4aa2-865e-d208858485ab.png) | Tạo mới Element | 

### Tạo mới Child Repository

Trên màn hình Repository, Click “+CREATE ELEMENT REPOSITORY”, thực hiện tương tự tạo mới Element Repository

### Tạo mới Element

Bước 1: Click “+NEW ELEMENT”

![newrole1](https://user-images.githubusercontent.com/105435351/198692362-2950cb9c-d572-466f-a2fd-e08e88cd88bf.png)

*Hệ thống hiển thị màn hình Create Element*

![newrole1](https://user-images.githubusercontent.com/105435351/198692362-2950cb9c-d572-466f-a2fd-e08e88cd88bf.png)

Bước 2:  Nhập thông tin cần thiết của Element

-	Element Template: Các template của Element đã được tạo ở Project Type
-	Name: Tên Element – nên đặt theo chức năng/ tên của element hiển thị trên giao diện hệ thống/ ứng dụng được test
-	Xpath: Địa chỉ của Element trên giao diện của hệ thống/ ứng dụng được test
-	Id: Id của element (nếu có)
-	Name: Tên của element – cấu phần của element do developer đặt (nếu có)

Các template có sẵn có thể áp dụng cho Element trong Repository

![newrole1](https://user-images.githubusercontent.com/105435351/198692362-2950cb9c-d572-466f-a2fd-e08e88cd88bf.png)

![newrole1](https://user-images.githubusercontent.com/105435351/198692362-2950cb9c-d572-466f-a2fd-e08e88cd88bf.png)

Có thể tìm Xpath của phần tử dựa trên vị trí xung quanh một phần tử khác đã xác định trên hệ thống: 
-	Below of: Bên dưới
-	Middle of: Ở giữa
-	Above of: Ở trên
-	Right of: Bên phải
-	Center of: Trung tâm
-	Left of: Bên trái

![newrole1](https://user-images.githubusercontent.com/105435351/198692362-2950cb9c-d572-466f-a2fd-e08e88cd88bf.png)

-	Description: Mô tả của Element
-	Status: Trạng thái của Element Active/ Deactive

Click “ ”  để thay đổi Repository của Element





























