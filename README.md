## 1. Giới thiệu về biểu diễn hệ nhị phân 
  # Giới Thiệu
- Là một hệ đếm dùng hai ký tự để biểu đạt một giá trị số bằng tổng số các lũy thừa của 2.
- Biểu diễn bằng 0 và 1.
- Được sắp xếp từ trái sang phải
  # Ứng Dụng
- Tính toán số học
- Lưu trữ dữ liệu (Binary File)
- Xử lý logic (AND, OR và NOT)
- Thực Thi Lệnh và Chương Trình
  # Mối Tương Quan Với Các Hệ Cơ Số 
- Base2 -> Base10 

![image](https://github.com/TooBunReal/training-w1/assets/89735990/3ad9805c-4b78-4d53-9f11-be34ef330fef)


- Base10 -> Base2 

![image](https://github.com/TooBunReal/training-w1/assets/89735990/9c5ecd4c-0142-4090-a7b9-c9f8230b88f8)

- Base2 <-> Base16

![image](https://github.com/TooBunReal/training-w1/assets/89735990/8f5ce20d-c419-46d1-95d9-194f18e1c320)


  # Biểu Diễn Số
- Bit cao nhất (bit trái nhất) được sử dụng để biểu diễn dấu của số (0 là dương, 1 là âm)
- Unsigned
  + ``0000 1101`` = ``13``
- Signed  
  + Phương Pháp Bù 2 ( Đảo Bit, Cộng 1 )
  + ```0000 1101``` -> ```1111 0010``` -> ```1111 0011``` -> ```-13```
## 2.Sự biểu diễn của Hexadecimal và Bytes
  # Sự Tương Quan
- Đơn vị lưu trữ cơ bản của máy tính là Bytes ( 1 byte = 8 bits )
- Một số hexadecimal được biểu diễn bởi 4 bits ( nữa bytes )
-> ta có thể biểu diễn 1 byte bằng 2 số hexacimal

![image](https://github.com/TooBunReal/training-w1/assets/89735990/7df5b8b2-d1fe-4d71-83c0-26d20ac145eb)


  # Cách Máy Tính Lưu Trữ Và Biểu Diễn Dữ Liệu Trong Bộ Nhớ
- Theo như kiến trúc máy tính thông thường, máy tính lưu trữ dữ liệu theo các ô nhớ có địa chỉ duy nhất.
- Các ô nhớ được sắp xếp một cách cố định theo thứ tự liên tiếp với địa chỉ là một con số thường ở dạng base10 hoặc base16.q
- Máy tính lưu trữ và biểu diễn dữ liệu trong bộ nhớ theo các đơn vị lưu trữ như byte, word, double word, hay quad word.

![image](https://github.com/TooBunReal/training-w1/assets/89735990/d47433fe-0223-48c2-832f-4b1c32c88bf9)


- Word là một đơn vị lưu trữ phổ biến được dùng trong kiến trúc máy tính.
- Độ dài của một word có thể khác nhau đối với các kiến trúc máy tính khác nhau (ví dụ: 16 bit, 32 bit, 64 bit).
- Dưới đây sẽ là minh họa về cách một bộ nhớ file 8 byte


| Address | Value |
| :---:   | :---: |
| 0x00    | AA   | 
| 0x01    | 30   | 
| 0x02    | 24   | 
| 0x03    | 3C   | 
| 0x04    | 5B   | 
| 0x05    | 9H   | 
| 0x06    | 12   | 
| 0x07    | 7E   | 



