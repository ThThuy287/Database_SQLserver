# Bài tập Thực hành: Quản Lý Bán Hàng

Thư mục này chứa các script T-SQL giải quyết bài tập thực hành hệ quản trị cơ sở dữ liệu (IT004) với chủ đề **Quản Lý Bán Hàng**.

## Sơ đồ Thực thể Liên kết (ERD)

<img width="933" height="552" alt="Ảnh chụp màn hình 2026-10-19 195032" src="https://github.com/user-attachments/assets/93f3504b-8303-451b-bc74-f2c0e81d46a4" />

## Cấu trúc file

Để đảm bảo database hoạt động đúng, vui lòng thực thi các file theo thứ tự từ 1 đến 4:

* **`1_DDL_Schema_QLBH.sql`**: Khởi tạo Database, tạo các bảng (`KHACHHANG`, `NHANVIEN`, `SANPHAM`, `HOADON`, `CTHD`) và thiết lập các ràng buộc (Primary Key, Foreign Key, Check constraints).
* **`2_DML_Data_QLBH.sql`**: Nhập dữ liệu mẫu (Mock data) bằng lệnh `INSERT` và thực hiện các cập nhật `UPDATE` cơ bản.
* **`3_Triggers_QLBH.sql`**: Cài đặt các Triggers để kiểm tra tính toàn vẹn dữ liệu (VD: Ràng buộc ngày lập hóa đơn, tự động tính trị giá hóa đơn và tổng doanh số).
* **`4_Queries_QLBH.sql`**: Chứa hơn 40 câu truy vấn `SELECT` báo cáo thống kê từ cơ bản đến nâng cao (Join, Group By, Subquery, Window Functions).

## Hướng dẫn chạy
1. Mở SQL Server Management Studio (SSMS).
2. Mở và chạy lệnh (Execute) tuần tự từng file SQL theo đúng thứ tự đánh số ở trên.
