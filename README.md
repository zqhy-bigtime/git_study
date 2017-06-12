# git_study
1·对于本地安装的git工具首先要进行配置邮箱和名字
git config --global user.name  "zqhy-bigtime"
git config --global user.email "zqhy_0929@163.com"
2.初始化仓库
  进入要git管理的上一层目录git init 初始化仓库
3.添加到仓库
  git add (如果是多个文件可以是git add .)
4.提交到仓库
  git commit -m "提交的Mark信息"
5.查看当前状态
 git status
6.查看历史信息
 git log (git reflog)
7.回溯某一次提交状态
  根据git reflog 查看相应提交信息所对应的ID值
  git reset --hard XXXID
