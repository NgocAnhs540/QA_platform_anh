# Projects
Quản lý toàn bộ dự án trên hệ thống (với người dùng là admin) hoặc một số dự án người dùng được tham gia.

Người dùng có vai trò là admin có thể tạo project mới, chỉnh sửa thông tin hoặc xoá project.

Người dùng có thể tạo ra danh sách các tham số dùng chung cho project, giá trị của các tham số được cài đặt ở các version của dự án (version_variable).

### Tạo mới một project

Bước 1:	Click nút **+New Project** để tạo một project mới

![createproject1](/test-framework-api/guest/doc-file/doc-file/e9bd4fed-b58c-4992-811e-d5cb48093146/createproject1.png)

Bước 2:	Trên màn hình “CREATE PROJECT” nhập các thông tin cần thiết của project, trong đó:

-	Project type: Loại Project
-	Code: Code của Project
-	Name: Tên Project
-	Description: Mô tả của Project
-	Auto Create Profile: Tạo profile tự động
-	Bug Tracker Type: Loại hình theo dõi lỗi
-	Jira base URL
-	Jira Username
-	Jira Token
-	Status: Lựa chọn Active/ Deactive
-	Start date: Ngày bắt đầu dự án
-	End date: Ngày kết thúc dự án

Bước 3:	Click nút “OK” hệ thống thông báo tạo mới thành công.

### Tạo mới Parameter
Mỗi một project sẽ có những parameter được sử dụng ở nhiều test case, thay vì việc mỗi lần cấu hình test case đều phải tạo lại parameter và nhập dữ liệu cho parameter khi chạy thì chúng ta sẽ tạo ra một bộ parameter dùng chung cho toàn bộ project. Khi người dùng sử dụng parameter chung thì sẽ không cần tạo lại các parameter project khi cấu hình hay nhập dữ liệu khi run. 

![create para](/test-framework-api/guest/doc-file/doc-file/867caa75-b7eb-4843-b00a-04ae80d72dfd/create para.png)

Bước 1:	Trên màn hình Projects, click chuột vào biểu tượng ![3cham](https://user-images.githubusercontent.com/105435351/197490871-756491bf-bdbc-460f-9a51-9b27ed4240c7.png) tương ứng với project muốn tạo mới parameter

Bước 2:	Click chọn “Set parameter”

![create para2](/test-framework-api/guest/doc-file/doc-file/53ea6862-18d9-4ee7-b655-d77f72b258cb/create para2.png)

Bước 3:	Trên màn hình Parameters Project, click “+ New parameter” và nhập loại variable, kiểu dữ liệu và tên của parameter

Bước 4:	Click “SAVE”

### Project
Từ màn hình hệ thống, click vào Project cần tác nghiệp

![editproject2](/test-framework-api/guest/doc-file/doc-file/ab2b382a-ef6b-49ca-85d6-7da9e2541f28/proj.png)

*Giao diện sau khi click vào Project*

| Label | Tên và chức năng |
| ------ | ------ | 
| ![1](/test-framework-api/guest/doc-file/doc-file/d0f98eac-95e8-4059-a783-1bb48721ad4b/1png.png) | List Project chuyển đổi giữa các Project mà người dùng tham gia trên hệ thống | 
| ![2](/test-framework-api/guest/doc-file/doc-file/519bfc37-fa5f-44eb-9f2e-12c9d79cde97/2.png) | Icon account: Đến màn hình cài đặt hệ thống/ thay đổi thông tin người dùng  | 
| ![3](/test-framework-api/guest/doc-file/doc-file/d8967b90-1b99-4ad2-9a9a-ef73e404324b/3.png) | Insights: Báo cáo kết quả Run test case, tỉ lệ Pass/ Faill số test case đã cấu hình trong hệ thống  |
| ![4](/test-framework-api/guest/doc-file/doc-file/1b11288a-2a4b-4f18-a670-e91e29e9dba8/4.png) | Element Repository: Kho lưu trữ Element  | 
| ![5](/test-framework-api/guest/doc-file/doc-file/a05a13b1-93d3-4fdf-9f69-2821b5e85376/5.png) | Test Lib: Thư viện các test case đã dựng trong dự án thực hiện cấu hình test case ở thư mục này  | 
| ![6](/test-framework-api/guest/doc-file/doc-file/a659aef4-a1d4-44f1-a451-2be2df4c79f5/6.png) | Runs: Lịch sử các test case đã chạy thông tin các lần chạy bao gồm môi trường, hệ điều hành, người chạy, thời gian, lịch chạy test case |
| ![7](/test-framework-api/guest/doc-file/doc-file/5800bc62-175c-460a-886d-dabce9ce8976/7.png) | Delete Data: Xoá dữ liệu các test case đã chạy  | 
| ![8](/test-framework-api/guest/doc-file/doc-file/395c8b1a-89f7-4b14-9872-247712027913/8.png) | File: Quản lý file dữ liệu thư mục chứa file dữ liệu cho các test case sử dụng element có data type là file | 
| ![9](/test-framework-api/guest/doc-file/doc-file/69385882-d609-442a-b375-3689bcf83428/9.png) | Setting: Cài đặt project cài đặt các thông tin cho project | 

***Project setting***

Để quay lại màn hình thiết lập hệ thống, click vào Icon Account, chọn “Project Setting”

![editproject2](/test-framework-api/guest/doc-file/doc-file/e5ff2a9b-57f4-4138-9b2e-810254dd1f20/2.3.1.png)

***View/ Chỉnh sửa tài khoản người dùng***

Bước 1: Click vào Icon Account, chọn "VIEW PROFILE"

![editproject2](/test-framework-api/guest/doc-file/doc-file/3e04a063-6f8f-404a-919c-7f09f5401d3b/2.3.2.png)

Trên Tab Profile, xem/ chỉnh sửa tên người dùng

Trên Tab Account, chỉnh sửa Password người dùng

![editproject2](/test-framework-api/guest/doc-file/doc-file/3992971b-bc5a-45d9-bed4-3e29af256cac/2.3.3.png)

