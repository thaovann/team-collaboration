# Terms
Resository
Branch
Conflict // xung đột
local : tất cả những gì trên máy tính
remote : dữ liệu trên 1 server nào đó
# Commnand
- git status: cho biet trang thai cua du an
- git add ten_file: lưu lại file
- git add . : chuẩn bị lưu lại toàn bộ file
- git reset : 
- git commit -m 'note_you_shoud_lwwrite': chính thức lưu
- git log     : xem những thời điểm đã lưu
- git log --oneline
- git checkout 'idcommit' : trở về trước khi có commit có id đó
- git checkout {branch name} : di chuyển đến branch khác/ kiểm tra branch hiện tại
- git branch : xuất ra danh sách branch
- git checkout -b {branch name}: tạo branch mới
- git merge {branch name} : tổng hợp lại branch vs branch main
- git branch -d {branch name}
- git push : đẩy lên 
- git remote add {name  // thường đặt là origin} {link project on github} : khi push những thay đổi lên thì ko cần gắn link github mà sẽ thay bằng tên mình đặt
- git push -u origin {branch name} : đẩy branch mới lên github
