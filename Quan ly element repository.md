# Quản lý Element Repository

### Màn hình danh sách element repository

![dn1](https://user-images.githubusercontent.com/105435351/196078501-e739e1e9-557b-4418-8a02-ad648b0e5ad8.png)

*Màn hình Element Repository Library*


| Label | Chức năng |
| ------ | ------ |
| ![Filter form](https://user-images.githubusercontent.com/105435351/196140896-9439dcdd-91bb-4877-a857-30caba8dc6c1.png) | Dùng để hiển thị/ ẩn công cụ lọc, tìm kiếm element repository |
| ![Search name](https://user-images.githubusercontent.com/105435351/196141212-a3d02511-e00e-46c0-920f-06fd7864e45e.png) | Tìm kiếm Element repository theo tên | 
| ![Search](https://user-images.githubusercontent.com/105435351/196141591-bd60de92-fe9f-4a3a-9bed-f2b15b593b31.png) | Button Search: Tìm kiếm | 
| ![Reset](https://user-images.githubusercontent.com/105435351/196141921-e3900573-4e06-4aa2-865e-d208858485ab.png) | Bỏ lọc tiêu chí tìm kiếm | 
| ELEMENT REPOSITORY NAME | Tên Element Repository | 
| DESCRIPTION | Mô tả của Element Repository  | 
| OWNER | Người tạo Element Repository | 
| STATUS | Trạng thái Element Repository:Active Deactive Element Repository chỉ dùng được khi trạng thái là Active| 
| CREATE DATE | Ngày tạo | 
| ![New Element Repository](https://user-images.githubusercontent.com/105435351/196141921-e3900573-4e06-4aa2-865e-d208858485ab.png) | Tạo mới Element repository | 
| ![Menu chinh sua/soa](https://user-images.githubusercontent.com/105435351/196141921-e3900573-4e06-4aa2-865e-d208858485ab.png) | Menu chỉnh sửa/ xoá Element Repository | 

### Tạo mới Element Repository

Bước 1: Trên màn hình Element Repository Library, click “+NEW ELEMENT REPOSITORY” để thêm mới

Hệ thống điều hướng đến màn hình CREATE ELEMENT REPOSITORY, cho phép người dùng nhập thông tin của Element Repository muốn thêm mới

Bước 2: Nhập đầy đủ các thông tin của Repository

Bước 3: Click “OK”, hệ thống thông báo tạo mới thành công.

![dn1](https://user-images.githubusercontent.com/105435351/196078501-e739e1e9-557b-4418-8a02-ad648b0e5ad8.png)

### Chỉnh sửa Element Repository

Bước 1: Trên màn hình Element Repository Library, Click vào biểu tượng ![3cham](https://user-images.githubusercontent.com/105435351/197490871-756491bf-bdbc-460f-9a51-9b27ed4240c7.png) ở cuối Repository cần chỉnh sửa

Bước 2: Chọn “Edit”, hệ thống hiển thị màn hình Edit Element Repository

Bước 3: Thực hiện chỉnh sửa thông tin Repository

Bước 4: Click OK, hệ thống thông báo Edited successful, quay về màn hình Repository Library, cập nhật thông tin đã chỉnh sửa trên danh sách.

<img src="https://user-images.githubusercontent.com/105435351/198542962-561f6562-2d76-4583-9b93-376b476493b8.png" width="35%" />

*Màn hình Edit Element Repository*

### Xoá Element Repository

Bước 1: Trên màn hình Element Repository Library, Click vào biểu tượng ![3cham](https://user-images.githubusercontent.com/105435351/197490871-756491bf-bdbc-460f-9a51-9b27ed4240c7.png) ở cuối Repository muốn xoá

<img src="https://user-images.githubusercontent.com/105435351/198542962-561f6562-2d76-4583-9b93-376b476493b8.png" width="35%" />

Bước 2: Chọn “Delete”, hệ thống hiển thị popup xác nhận xoá

<img src="https://user-images.githubusercontent.com/105435351/198542962-561f6562-2d76-4583-9b93-376b476493b8.png" width="35%" />

Bước 3: Xác nhận “DELETE”

-	Nếu trong Repository có chứa Element, hệ thống hiển thị thông báo như sau, và hành động xoá không thành công

<img src="https://user-images.githubusercontent.com/105435351/198542962-561f6562-2d76-4583-9b93-376b476493b8.png" width="35%" />

-	Nếu trong Repository không chứa Element, hệ thống thông báo Delete successful, điều hướng về màn hình Repository Library, danh sách Repository không còn chứa Repository đã xoá.

### Delete Element

Bước 1: Trên màn hình Element Repository Library, Click vào biểu tượng ![3cham](https://user-images.githubusercontent.com/105435351/197490871-756491bf-bdbc-460f-9a51-9b27ed4240c7.png) ở cuối Repository muốn xoá element

<img src="https://user-images.githubusercontent.com/105435351/198542962-561f6562-2d76-4583-9b93-376b476493b8.png" width="35%" />

Bước 2: Chọn “Delete all element” để xoá toàn bộ element trong repository đó, hệ thống hiển thị popup xác nhận xoá toàn bộ element trong repository

<img src="https://user-images.githubusercontent.com/105435351/198542962-561f6562-2d76-4583-9b93-376b476493b8.png" width="35%" />

Bước 3: Xác nhận “DELETE”, hệ thống hiển thị thông báo Delete successful, trên danh sách Repository vẫn còn repository vừa thao tác, các element thuộc repository đó bị xoá, các element thuộc child repository thì vẫn được giữ nguyên.











