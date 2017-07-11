将github的账号和本地的仓库绑定，以明确身份：
git  config - -global  user.email  “2609016156@qq.com”
git  config - -global   user.name  “huainanwang”

git init 
git add README.md 
git commit -m "first commit"//提交暂存区的文件
git remote add origin https://github.com/huainanwang/study.git //添加远程仓库
git push -u origin master   //上传本地当前分支代码到master分支。（master是主分支）

工厂
   本地仓库
      集中仓库
	  今天学了git 的相关知识：
	  初始化本地仓库 git init
	  可以使用版本控制功能
	  将需要进行版本控制功能的文件，添加到git 管理中
	  git  add  filename
	  确认更改到git 中 
	  git  commit  –m“初始化了仓库” 
	  每次做修改，只需重复git add 和 git commit 操作即可
	  查看当前仓库中的文件状态：
	     git  status
		 查看历史提交：
		    git  log
			查看当前文件和仓库中文件的区别：
			   git  diff
