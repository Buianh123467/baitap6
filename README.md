Bài tập 6: Hệ quản trị CSDL
Chủ đề: Câu lệnh Select
Yêu cầu bài tập: 
Cho file sv_tnut.sql (1.6MB)
1. Hãy nêu các bước để import được dữ liệu trong sv_tnut.sql vào sql server của em
2. dữ liệu đầu vào là tên của sv; sđt; ngày, tháng, năm sinh của sinh viên (của sv đang làm bài tập này)
3. nhập sql để tìm xem có những sv nào trùng hoàn toàn ngày/tháng/năm với em?
4. nhập sql để tìm xem có những sv nào trùng ngày và tháng sinh với em?
5. nhập sql để tìm xem có những sv nào trùng tháng và năm sinh với em?
6. nhập sql để tìm xem có những sv nào trùng tên với em?
7. nhập sql để tìm xem có những sv nào trùng họ và tên đệm với em.
8. nhập sql để tìm xem có những sv nào có sđt sai khác chỉ 1 số so với sđt của em.
9. BẢNG SV CÓ HƠN 9000 ROWS, HÃY LIỆT KÊ TẤT CẢ CÁC SV NGÀNH KMT, SẮP XẾP THEO TÊN VÀ HỌ ĐỆM, KIỂU TIẾNG  VIỆT, GIẢI THÍCH.
10. HÃY NHẬP SQL ĐỂ LIỆT KÊ CÁC SV NỮ NGÀNH KMT CÓ TRONG BẢNG SV (TRÌNH BÀY QUÁ TRÌNH SUY NGHĨ VÀ GIẢI NHỮNG VỨNG MẮC)

DEADLINE: 23H59:59 NGÀY 25/4/2025
 Hãy nêu các bước để import được dữ liệu trong sv_tnut.sql vào sql server của em
Vào phần File > Open > Files > chọn file sv_tnut.sql đã tải trước đó
![Image](https://github.com/user-attachments/assets/79f13c82-2b61-4d0c-89c6-89d17c473c05)
 dữ liệu đầu vào là tên của sv; sđt; ngày, tháng, năm sinh của sinh viên
  ![Image](https://github.com/user-attachments/assets/e89cf0d8-0bd6-4151-8095-3df9c5ab7288)

nhập sql để tìm xem có những sv nào trùng hoàn toàn ngày/tháng/năm
![Image](https://github.com/user-attachments/assets/76ab3353-0ed8-4cf0-a7c2-68431577bdba)

 nhập sql để tìm xem có những sv nào trùng ngày và tháng sinh 
![Image](https://github.com/user-attachments/assets/f0677c13-37b0-42aa-9dfa-3621198264ca)

 nhập sql để tìm xem có những sv nào trùng tháng và năm sinh
![Image](https://github.com/user-attachments/assets/94bc0371-bb6b-4ec1-beea-1832e5de40ff)
nhập sql để tìm xem có những sv nào trùng tên 
![Image](https://github.com/user-attachments/assets/400433b4-ec3f-40bb-9615-dd551ea25405)
nhập sql để tìm xem có những sv nào trùng họ và tên đệm 
![Image](https://github.com/user-attachments/assets/adf2fe30-7122-4589-bb0c-d646a82e76c8)

nhập sql để tìm xem có những sv nào có sđt sai khác chỉ 1 số so với sđt của em.
![Image](https://github.com/user-attachments/assets/2718bdcd-b11e-47e5-bed6-83d2e9d2df24)

BẢNG SV CÓ HƠN 9000 ROWS, HÃY LIỆT KÊ TẤT CẢ CÁC SV NGÀNH KMT, SẮP XẾP THEO TÊN VÀ HỌ ĐỆM, KIỂU TIẾNG  VIỆT, GIẢI THÍCH.
   
WHERE lop LIKE '%KTP%': để lọc sinh viên có lớp chứa chuỗi "KTP".

ORDER BY ten COLLATE Vietnamese_CI_AS, hodem COLLATE Vietnamese_CI_AS:
Để sắp xếp theo tên, sau đó theo họ đệm, đúng thứ tự chữ cái 

![Image](https://github.com/user-attachments/assets/e2e04da5-caed-4068-abae-15b2fb3e7c7f)

1HÃY NHẬP SQL ĐỂ LIỆT KÊ CÁC SV NỮ NGÀNH KMT CÓ TRONG BẢNG SV

Do database không có cột giới tính em sử dụng hodem 'Thi' để thay thế tạm cho giới tính nữ
![Image](https://github.com/user-attachments/assets/2783d36d-8f6c-4fed-a358-4ea2028ba8f7)




