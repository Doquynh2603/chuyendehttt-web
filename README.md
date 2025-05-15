
## Hướng dẫn và Cài đặt
Yêu cầu: 
* [Node.js](https://nodejs.org/) v19+ để có thể chạy chương trình.
* [Xampp](https://www.apachefriends.org/download.html) để thực hiện thao tác liên quan đến CSDL.

#### Bước 1: Mở Xampp, truy cập vào phpMyAdmin
* Bật Apache và MySQL
* Sau khi MySQL chạy, hãy nhấn chọn Admin của MySQL
![image](https://github.com/namtuthien/SE104.O11.Group6/assets/145759907/1b60556b-657c-482c-8928-163192962c65)

#### Bước 2: Tạo cơ sở dữ liệu mới trong phpMyAdmin
Tạo database mới có tên là
```
ie104_group2
```
![image](https://github.com/NunNunIT/IE104.O12.Group2/assets/145759907/4dcd1d54-f022-4c7f-b6d1-a5544b29c34e)

Bạn có thể tạo database theo cách trong hình hoặc mở tab SQL tại thanh điều hướng và sử dụng lệnh 
```
CREATE DATABASE ie104_group2;
```

#### Bước 3: Nhập dữ liệu cho cơ sở dữ liệu:
- Đầu tiên, truy cập thư mục src/config/database. Tại đây chứa file sql cần thiết
![image](https://github.com/NunNunIT/IE104.O12.Group2/assets/145759907/b5841b38-d7db-4927-bcaf-e87fc78eaffe)
- Tải file: ie104_group2.sql
- Chọn tab Import trên thanh điều hướng
- Chọn Choose File --> Chọn file mới tải về ở trên
![image](https://github.com/NunNunIT/IE104.O12.Group2/assets/145759907/eadc23ee-fe49-418d-a57e-09d4ee48c48f)
    + Sau đó, vuốt xuống dưới để nhấn nút 'Import'

Sau khi thực hiện cách trên bạn sẽ có đầy đủ cơ sở dữ liệu của trang web. Kết quả như trong hình:
![image](https://github.com/NunNunIT/IE104.O12.Group2/assets/145759907/0afa3cdd-46ec-4eda-abdc-bac2ca1729fd)

#### Bước 4: Thực hiện clone repository này với lệnh
```
https://github.com/NunNunIT/IE104.O12.Group2.git
```
#### Bước 5: Mở dự án mới clone về và thực hiện các câu lệnh sau
```
npm install
```
```
npm start
```
Nếu ở màn hình terminal cho ra kết quả sau đây, tức các bạn đã thành công
![image](https://github.com/namtuthien/SE104.O11.Group6/assets/145759907/3b6feed5-2199-479d-8b54-9531ce608204)

#### Bước 6: Mở website. Có 2 cách:
* Cách 1: Ctrl + Click vào đường link http://127.0.0.1:3000 trên terminal
* Cách 2: Mở trình duyệt bất kỳ và nhập đường dẫn sau ``` http://127.0.0.1:3000 ```

#### Đến đây các bạn đã có thể vào trang web của nhóm. 
* Bạn có thể đăng ký tài khoản khách hàng mới để thực hiện các thao tác trong trang web hoặc đăng nhập bằng tài khoản sau:
  + Email: ```0916552603```
  + Mật khẩu: ```12345678```

