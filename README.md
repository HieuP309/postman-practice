# BÁO CÁO THỰC HÀNH POSTMAN

## Thông tin sinh viên

* Họ và tên: Nguyễn Hiếu
* Môn học: Kiểm thử phần mềm
* Nội dung: Tìm hiểu và thực hành công cụ Postman

---

## 1. Mục tiêu

* Làm quen với công cụ Postman.
* Thực hiện gửi Request GET và POST.
* Kiểm tra kết quả phản hồi từ API.
* Tìm hiểu cách lưu và quản lý Collection.

---

## 2. Công cụ sử dụng

* Postman
* GitHub

---

## 3. Nội dung thực hiện

### 3.1 Tạo Collection

Tạo Collection với tên "Postman Practice".

<img width="1932" height="1277" alt="image" src="https://github.com/user-attachments/assets/162d5533-6247-42f5-b30b-782604dacfbc" />


---

### 3.2 Thực hiện GET Users

API:

https://jsonplaceholder.typicode.com/users

Kết quả nhận được danh sách người dùng dưới dạng JSON.

![GET Users](images/get-users.png)

---

### 3.3 Thực hiện GET Posts

API:

https://jsonplaceholder.typicode.com/posts

Kết quả nhận được danh sách bài viết.

![GET Posts](images/get-posts.png)

---

### 3.4 Thực hiện POST User

API:

https://jsonplaceholder.typicode.com/users

Dữ liệu gửi:

{
"name": "Nguyen Hieu",
"email": "[hieu@gmail.com](mailto:hieu@gmail.com)"
}

Kết quả hệ thống phản hồi thành công và trả về dữ liệu vừa gửi.

![POST User](images/post-user.png)

---

## 4. Kết quả đạt được

* Cài đặt thành công Postman.
* Tạo được Collection.
* Thực hiện thành công Request GET.
* Thực hiện thành công Request POST.
* Xuất Collection thành file JSON.
* Đưa sản phẩm lên GitHub.

---

## 5. Kết luận

Qua bài thực hành, em đã tìm hiểu được cách sử dụng Postman để kiểm thử API, gửi request và kiểm tra dữ liệu phản hồi. Đây là công cụ hữu ích trong quá trình học tập và kiểm thử phần mềm.
