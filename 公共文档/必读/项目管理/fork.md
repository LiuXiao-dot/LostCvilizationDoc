# 目录
[TOC]
# fork使用说明
## clone项目
 （不会请百度）
## 小型任务工作流程
1.在main分支中修改
2.检查修改，将不是自己改的内容Discard，自己改的Stage
3.写上注释并Commit，注释标题：分支名或任务名，注释详细内容：分条列出（可不全）
4.Pull至最新
5.处理冲突，必要时复制取消自己的提交，把修改的内容复制一下，先更新再重新改
6.Push
## 大任务工作流程
1.创建任务分支
2.在分支中任意修改
3.执行当前分支Rebase On Main,将主分支的修改内容同步到当前分支中
4.处理冲突
5.checkout到Main分支
6.执行Main分支Rebase On 修改分支
7.Push
