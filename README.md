# BTVN6
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

Ghi chú: Giải thích tại sao lại có SQL như vậy.

# Bài Làm
1. Các bước để import được dữ liệu trong sv_tnut.sql vào sql server

   ![image](https://github.com/user-attachments/assets/9536bc8a-8194-45e4-88ae-1a5ab385c085)

2. Truy vấn dữ liệu đầu vào là tên của sv; sđt; ngày, tháng, năm sinh của sinh viên (của sv đang làm bài tập này)

   ![image](https://github.com/user-attachments/assets/0e5d4812-bac4-4277-ab61-104b4ab7975b)

3. Truy vấn những sv nào trùng hoàn toàn ngày/tháng/năm với em

  ![image](https://github.com/user-attachments/assets/920f2d93-c263-4391-bc9c-607034bdcee5)

4. Truy vấn những sv nào trùng ngày và tháng sinh với em

   ![image](https://github.com/user-attachments/assets/13e227f6-e7d8-44db-9d4c-a42485fc390a)

5. Truy vấn những sv nào trùng tháng và năm sinh với em
   
   ![image](https://github.com/user-attachments/assets/eb7a8544-d2cd-435f-a7ea-d85f3af62295)

6. Truy vấn những sv nào trùng tên với em
   
   ![image](https://github.com/user-attachments/assets/a898741d-25bd-4a81-93ea-29b1e8039f4c)

7. Truy vấn những sv nào trùng họ và tên đệm với em
    
   ![image](https://github.com/user-attachments/assets/a0a9133f-3101-4b63-8328-e35be7777782)

8. Truy vấn những sv nào có sđt sai khác chỉ 1 số so với sđt của em
    
   ![image](https://github.com/user-attachments/assets/c87e0f29-f61c-434a-96d9-414843fb9890)

9. LIỆT KÊ TẤT CẢ CÁC SV NGÀNH KMT, SẮP XẾP THEO TÊN VÀ HỌ ĐỆM, KIỂU TIẾNG  VIỆT, GIẢI THÍCH.
 
    ![image](https://github.com/user-attachments/assets/ad3602ba-69a2-4c3f-8bcd-5eb7018d22d3)

   Giải thích:
   
   ORDER BY ten, hodem: sắp xếp đúng kiểu Việt Nam.

   COLLATE Vietnamese_CI_AS: đảm bảo sắp xếp tiếng Việt có dấu đúng.

10. Truy vấn các sinh viên nữ chuyên ngành KMT có trong bảng SV

    ![image](https://github.com/user-attachments/assets/770ba6d9-1b62-4abf-8b93-b0025b644c97)


    

 
  

