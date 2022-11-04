# HuyNhat-Blog
link bài :https://drive.google.com/file/d/1JLs4bHYWUUm0t7ZO8COce4n1gZS6G_PJ/view?usp=sharing




[dotnet_version]
6.0.402
Lệnh dotnet
[install_dotnet-ef]
dotnet tool install --global dotnet-ef

<!-- dotnet restore --> không chạy được thì thử <!-- dotnet tool restore -->

tạo thêm thư mục Migrations nếu chưa có 
[Add_folder_Migrations]
dotnet ef migrations add Migrations

[Build_Project]
dotnet build

[database_update]
dotnet ef database update

[Run_project]
dotnet run




[Lệnh git]
add user.email and user.name
git config --global user.email "user@gmail.com"
git config --global user.name "username"
git add .
git commit -m "Initial commit"
git remote
git push

[HTTP]
http://localhost:5114/api/user
http://localhost:5101/swagger

[Body postman]
{
"DisplayName":"Dang Huy Nhat",
"Email" : "huynhat2412@gmail.com",
"Phone" :"0353482293"
}
