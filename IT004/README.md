# IT004 - Thực Hành Cơ Sở Dữ Liệu

Repository này lưu trữ mã nguồn các bài tập và đồ án thực hành môn học **Cơ sở dữ liệu (IT004)**

Toàn bộ mô hình được thiết kế và truy vấn sử dụng ngôn ngữ **T-SQL** trên hệ quản trị **Microsoft SQL Server**.

## Cấu trúc Repository

Dựa trên yêu cầu đề bài đính kèm (`BaiTap_THCSDL_v2025.doc`), thư mục hiện tại bao gồm mã nguồn của hai hệ thống nghiệp vụ lõi:

* **`QUẢN LÝ BÁN HÀNG/`**: Cơ sở dữ liệu phục vụ quy trình kinh doanh bán lẻ. Xử lý lưu trữ thông tin khách hàng, nhân viên, danh mục sản phẩm, quản lý hóa đơn và chi tiết hóa đơn.
* **`QUẢN LÍ HỌC VỤ/`**: Cơ sở dữ liệu phục vụ quản lý giáo dục. Xử lý dữ liệu về khoa, môn học, giáo viên, học viên, phân công lịch giảng dạy và theo dõi kết quả thi cử.

## Kỹ năng Kỹ thuật & Nghiệp vụ 

* **Thiết kế Schema (DDL):** Khởi tạo cấu trúc bảng, thiết lập Khóa chính (Primary Key), Khóa ngoại (Foreign Key) để định hình các mối quan hệ `1-N`, `N-N`, và cài đặt các ràng buộc toàn vẹn (`CHECK`).
* **Trigger:** Xây dựng các triggers xử lý logic nghiệp vụ tự động đảm bảo tính toàn vẹn dữ liệu.
* **Truy vấn (DQL):** Trích xuất thông tin bằng các kỹ thuật `JOIN`, hàm tập hợp (`SUM`, `MAX`, `COUNT`), gom nhóm (`GROUP BY`, `HAVING`), truy vấn lồng (Subqueries), phép chia tập hợp (`NOT EXISTS`), và kỹ thuật xếp hạng (`RANK() OVER`).

## Công cụ Sử dụng
* **RDBMS:** Microsoft SQL Server
* **IDE/Client:** SQL Server Management Studio (SSMS)
