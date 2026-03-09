
进入文件后右键打开git bash；使用git init命令初始化仓库

配置全局用户名和邮箱

git config --global user.name "姓名"
git config --global user.email "邮箱"

添加当前目录下所有文件（所有新加的文件都需要先通过这一步）

git add .

查看当前仓库状态（助开发者了解哪些文件已经被修改、哪些文件被新增、哪些文件被删除等）

git status

提交更改到本体仓库（说明）

git commit -m "说明"

查看日志

git log

添加远程仓库（origin 是远程仓库别名）

git remote add origin git@github.com:用户名/仓库名.git

将本地文件推送到远程仓库,首次推送（建立关联）

git push -u origin 分支名

后续推送

git push

（第一次可能需要输入完整
git push origin main）

拉取并合并（最常用）

git pull
