# git的操作笔记

### git分为 工作区，暂存区，本地库，(github,gitee)

1. 先初始化本地库  git init
2. 查看本地库状态  git status
3. 添加到暂存区    git add
4. 提交本地库      git commit -m "日志信息" "文件名"
5. 查看版本号      git reflog/git log(详)
6. 回滚版本号      git reset --hard "版本号"
7. 创建分支        git branch "分支名"
8. 查看分支        git branch -v
9. 切换分支        git checkout "分支名"
10. 合并分支       git merge "分支名"

新文件夹需要先git初始化才能进行操作   
每次修改文件需要添加暂存区，再提交本地库  
当合并冲突时，需手动打开文件打开文件进行修改  

pull  将本地库文件把工作区文件进行更新      
push  将暂存区文件推送到本地库    
clone 将本地库文件克隆到工作区    

.[github]{github.md}
.[IDEA]{IDEA-git.md}
