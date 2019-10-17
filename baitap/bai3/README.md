Tạo 1 class SinhVien gồm các thuộc tính: id , họ, tên, điểm, giới tính và
các phương thức thực hiện:
* Phương thức khởi tạo SinhVien () tạo 1 SinhVien với thuộc tính mặc định
* Phương thức nhập nhap() lấy thông tin SinhVien từ bàn phím
* Phương thức hiển thị hienthi() 1 SinhVien ra màn hình
* Phương thức đọc docfile để tạo 1 SinhVien từ file sinhvien_id.dat
* Phương thức ghi ghiFile để lưu 1 SinhVien ra file sinhvien_id.dat
Lưu ý: tự xác định cấu trúc file sinhvien.dat
* Nạp Chồng phương thức khởi tạo để có thể tạo SinhVien với input từ bàn phím
* Phương thức sosanhTen(SinhVien sv) so sánh 2 họ tên với nhau (trả về 0 nếu
bằng nhau, -1 nếu sv nhỏ hơn, 1 nếu sv lớn hơn)
* Phương thức sosanh() kiểm tra 2 sinh viên có trùng tất cả thông tin với nhau

Tạo class DSSinhVien sử dụng class SinhVien ở , gồm  thuộc tính mảng SinhVien. Viết các phương thức thực hiện:
* Phương thức khởi tạo DSSinhVien() khởi tạo 1 danh sách rỗng
* Phương thức timkiem(ID) trả về sinh viên có mã tương ứng
* Phương thức sua(id=A, ho=x, ten=y,...  ) sửa sinh viên có ID là thành dữ liệu như các biến truyền vào (không giới hạn số lượng biến truyền vào)
* Phương thức xoa(int id) để xoá sinh viên có ID tương ứng
* Phương thức them(SinhVien sv) để them 1 sinh viên vào danh sách
* Phương thức sapxepHoTen() để sắp xếp lại sinh viên theo họ tên ABC.

Viết hàm main khởi tạo đối tượng DSSinhvien . Lần lượt chạy qua các phương thức cua DSSinhVien trên (input cho mỗi phương thức tự nghĩ). sử dụng chức năng debug của pycharm để kiểm tra hoạt động.

Không giới hạn thư viện sử dụng.VD sắp xếp, so sánh nếu tìm đc thư viện và dùng vào càng tốt.
