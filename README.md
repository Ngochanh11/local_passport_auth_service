3. local_passport_auth_service
   
a. register

Mở terminal và run : node app.js

Mở Postman chọn phương thức POST và nhập url: http://localhost:3000/auth/register

Chọn Body -> raw(json)

Nhập {"username": "admin", "password": "12345"} và chọn Send

Kết quả:
<img width="1511" height="882" alt="image" src="https://github.com/user-attachments/assets/b8dba117-9609-409d-9178-a8c237f7e12f" />

Check in database

<img width="1762" height="875" alt="image" src="https://github.com/user-attachments/assets/6af561f7-c1d1-4867-8dc9-51211b05c6a8" />

b. login

Mở Postman chọn phương thức POST và nhập url: http://localhost:3000/auth/login

Chọn Body -> raw(json)

Nhập {"username": "admin", "password": "12345"} và chọn Send

Kết quả:

<img width="1507" height="929" alt="image" src="https://github.com/user-attachments/assets/6c05a441-30f8-43d5-b63b-81e7787fe2f0" />
