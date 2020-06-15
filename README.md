#How To Use Git

##Setup
1. Tạo 1 repositories trên GitHub
2. Tạo 1 folder dưới máy để chứa dự án với tên bất kỳ
3. Khởi tạo git đầu tiên cho project: git init

##Connect folder and GitHub
git remote add origin <link >
git remote -v: kiểm tra liên kết link đúng chưa

##Push file
1. Tạo file trong folder
2. git status: Kiểm tra file mới thêm vào
3. git add . (git add --all): thêm tất cả các file project vào:
4. git commit -m "nd commit": tạo commit:
5. git log (gitk: debug trước khi chạy): kiểm tra commit thành công: 
6. git push origin master: đẩy lên git

##Restore file
git restore <Tên file>
Quay lai phien ban truoc
git reset --hard <commit_id>

##Pull
git pull <link gitHub>: lấy dự án về
git push origin master -f: