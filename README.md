"Reinforce_learning" 

# 提交远程仓库
# 添加所有文件到暂存区
git add .
 
# 或者添加特定文件
git add filename.txt

# 提交更改，并附上提交信息
git commit -m "提交信息"

# 使用HTTPS URL
git remote add origin https://github.com/username/my_project.git

# 推送master/master分支的所有内容到远程仓库
git push -u origin master