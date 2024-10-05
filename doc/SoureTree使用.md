## 1. SourceTree安装
在使用SourceTree之前必须要先安装Git和sourceTree，注意新版的SourceTree安装的时候需要有bitbucket的账号，可以自行注册。    
## 2. 获取远程仓库地址
![获取远程仓库地址](https://images.gitee.com/uploads/images/2019/0925/194102_698a3d5c_5267594.png "address.PNG")
## 3. Clone远程仓库
打开sourcetree，点击tab页上的“+”号，准备创建新仓库，点击clone,填入远程仓库地址，目标路径（本地存放路径），点击克隆。如下图
![Clone](https://images.gitee.com/uploads/images/2019/0928/101450_8af88c08_5267594.png "clone.png")
## 4. 提交修改
提交和推送。由于git是分布式版本控制工具，存在着本地仓库和远程仓库，所以我们在本地工作副本进行的编辑，要先提交到本地仓库，再从本地仓库推送到远程仓库。在本地修改文件完成后，打开sourceTree, 可以看到文件的变动已经显示到软件界面，点击需要保存修改的文件，选择暂存所选，也可以直接选择暂存所有。
![add](https://images.gitee.com/uploads/images/2019/0928/102902_d11d5428_5267594.png "add.png")
输入提交注释，点击提交
![commit](https://images.gitee.com/uploads/images/2019/0928/103206_78dcca6d_5267594.png "commit.png")
## 5，推送远程仓库
提交完成后，可以看到日志/历史选项卡中已显示提交的版本日志，在master分支提交了新的修改及改动的内容，不过这个master分支是本地仓库的，并不是远程仓库的。此时的修改记录仅留在本地仓库，还需要用push操作将本地修改同步到远程仓库上。
![log](https://images.gitee.com/uploads/images/2019/0928/103431_0fa0519e_5267594.png "log.png")
点击推送，勾选将本地master分支推送到远程master分支，点击推送。
在首次推送时会提示要求输入仓库的用户名和密码，输入在网站上注册的用户和密码即可。
![push](https://images.gitee.com/uploads/images/2019/0928/125957_ea35aa23_5267594.png "push.png")
推送完成后，可以看到最新的版本里显示了master 和 origin/master，这表明本地master分支和远程master分支是同步的，登录Gitee可以看到仓库里已有提交记录了。如下图。这样本地修改的代码或文件就被同步到了远程仓库，可以被别人拉下来使用。
![pushLog](https://images.gitee.com/uploads/images/2019/0928/130250_fc53c83a_5267594.png "pushLog.png")
## 下一步
 拉取代码，分支，合并，冲突解决，回滚代码等功能的使用就留给同学们自行探索，可以通过在网上查阅相关资料完成。
