# ceshiGit


# 创建开发分支1
1、git checkout -b develop_1      

#  将本地创建的 开发分支 push到远程仓库
2、git push origin develop_1:develop_1

# 进入 git 刷新一下， 你会发现分支变成了 2个 master和develop_1   其中develop_1 有修改  master中没有
#  接下来是  合并 两个 分支  在 远程 git上操作

		a、在分支 （最好develop_1）下 ，点击 Compare & pull request 按钮 数据 title和commit 内容
		b、然后在 Pull request 下就可以看到 你的 title和commit 
		c、进入 Pull request 下的 commit 就可以看到 你的 所有的 commit 
		d、Files Changed 中可以看到你修改的内容  并且可以在 Review Changes中写下你的 建议和 修改内容
		e、如果最后没有问题 可以在 Conversation 中点击 Merge Pull request
		
#  以上 是发送 pull request的过程。这个过程可以 进行 code review


这种方式 适用于 人数少   两个人在同一个分支上开发  最后每次都合并到主分支上