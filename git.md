[GoGoCode的仓库](https://github.com/thx/gogocode/)
[B站的学习视频](https://www.bilibili.com/video/BV1db4y1d79C?t=1298)

# 用到的命令：

## 克隆仓库：

git clone git地址

## 初始化仓库：

git init 

## 添加文件到暂存区：

git add -A

## 把暂存区的文件提交到仓库：

git commit -m 

提交信息

（直接在vscode的上面的源代码管理下面的消息框比这个好用）

## 查看提交的历史记录：

git log --stat

(在下的的COMMITS比这个好用)

## 工作区回滚：

git checkout filename

(在**更改区**下,对应的更改文件有有四个按钮，点对应的第二个就 可以回滚)



## 撤销最后一次提交：

git reset HEAD^1

（COMMITS下点到对应想要回滚的地方，然后右键，选择第一个undo commit）

## 以当前分支为基础新建分支：

git checkout -b branchname

## 列举所有的分支：

git branch

## 单纯地切换到某个分支：

git checkout branchname

## 删掉特定的分支：

git branch -D branchname

## 合并分支：

git merge branchname

## 推送当前分支最新的提交到远程：

git push

## 拉取远程分支最新的提交到本地：

git pull
