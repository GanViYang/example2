# 进入你的项目目录
cd your-project-directory

# 初始化本地Git仓库（如果还没有初始化）
git init

# 添加所有文件到暂存区
git add .

# 提交文件
git commit -m "Initial commit"

# 添加远程仓库（替换为你的仓库URL）
git remote add origin https://github.com/your-username/your-repo.git

# 推送到GitHub
git push -u origin master

git lfs install
git lfs track "*apple.jpeg"  # 假设你上传的是JPEG图片
git add .gitattributes
git add .
git commit -m "Track large files with Git LFS"
git push -u origin master
