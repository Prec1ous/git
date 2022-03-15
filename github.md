# github 操作   

## 远程仓库操作

|   代码功能    |   如何实现   |
| ------------ | ---------- |
| 查看所有远程库别名 |  git remote -v |
| 为远程库起别名     |  git remote add "别名" "远程地址"|
| 推送本地分支到远程库 | git push "别名" "分支名" |
| 拉取远程库到本地库 | git pull "别名" "分支名" | 
| 克隆远程库到本地库 | git clone "远程链接" | 

![github基础操作图](https://img.php.cn/upload/image/719/194/534/1641535866915411.png)

- fork 从他人的远程库复制到自己的远程库
- Pull request 从自己的远程库发送推送请求到他人的远程库

> ### 笔记：
> - push和pull需要再同一团队才能操作
> - clone会做如下步骤： 1、拉取代码。2、初始化本地仓库。3、创建别名
> - fork后修改的代码只会提交到自己的本地库

### ssh免密登录
- 生存.ssh密钥目录  ssh-keygen -t rsa -C "邮箱地址@qq.com"
- id_rsa 为私钥  id_rsa.pub为公钥
- 打开github -> setting -> SSH and FPG keys 将公钥粘贴进去
