bai tap 4: (sql server)
yêu cầu bài toán:
 - Tạo csdl cho hệ thống TKB (đã nghe giảng, đã xem cách làm)
 - Nguồn dữ liệu: TMS.tnut.edu.vn
 - Tạo các bảng tuỳ ý (3nf)
 - Tạo được query truy vấn ra thông tin gồm 4 cột: họ tên gv, môn dạy, giờ vào lớp, giờ ra.
   trả lời câu hỏi: trong khoảng thời gian từ datetime1 tới datetime2 thì có những gv nào đang bận giảng dạy.

các bước thực hiện:
1. Tạo github repo mới: đặt tên tuỳ ý (có liên quan đến bài tập này)
2. tạo file readme.md, edit online nó:
   paste những ảnh chụp màn hình
   gõ text mô tả cho ảnh đó

deadline: 15/4/2025
--------------------------------------------------------------------------------------------------------------------
LỌC GIẢNG VIÊN TRONG TMS.tnut.edu.vn
![image](https://github.com/user-attachments/assets/035298e1-08dc-4c51-b0a9-4ee56ffd44db)

Tạo bảng 
Bảng GV chọn MaGV làm Key

![image](https://github.com/user-attachments/assets/dc0fba77-cbd0-4eb8-bf43-d50401e9ac2a)


Bảng MonHoc chọn MaMH là key

![image](https://github.com/user-attachments/assets/afa542cb-dab5-475c-903c-c0d4cc97b1fc)

Bảng Lop chọn MaLop làm key 

![image](https://github.com/user-attachments/assets/ab172730-b4ab-4bc3-ada6-6d33a1820fc7)

Bảng MaPhong chọn MaPhong làm key 

![image](https://github.com/user-attachments/assets/b1ca2d5d-a260-40bd-ab7a-d0536db3ef7a)

bảng LichTKB 

![image](https://github.com/user-attachments/assets/17061576-b445-4c3a-89ef-10048a84cbea)


TẠO KHÓA NGOẠI CHO BẢNG TKB






