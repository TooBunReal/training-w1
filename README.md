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

![image](https://github.com/TooBunReal/training-w1/assets/89735990/a3c0e92c-16f1-4b6a-af69-d23b4c0fa48d)

- Base10 -> Base2 

![image](https://github.com/TooBunReal/training-w1/assets/89735990/5a974db0-8945-453f-8bc5-e06bdf53333c)

- Base2 <-> Base16

![image](https://github.com/TooBunReal/training-w1/assets/89735990/35e2c67a-6d8b-4249-889d-a64ec03996a7)

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

![image](https://github.com/TooBunReal/training-w1/assets/89735990/35c02387-c98a-4c6a-871a-f5ff2f364c91)

  # Cách Máy Tính Lưu Trữ Và Biểu Diễn Dữ Liệu Trong Bộ Nhớ
- Theo như kiến trúc máy tính thông thường, máy tính lưu trữ dữ liệu theo các ô nhớ có địa chỉ duy nhất.
- Các ô nhớ được sắp xếp một cách cố định theo thứ tự liên tiếp với địa chỉ là một con số thường ở dạng base10 hoặc base16.q
- Máy tính lưu trữ và biểu diễn dữ liệu trong bộ nhớ theo các đơn vị lưu trữ như byte, word, double word, hay quad word.

![image](https://github.com/TooBunReal/training-w1/assets/89735990/e4924f32-985f-4ec5-879f-bf0e8bc8533b)

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



