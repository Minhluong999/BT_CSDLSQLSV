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

![image](https://github.com/user-attachments/assets/825442f6-445a-443c-b4e4-aef52cfdac57)


Bảng LopHP chọn MaLop làm key 

![image](https://github.com/user-attachments/assets/288001ba-27e3-454f-bfe9-754a4bcfce87)


Bảng MaPhong chọn MaPhong làm key 

![image](https://github.com/user-attachments/assets/b3d2aed2-7b8b-440b-9b04-7788e481e45f)


bảng LichTKB 

![image](https://github.com/user-attachments/assets/17061576-b445-4c3a-89ef-10048a84cbea)


TẠO KHÓA NGOẠI CHO BẢNG TKB

![image](https://github.com/user-attachments/assets/5874c166-a745-4169-8b06-b05f6b19d562)


THÔNG TIN GIANG VIEN

![image](https://github.com/user-attachments/assets/5f54211b-f5c1-46eb-b008-834aec6ba467)


BẢNG LopHP


![image](https://github.com/user-attachments/assets/319e9f6a-b254-46c2-b3be-16129ce8cbea)


BẢNG MONHOC

![image](https://github.com/user-attachments/assets/e642526e-c826-48d9-84cb-47286e9f9ce5)


Bảng lichTKB


![image](https://github.com/user-attachments/assets/7647d805-3693-4df2-953d-4e751ac1fcbc)


Trong khoảng thời gian từ datetime1 tới datetime2 thì có những gv nào đang bận giảng dạy.




