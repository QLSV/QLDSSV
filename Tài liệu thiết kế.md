CHƯƠNG 1. KHẢO SÁT, ĐẶC TẢ YÊU CẦU BÀI TOÁN

I. Mô tả yêu cầu bài toán


Bảng điểm bao gồm các loại sau:

-Bảng điểm tổng hợp: là bảng điểm của tất cả các môn. Trong đó sẽ có điểm quá trình, điểm thi và điểm trung bình môn.

-Bảng điểm tổng hợp cuối mỗi kỳ sẽ được in và gửi tới các lớp để sinh viên biết điểm.

-	Bảng điểm học phần: Là bảng điểm thống kê theo từng học phần sẽ được tra cứu theo từng học kỳ. 

-	Bảng điểm cá nhân: là bảng điểm chứa tất thông tin điểm tất cả các môn học của 1 sinh viên Với tình hình hiện nay, với số lượng sinh viên ngày càng nhiều, công tác quản lý điểm cho sinh viên ngày càng được chú trọng hơn. Đặc biệt hơn nữa là có sự hỗ trợ to lớn từ máy tính,. Việc xây dựng hệ thống quản lý điểm bằng máy tính dựa trên phương pháp quản lý mới,khắc phục được những nhược điểm của hệ thống cũ để xây dựng hệ thống mới khả thi hơn.Công tác quản lí điểm phục vụ cho sinh viên là chủ yếu, ngoài ra bảng điểm sinh viên được lưu trữ ở kho hồ sơ của trường. Theo hệ thống cũ, mọi hồ sơ được lưu bằng các văn bản, giấy tờ. hiện nay để làm giảm các công việc thì các bảng điểm và các công tác tính điểm được thực hiện bởi máy tính và phần mềm quản lí điểm sinh viên. Như vậy phần mềm này đã góp sức làm giảm thiểu sai sót, và làm công việc quản lí điểm tốn ít thời gian hơn.
Hiện nay các trường đại học của Việt Nam, cũng như các doanh nghiệp đang trong tiến trình ứng dụng mạnh mẽ sự phát triển của công nghệ thông tin vào quản lý. Mới đầu chỉ là những máy tính cá nhân đơn giản và cho đến nay là các mạng thông tin phức tạp. Tuy nhiên do đặc điểm công nghệ thông tin của Việt Nam mới trong quá trình phát triển nên mặc dù đã quan tâm đến việc ứng dụng công nghệ thông tin vào quản lý nhưng các phần mềm hệ thống, các phần mềm trợ giúp hoặc phần mềm quản lý có thể thay thế hoàn toàn công việc thủ công chưa được quan tâm. Với chương trình “quản lý điểm sinh viên” này hy vọng sẽ giúp cho công tác quản lý sinh viên diễn ra đơn giản và tiết kiệm thời gian hơn



II. Biểu đồ lớp

Sơ đồ phân rã chức năng của hệ thống (BFD)

 ![mo hinh phan ra](https://user-images.githubusercontent.com/27815316/28240787-d402375c-69b1-11e7-85de-2f18988b4c3b.png)
 
 
Biểu đồ luồng dữ liệu

 ![bi u d lu ng d li u](https://user-images.githubusercontent.com/27815316/28240565-9fcb8ce8-69ae-11e7-88d4-fe82d50033e3.png)
 
Biểu đồ luồng dữ liệu mức đỉnh (DFD)

 ![bi u d lu ng m c d nh](https://user-images.githubusercontent.com/27815316/28240583-f61b1a6e-69ae-11e7-935f-20c2dbfafb85.png)
 

Biểu đồ luồng dữ liệu phân rã chức năng quản sinh viên 

![bieu do luong du lieu phan ra chuc nang sinh vien](https://user-images.githubusercontent.com/27815316/28240624-71f0ea10-69af-11e7-8c51-db3d7c31b67c.png)
 

Biểu đồ luồng dữ liệu cho chức năng quản lý điểm
 
 
 ![bieu do luong diem](https://user-images.githubusercontent.com/27815316/28240663-e807f7e8-69af-11e7-9b08-a20bac348d2b.png)
 

Biểu đồ luồng dữ liệu cho chức năng quản lý môn học

![bieu do luong mon hoc](https://user-images.githubusercontent.com/27815316/28240712-792027fa-69b0-11e7-8962-bd00393578e9.png)
 


Biểu đồ quan hệ (ER)

![mo hinh quan he](https://user-images.githubusercontent.com/27815316/28240714-8ffb3d7a-69b0-11e7-9ae5-24c821831971.png)

 

CHƯƠNG 2.	THIẾT KẾ CƠ SỞ DỮ LIỆU : THIẾT KẾ VÀ MÔ TẢ MÔ HÌNH DỮ LIỆU VẬT LÝ

I.Cơ sở dữ liệu

o	Bảng tblDangNhap (fldTenDangNhap, fldMatKhau, fldHoTen, fldEmail)

CREATE TABLE tblDangNhap(

fldTenDangNhap    nvarchar(50) NOT NULL PRIMARY KEY,

fldMatKhau        nvarchar(20) NOT NULL,

fldHoTen          nvarchar(50) NOT NULL,

fldEmail          nvarchar (50) NOT NULL)  


![bangdn](https://user-images.githubusercontent.com/27815316/28241364-536e4fe8-69bd-11e7-8f64-af8af20790a2.png)


o	Bảng tblDiem (fldMaSV, fldMaMH, fldLanThi, fldHeSo, fldDiem, fldTrangThai)

CREATE TABLE tblDiem(

fldMaSV      nvarchar(10) NOT NULL PRIMARY KEY,

fldMaMH      nvarchar(10) NOT NULL,

fldLanThi    tinyint      NOT NULL,

fldHeSo      tinyint      NOT NULL,

fldDiem      float        NOT NULL,

fldTrangThai bit         NOT NULL)
  
  
  ![bangdiem](https://user-images.githubusercontent.com/27815316/28241374-7f4710d2-69bd-11e7-8d83-f47eebd91878.png)
  

o	Bảng tblGiangVien (fldMaGV, fldHoTenGV, fldMaMH, fldNgaySinh, fldGioiTinh, fldEmail, fldDiaChi, fldSDT) 

CREATE TABLE tblGiangVien(

fldMaGV        nvarchar(10) NOT NULL PRIMARY KEY,

fldHoTenGV     nvarchar(70) NOT NULL,

fldMaMH        nvarchar(10) NOT NULL,

fldNgaySinh    datetime     NOT NULL,

fldGioiTinh    bit          NOT NULL,

fldEmail       nvarchar (50) NOT NULL,

fldDiachi      nvarchar (70) NOT NULL,

fldSDT         nvarchar (15) NOT NULL)  




![banggiangvien](https://user-images.githubusercontent.com/27815316/28241377-958438ac-69bd-11e7-8dc0-11ea749dcc6f.png)



o	Bảng tblKhoa (MaSV, MaMH, DiemKT, DiemThi)

CREATE TABLE tblKhoa(

fldMaKhoa       nvarchar(10) NOT NULL PRIMARY KEY,

fldTenKhoa      nvarchar (50) NOT NULL,

fldSDT          nvarchar (15) NOT NULL)


![bangkhoa](https://user-images.githubusercontent.com/27815316/28241380-a8d6fc50-69bd-11e7-87f5-75e68bcbc1f2.png)


o	Bảng tblLop (fldMaLop, fldTenLop, fldMaKhoa, fldKhoaHoc)

CREATE TABLE tblLop(

fldMaLop   	nvarchar(10) NOT NULL PRIMARY KEY,

fld TenLop    nvarchar (50) NOT NULL,

fldMaKhoa     nvarchar (10) NOT NULL,

fldKhoaHoc    nvarchar (20) NOT NULL) 


![banglop](https://user-images.githubusercontent.com/27815316/28241386-b95e295e-69bd-11e7-9004-18a3759ea6e4.png)


o	Bảng tblMonHoc (fldMaMH, fldTenMh, fldSoTrinh, fldHinhThucThi, fldHocKy, fldPhongHoc)

CREATE TABLE tblMonHoc(

fldMaMH 			nvarchar (10) NOT NULL PRIMARY KEY,

fldTenMH      	nvarchar (20) NOT NULL,

fldSoTrinh		int			NOT NULL,

fldHinhThucThi 	nvarchar (20) NOT NULL,

fldHocKy			int NOT NULL,

fldPhongHoc		nvarchar (10) NOT NULL)  



![bangmh](https://user-images.githubusercontent.com/27815316/28241393-cbbbf284-69bd-11e7-8705-609c77f7f637.png)







o	Bảng tblSinhVien ( fldMaSV, fldHoten, fldMaLop, fldHeDaoTao, fldNgaySinh, fldDiaChi, fldGioiTinh, fldSDT)

CREATE TABLE tblSinhVien(

fldMaSV		nvarchar (10) NOT NULL PRIMARY KEY,

fldHoTen 		nvarchar (70) NOT NULL,

fldMaLop		nvarchar (10) NOT NULL,

fldHeDaoTao   nvarchar (50) NOT NULL,

fldNgaySinh	datetime		NOT NULL,

fldDiaChi		nvarchar (100)NOT NULL,

fldGioiTinh	bit			NOT NULL,

fldSDT		nvarchar (15) NOT NULL)
 


![bangsv](https://user-images.githubusercontent.com/27815316/28241396-d808e0b0-69bd-11e7-92c5-a81ac41379db.png)










II. Các giao diện phần mềm
	
  Giao diện đăng nhập 
 
 ![form dang nhap](https://user-images.githubusercontent.com/27815316/28240736-057f8fa6-69b1-11e7-8a56-b0f4025bd339.png)
 
 
Giao diện thông tin sinh viên

![thong tin sinhvien](https://user-images.githubusercontent.com/27815316/28240738-18fc64aa-69b1-11e7-9d75-5a4f7bc0ff4f.png)

 
Giao diện thông tin giáo viên
 
![thong tin giao vien](https://user-images.githubusercontent.com/27815316/28240748-34879fb4-69b1-11e7-8103-0a4bcddec448.png)

Giao diện thông tin lớp
 
 
 ![thong tin lop](https://user-images.githubusercontent.com/27815316/28240754-4a1bd412-69b1-11e7-8ae6-43c94a38e329.png)
 

Giao diện thông tin khoa

 ![thong tin khoa](https://user-images.githubusercontent.com/27815316/28240758-561a5982-69b1-11e7-8d80-20dab03b540b.png)
 

Giao diện thông tin môn học

 
 ![thong tin mon hoc](https://user-images.githubusercontent.com/27815316/28240766-67501728-69b1-11e7-8184-60913e732453.png)
 

Giao diện nhập điểm

 
 ![nhap diem](https://user-images.githubusercontent.com/27815316/28240768-79e654ba-69b1-11e7-8ca8-04d514b490a4.png)
 
 
Giao diện tính điểm

 ![tinhdiem](https://user-images.githubusercontent.com/27815316/28240770-8ad1bb16-69b1-11e7-9da9-3b626dc4d4a8.png)
 
 
