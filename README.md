Chế độ hoạt động :normal,insert,visual
-Mode Normal : 
+Phím a:chuyển mod insert tại vị trí sau con trỏ
+Phím A:chuyển mod insert tại vị trí cuối cùng
+Phím o:tạo 1 dòng mới ở dưới và chuyển mod insert tại đầu dòng đó
+Phím O:tạo 1 dòng mới ở phía trên
+Phím u:back lại
+Phím Cirl R:redo

-Mode Visual:bôi đen
+Phím V:chuyển sang mod Visual và bôi đen cả dòng
+Phím v+i+w:bôi đen một từ
+Phím g+g+V+G: bôi đen toàn bộ văn bản

-Mode command:
+echo "hello"

*Điều hướng: h,j,k,l
+Phím gg:lên đầu của file
+Phím G:di chuyển con trỏ xuống cuối file
+Phím :số dòng: di chuyển con trỏ tới dòng mong muốn
+Phím w: di chuyển đến word tiếp theo
+Phím b: di chuyển đến word trước đó
+Phím 0: di chuyển đến đầu dòng(hoặc Home)
+Phím $:di chuyển đến cuối dòng(hoặc End)

*Copy,Paste
+Phím y:copy 1 đoạn text được bôi đen
+Phím p:paste vào dòng bên dưới con trỏ
+Phím P: paste vào dòng bên trên con trỏ
+Phím d: cut 1 đoạn text được bôi đen

*Tìm kiếm :
+Phím /chuỗi_cần_tìm: tìm kiếm 
+Phím *: tìm kiếm word tại vị trí con trỏ
+Phím n: di chuyển con trỏ sang kết quả tìm kiếm tiếp theo
+Phím N: di chuyển con trỏ sang kết quả tìm kiếm trước đó
+Command :%s/text_cũ/text_mới: thay thế text
*Mở đóng file :
+Command :Ex,Vex,Sex: hiển thị thư muc 
+Command :e tên_file: mở file
+Command :q: thoát Vim
+Command :bd: thoát file đang mở
+Command :w: save file
+Command :wq :save và thoát 
+Command :q! :thoát nhưng không save
+Command :vs :mở file và chia đôi cửa sổ
+Phím Cirl+w+mũi tên/h/l:di chuyển con trỏ chuột khi chia đôi cửa sổ
+Phím Cirl+w+HJKL:đổi vị trí các ô
