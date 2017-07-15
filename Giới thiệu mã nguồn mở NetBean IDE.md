1.NETBEANS IDE CÔNG CỤ HỖ TRỢ LẬP TRÌNH MIỄN PHÍ TỐT NHẤT
NetBeans IDE là một công cụ hỗ trợ lập trình viết mã code miễn phí được cho là tốt nhất hiện nay, được sử dụng chủ yếu 
cho các lập trình viên phát triển Java tuy nhiên phần mềm có dung lượng khá là nặng dành cho các máy cấu hình có RAM, CPU tương đối cao 
để vận hành.
Netbean được viết bằng ngôn ngữ Java và có thể chạy trên được hầu hết các hệ điều hành phổ biến như: Windows, Linux, OS X và Solaris 
và các nền tảng khác nhau chỉ cần một JVM (Java Virtual Machine) tương thích.
NetBeans IDE được phát triển dựa trên một nền tảng có tên NetBeans Platform cho phép các ứng dụng được phát triển bởi một tập hợp
các thành phần bên trong nó gọi là Mô đun ngoài ra còn hỗ trợ các ứng dụng do bên thứ 3 phát triển. 
Mỗi lần ra mắt phiên bản mới nhà phát triển sản phẩm này đều ra mắt thử nghiệm và nhận đánh giá từ người dùng trước khi phát hành phiên bản
chính thức.
Netbeans IDE có nhiều gói (Bundles) tùy chỉnh cho phép lập trình viên download về để tiết kiệm dung lượng, tốc độ vận hành 
ngoài một gói cài đặt đầy đủ hỗ trợ tất cả các ngôn ngữ lập trình còn lại.
Netbeans hỗ trợ gợi ý cú pháp rất tốt, ngoài ra còn có các tính năng mạnh mẽ như (Format code) tự động căn chỉnh mã nguồn,
Remote FTP, SVN …. và rất nhiều tĩnh năng hữu ích khác.
Mã nguồn Netbean IDE mới nhất hiện nay là NetBean 8.2 .
2.	Hệ quản trị CSDL SQL Server
Một cơ sở dữ liệu - CSDL(DataBase): Là một kho dữ liệu được tổ chức theo một nguyên  tắc nào đó. Đó là một tập hợp  các tập tin  có 
liên  quan  với nhau, được thiết kế nhằm làm giảm thiểu sự dư thừa dữ liệu, đảm bảo tính tin cậy khi truy xuất dữ liệu. Các tập tin này chứa các thông tin biểu diễn các
đối tượng trong một ứng dụng thế giới thực. CSDL lưu giữ thông tin của một trường đại học như : khoa, giảng viên, sinh viên, khóa học,..
Thông thường, một cơ sở dữ liệu sẽ bao trùm tất cả các thông tin của một ứng dụng, không nên đặt hai cơ sở dữ liệu vào một ứng dụng.
-	Dư thừa dữ liệu và tính không nhất quán (Data redundancy and inconsistency) : Do các file và các trình ứng dụng được tạo ra bởi các
người lập trình khác nhau, nên các file có định dạng khác nhau, các chương trình được viết trong các ngôn ngữ lập trình khác nhau,
cùng một thông tin có thể được lưu giữ trong các file khác nhau. Tính không thống nhất và dư thừa này sẽ làm tăng chi phí truy xuất 
và lưu trữ, hơn nũa, nó sẽ dẫn đến tính không nhất quán của dữ liệu: các bản sao của cùng một dữ liệu có thể không nhất quán .
-	Khó khăn trong việc truy xuất dữ liệu: Môi trường của hệ thống xử lý file thông thường không cung cấp các công cụ cho phép truy xuất
thông tin một cách hiệu quả và thuận lợi.
-	Sự cô lập dữ liệu(Data isolation) : Các giá trị dữ liệu được lưu trữ trong cơ sở dữ liệu phải thoả mãn một số các ràng buộc về tính nhất
quán của dữ liệu ( ràng buộc nhất quán / consistency contraints ).
-	Trong hệ thống xử lý file thông thường, rất khó khăn trong việc thay đổi các chương trình để thoả mãn các yêu cầu thay đổi ràng buộc.
Vấn đề trở nên khó khăn hơn khi các ràng buộc liên quan đến các hạng mục dữ liệu nằm trong các file khác nhau.
-	Các vấn đề về tính nguyên tử (Atomicity problems).
-	Tính nguyên tử của một hoạt động (giao dịch) là: hoặc nó được hoàn tất trọn vẹn hoặc không có gì cả . Điều này có nghĩa là một hoạt động
(giao dịch) chỉ làm thay đổi các dữ liệu bền vững khi nó đã hoàn tất (kết thúc thành công) nếu không, giao dịch không để lại một dấu vết
nào trên CSDL. Trong hệ thống xử lý file thông thường khó đảm bảo được tính chất này.
-	Tính bất thường trong truy xuất cạnh tranh : Một hệ thống cho phép nhiều người sử dụng cập nhật dữ liệu đồng thời, có thể dẫn đến
kết quả là dữ liệu không nhất quán. Điều này đòi hỏi một sự giám sát. Hệ thống xử lý file thông thường không cung cấp chức năng này.
-	Vấn đề an toàn (Security problems): một người sử dụng hệ cơ sở dữ liệu không cần thiết và cũng không có quyền truy xuất tất cả các
dữ liệu. Vấn đề này đòi hỏi hệ thống phải đảm bảo được tính phân quyền, chống truy xuất trái phép ... Các bất lợi nêu trên đã gợi 
mở sự phát triển các DBMS. Phần sau của giáo trình sẽ đề cập đến các quan niệm và các thuật toán được sử dụng để phát triển một hệ cơ sở
dữ liệu nhằm giải quyết các vấn đề  nêu trên .


