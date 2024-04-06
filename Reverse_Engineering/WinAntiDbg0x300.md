Trước hết tôi vẫn sẽ dùng tool `Exeinfo Pe` để check xem các thông tin cơ bản của file. File này đã được nén lại (UPX). Tác dụng của UPX thì như tôi đã để cập trước đó là dùng để ẩn đi chương trình gốc

![image](https://github.com/daglongg/PicoCTF_2024/assets/138242812/481971cd-8420-4a17-b671-e006d47d1646)

 Đây là chương trình lúc chưa được UPX, 1 chương trình mà chỉ có 1 funtion duy nhất, đây cũng là dấu hiệu cho thấy chương trình đã được nén, hay được can thiệp

 ![image](https://github.com/daglongg/PicoCTF_2024/assets/138242812/84dc3a2c-0b0f-4a15-a986-e6e9acd00ca2)

 Tôi sẽ dùng câu lệnh `upx -d WinAntiDbg0x300.exe`
