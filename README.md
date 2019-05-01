# 借助Github托管项目
### 仓库Repository：你的项目；每个项目对应一个仓库，多个开源项目则有多个项目，
### 收藏Star：收藏项目人数；方便下次查看
### Fork：复制克隆项目，会自动生成该仓库，其独立存在，forked from XXX
### PullRequest 想把自己的改进合并到原有项目里面的请求
### watch：关注项目，当有更新可收到通知
----------------------------------------------------------------------------------
## 仓库管理
### 创建文件
----------------------------------------------------------------------------------
## Git的安装和使用（管理GitHub托管项目代码）
### 下载地址：https://git-scm.com/downloads
#### 检验是否安装成功：点击桌面右键出现Git GUI和Git Bash
#### 设置用户名：git config --global user.name "xxxxx"
#### 设置邮箱：git config --global user.email "xxxx@163.com"
#### 命令：git init 创建Git仓库（是隐藏文件夹形式的）
### 向仓库中添加文件流程
 ![Image text](https://github.com/youcoding98/youcoding98/blob/master/img-storage/%E4%BB%93%E5%BA%93%E6%B7%BB%E5%8A%A0%E6%96%87%E4%BB%B6.png)
 #### touch a1.php  创建文件
 #### git status  查询文件状态
 #### git add a1.php 添加到暂存区
 #### git commit -m 'add a1.php' 将文件从暂存区提交到仓库
 --------------------------------------------------------------------
 #### vi a1.php 修改文件    git status 查看状态  git add a1.php 添加到暂存区
 #### git commit -m '第一次通过git修改文件并提交到仓库'
-----------------------------------------------------------------------
 #### rm -rf a1.php 删除文件
 #### git rm a1.php 从Git中删除文件
 #### git commit -m '第一次通过Git删除仓库文件'
 ----------------------------------------------------------------------
 ## Git管理远程仓库

