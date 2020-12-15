Bài 1: Bem là gì? Tìm hiểu về Bem khi đặt tên class	
  --> là tiêu để chuẫn khi đặt tên class
1)Ý nghĩa.
  - Viết tắt của từ: Block Element Modifier
  - Block: Khối
  - Element:thành phần trong khối
  - Modifiler: Bổ sung ý nghĩa cho 'Block' hoặc 'Element'
  !nếu muốn thêm những cái khác so với cái cũ thì ta thêm một class mới 
2)Tại sao phải sử dụng Bem?
  - mỗi người đặt một kiểu riêng 
  - members đặt class trùng nhau, css đè lên nhau
--> trùng class,css dẫn đến ghi đè hông 
3)Cú pháp
  -.block
  -.block__element

  -.block--modifier
  -.block__element--modifier
 --> block và element là trạng thái bình thường còn modifier là bổ nghĩa
4)Tính ứng dụng  
  - xây dựng layout website 
  - xây dựng các thành phần trên website 
5)Ưu điểm  
  - Tính rõ ràng 
  - Tái sử dụng dễ dàng 
  - giúp cả team làm việc với nhau dễ dàng 
  - Tính module, không lo css của class này sẽ ảnh hướng lên CSS của class khác 
6)Nhược điểm 
  - Tên class dài 
  - da số người cho là xấu 
7)khi nào nên sử dụng BEM là phù hợp?
  - Dự án nhiều members
  - Dự án lớn, số lượng pages nhiều hoặc số lượng các thành phần trên giao diện nhiêu 
8)Thực hành 
 - Làm button
 - làm message
 - làm một thành phần trên website 