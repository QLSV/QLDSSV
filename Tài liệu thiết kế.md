CHƯƠNG 1. KHẢO SÁT, ĐẶC TẢ YÊU CẦU BÀI TOÁN

I. Mô tả yêu cầu bài toán

- Xây dựng chương trình “quản lý sinh viên” nhằm hỗ trợ cho công tác quản lý thông tin sinh viên, điểm… Bài toán đặt ra là phân tích thiết kế hệ thống thông tin vấn đề đặt ra là vì sao phải quản lý ? và quản lý như thế nào để công việc có hiệu quả, tiết kiệm được thời gian cho cán bộ nhân viên


- Bộ phận quản lý điểm lập danh sách thi, lập bảng điểm theo lớp, bảng điểm cho từng cá nhân dựa theo danh sách lớp, hồ sơ sinh viên… Bộ phận này sẽ lấy thông tin điểm quá trình từ giáo viên giảng dạy nhập vào các bảng điểm, cập nhật điểm thi ngay sau khi có kết quả thi. Tổng hợp điểm và tính ra điểm trung bình của từng sinh viên theo hệ số 10, hệ chữ, và hệ 4. Tất cả được in ra để gửi tới các lớp và được lưu lại để tiện theo dõi.
Bảng điểm bao gồm các loại sau:

-Bảng điểm tổng hợp: là bảng điểm của tất cả các môn. Trong đó sẽ có điểm quá trình, điểm thi và điểm trung bình môn.

-Bảng điểm tổng hợp cuối mỗi kỳ sẽ được in và gửi tới các lớp để sinh viên biết điểm.

-	Bảng điểm học phần: Là bảng điểm thống kê theo từng học phần sẽ được tra cứu theo từng học kỳ. 

-	Bảng điểm cá nhân: là bảng điểm chứa tất thông tin điểm tất cả các môn học của 1 sinh viên Với tình hình hiện nay, với số lượng sinh viên ngày càng nhiều, công tác quản lý điểm cho sinh viên ngày càng được chú trọng hơn. Đặc biệt hơn nữa là có sự hỗ trợ to lớn từ máy tính,. Việc xây dựng hệ thống quản lý điểm bằng máy tính dựa trên phương pháp quản lý mới,khắc phục được những nhược điểm của hệ thống cũ để xây dựng hệ thống mới khả thi hơn.Công tác quản lí điểm phục vụ cho sinh viên là chủ yếu, ngoài ra bảng điểm sinh viên được lưu trữ ở kho hồ sơ của trường. Theo hệ thống cũ, mọi hồ sơ được lưu bằng các văn bản, giấy tờ. hiện nay để làm giảm các công việc thì các bảng điểm và các công tác tính điểm được thực hiện bởi máy tính và phần mềm quản lí điểm sinh viên. Như vậy phần mềm này đã góp sức làm giảm thiểu sai sót, và làm công việc quản lí điểm tốn ít thời gian hơn.
Hiện nay các trường đại học của Việt Nam, cũng như các doanh nghiệp đang trong tiến trình ứng dụng mạnh mẽ sự phát triển của công nghệ thông tin vào quản lý. Mới đầu chỉ là những máy tính cá nhân đơn giản và cho đến nay là các mạng thông tin phức tạp. Tuy nhiên do đặc điểm công nghệ thông tin của Việt Nam mới trong quá trình phát triển nên mặc dù đã quan tâm đến việc ứng dụng công nghệ thông tin vào quản lý nhưng các phần mềm hệ thống, các phần mềm trợ giúp hoặc phần mềm quản lý có thể thay thế hoàn toàn công việc thủ công chưa được quan tâm. Với chương trình “quản lý điểm sinh viên” này hy vọng sẽ giúp cho công tác quản lý sinh viên diễn ra đơn giản và tiết kiệm thời gian hơn

II. Mô tả các loại người dùng
    
    Người dùng được chia làm hai đối tượng chính:quản lý hệ thống và người truy cập hệ thống để xem thông tin.
     
-    Quản lý hệ thống có quyền cập nhật, chỉnh sửa thông tin trong toàn hệ thống. Với hệ thống “quản lý sinh viên” người quản lý hệ thống có chức năng cập nhật thông tin về sinh viên như: họ tên , ngày sinh, quê quán, ngành hoc, lớp học, điểm.
      
      + Quản Lý Sinh Viên : Hệ thống sẽ nhập danh sách sinh viên có sẵn từ phòng  đào tạo, thêm  sửa  thông  tin sinh viên, và xóa sinh viên trong trường hợp sinh viên bị thôi học hoặc nguyên nhân nào đó.
      
      + Quản Lý Môn Học -Thêm môn học: Thêm môn học cho sinh viên sau khi có được danh sách các môn học trong học kỳ của sinh viên.Trong trường hợp có  sinh viên học lại hoặc học thêm môn học khác, bộ môn phải thêm vào. Và hệ thống quản lý cũng phải thêm môn học cho sinh viên để quản lý điểm môn đó. 
   Xóa môn học: nếu môn học bị thêm nhầm cho sinh viên, hệ thống có thể xóa đi.
      
      +Theo Dõi Xử Lý Điểm: Quá trình này, là quá trình cốt lõi của hệ   thống, nó bao gồm các chức năng con .
      
      +Nhập Điểm: Hệ thống sẽ  nhận điểm từ giáo viên bộ môn và nhập vào hệ thống điểm. Lần 2 hệ thống sẽ nhập nguồn điểm từ kết quả thi của sinh viên trong kỳ thi. Sau đó , tổng điểm của cả hai lần và đưa ra kết quả cuối cùng. 	
     
     +Sửa Điểm: Sau khi báo điểm cho sinh viên nếu có sai xót có thể sửa lại
     
-   Người truy cập hệ thống là những người cần lấy thông tin cần thiết từ hệ thống. Và đối tượng này khi truy cập vào hệ thống để xem thông tin cần có tài khoản. Đối tương này chỉ có quyền truy nhập xem thông tin chứ không thể cập nhật,sửa đổi thông tin trong hệ thống.

III. Biểu đồ lớp

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

 

CHƯƠNG 2.	XÂY DỰNG HỆ THỐNG

I. Các giao diện phần mềm
	
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
 
 
