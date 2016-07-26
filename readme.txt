git 学习心得

-- 本地仓库初始化
git init

-- git本地仓库提交
git add readme.txt
git commit -m "wrote a readme file"

--git 创建ssh key 
	打开gitBash命令窗口输入命令：
	命令:  ssh-keygen -t rsa -C "youremail@example.com"

-- github 添加秘钥
	网址: https://github.com/settings/ssh 
	添加自己的公钥id_rsa.pub

-- 关联远程仓库
	在本地仓库中运行命令 git remote add origin git@github.com:michaelliao/learngit.git

-- 远程提交
	git push origin master

-- 从远程服务器克隆仓库到本地
	git clone git@github.com:michaelliao/gitskills.git