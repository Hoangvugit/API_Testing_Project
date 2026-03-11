📌 Hướng dẫn đồng bộ GitHub cho dự án nhóm
1. Repo chính
- Chỉ cần một repo duy nhất trên GitHub cho cả dự án.
- Repo chính Vũ tạo là API_Testing_project
- Người tạo repo thêm 2 thành viên còn lại làm collaborator để cả team có quyền push/pull.
2. Clone repo về máy
- Mỗi thành viên tải repo về máy bằng lệnh:
- git clone https://github.com/Hoangvugit/API_Testing_Project.git
3. Tạo branch riêng cho từng người
  - Thành viên Backend (Đạt):Nhập lệnh
    git checkout -b backend
  - Thành viên Frontend (Vũ):
    git checkout -b frontend
  - Thành viên tích hợp AI (Nhị) :
    git checkout -b ai-module
4. Quy trình làm việc hằng ngày
 - Pull code mới nhất từ dev trước khi bắt đầu:
    git pull origin dev
 - Code trong branch của mình.
 - Commit thường xuyên với message rõ ràng:
    git add .
    git commit -m "Mô tả rõ ràng thay đổi"
 - Push lên GitHub:
    git push origin <branch-name>
 - Tạo Pull Request (PR) từ branch của mình vào dev.
 - Review chéo: ít nhất một thành viên khác xem PR trước khi merge.
 - Khi ổn định, nhóm trưởng merge dev vào main.
5. Quy ước chung
 - Không commit trực tiếp vào main.
 - Luôn pull code mới nhất trước khi code.
 - Commit message ngắn gọn, mô tả rõ thay đổi.
 - Dùng Issues để ghi nhận bug hoặc yêu cầu mới.
 - Dùng Project Board để quản lý tiến độ (To Do → In Progress → Done).







