# Git-test1
练习Git1

# 将本地分支上传到特定服务器分支
创建分支
git branch main5
切换分支 
git checkout main5
添加所有工作区的文件到缓存区中
git add .
提交到本地仓库并注释提交信息
git commit -m 'version5'
将当前分支与远程服务器的指定分支关联
git branch --set-upstream-to=origin/master
git push origin HEAD:master


# 将本地分支上传到一个服务器没有的新分支
git push --set-upstream origin main5
git push

#使用git 设置代理vpn 
[https]
	proxy = http://127.0.0.1:10809

[http]
	proxy = http://127.0.0.1:10809
