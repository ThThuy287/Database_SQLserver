# Bài tập Thực hành: Quản Lý Học Vụ

Thư mục này chứa các script T-SQL giải quyết bài tập thực hành hệ quản trị cơ sở dữ liệu (IT004) với chủ đề **Quản Lý Học Vụ**.

## Sơ đồ Thực thể Liên kết (ERD)

<img width="1090" height="725" alt="Ảnh chụp màn hình 2026-10-19 195418" src="https://github.com/user-attachments/assets/54df1c10-3b83-4bd9-9917-3b14c66ab075" />

## Cấu trúc file

Để đảm bảo database hoạt động đúng, vui lòng thực thi các file theo thứ tự từ 1 đến 4:

* **`1_DDL_Schema_QLHV.sql`**: Khởi tạo Database `QuanLyHocVu`, tạo các bảng (`KHOA`, `MONHOC`, `DIEUKIEN`, `GIAOVIEN`, `LOP`, `HOCVIEN`, `GIANGDAY`, `KETQUATHI`) và thiết lập các ràng buộc (Khóa chính, Khóa ngoại, Check constraints về độ tuổi, điểm số từ 0-10)[cite: 9].
* **`2_DML_Data_QLHV.sql`**: Nạp dữ liệu mẫu (Mock data) bằng lệnh `INSERT` cho danh sách khoa, giáo viên, học viên, môn học, phân công giảng dạy và kết quả thi[cite: 8].
* **`3_Triggers_QLHV.sql`**: Cài đặt các Triggers kiểm tra quy tắc nghiệp vụ phức tạp (VD: Trưởng khoa phải có học vị TS/PTS, điều kiện môn học tiên quyết, chỉ được thi lại khi điểm < 5, cập nhật sĩ số lớp)[cite: 7].
* **`4_Queries_QLHV.sql`**: Chứa 35 câu lệnh `SELECT` phục vụ việc truy vấn, thống kê và trích xuất báo cáo từ cơ bản đến nâng cao (Join, Group By, Subquery, Except, Intersect, Window Functions)[cite: 6].

## Hướng dẫn chạy
1. Mở SQL Server Management Studio (SSMS).
2. Mở và chạy lệnh (Execute) tuần tự từng file SQL theo đúng thứ tự đánh số ở trên.
