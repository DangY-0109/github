#Terms
Repository(Repo)
Branch
Conflict  //xung đột, nếu có 2 branch mà thay đổi cùng một file thì sẽ xảy ra xung đột
Local
Remote
#Commands
- git init // Trở thành một Repository(Repo)
- git status // Thấy được dự án của mình
- git add // Chuẩn bị thêm dự án lưu ( "git add. " Chuẩn bị lưu tất cả)
- git reset // Đổi ý lấy lại cái chuẩn bị lưu
- git commit // Lưu chính thức và ghi chú git commit -m 'note'
- git log // xem lại những gì đã lưu từ trước đến nay
- git log --oneline // cũng là xem lại nhưng mà gọn hơn nè :3
- git checkout {branch name} // Qauy trở lại để kiểm tra cái cũ , quay trở lại để kiểm tra cái mới
- git checkout -b {branch name} // Tạo một branch mới
- git branch // Kiểm tra branch 

-- KHI TẠO MỘT TRANG MỚI EX: contact.html thì trước hết cần lưu lại -> git add . // SAU ĐÓ THÌ CẦN LƯU CHÍNH THỨC  -> git commit -m" name ".
- git merge {branch name} // Tổng hợp branch của dev và của master lại
- git branch -d {branch name} // xóa branch
- git push // đẩy lên local repos.. lên local...  git push ...link... {branch}