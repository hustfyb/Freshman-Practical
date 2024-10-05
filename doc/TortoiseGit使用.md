## 1. TortoiseGit安装
在使用TortoiseGit之前必须要先安装Git。TortoiseGit没有独立的程序界面，所有操作集成在Explore中。
## 2. 创建仓库
本地Git仓库的创建有两种，一是直接Clone已存在的Git仓库，二是本地创建。
### 2.1 Clone仓库
在存放代码的目录点右键，选择Clone    
![](https://images.gitee.com/uploads/images/2019/0928/150652_540ef836_5267594.png "clone1.png")     
输入Url，自动创建本地目录，也可以手动选择    
![](https://images.gitee.com/uploads/images/2019/0928/150739_a180c535_5267594.png "clone2.png")     
确定以后就会Clone本地仓库了    
![](https://images.gitee.com/uploads/images/2019/0928/150810_29274a6c_5267594.png "clone3.png")     
### 2.2.创建本地版本库
新建一个项目目录StudyGit, 在代码目录右键选择创建版本库    
![](https://images.gitee.com/uploads/images/2019/0928/150833_27f7884c_5267594.png "clone4.png")     
弹出提示，不要勾选纯版本库，直接确定    
![](https://images.gitee.com/uploads/images/2019/0928/150857_b0de238d_5267594.png "clone5.png")     
目录下生成一个.git的目录，这个目录里面记录的是git操作相关内容，不要动。可以从这儿开始工作了。
## 3. Commit,Push,Pull
### 3.1.当修改完一段代码后，需要把代码提交到版本库中
以从远端Clone的库为例，在2.1.中的目录中右键点击Commit    
![](https://images.gitee.com/uploads/images/2019/0928/150920_0b2e5026_5267594.png "commit1.png")        
第一次操作的时候会提示需要输入身份（邮箱）    
![](https://images.gitee.com/uploads/images/2019/0928/150936_583a35cd_5267594.png "commit2.png")
点定后进入设置    
![](https://images.gitee.com/uploads/images/2019/0928/151002_3ebdbbb1_5267594.png "commit3.png")
确定后提交到本地版本库    
![](https://images.gitee.com/uploads/images/2019/0928/151058_b2bf8409_5267594.png "commit4.png")
### 2.2.推送Push更改
提交完成以后弹出如下提示
![](https://images.gitee.com/uploads/images/2019/0928/151123_8f2dca28_5267594.png "push1.png")
可以选择推送，也可以先关闭不Push，点了推送，如果是第一次会出现身份认证的对话框，输入仓库网站的用户密码即可。
否则出现下图对话框，可以选择推送到哪个分支    
![输入图片说明](https://images.gitee.com/uploads/images/2019/0928/151333_23382221_5267594.png "push2.png")
确定之后出现如下图的对话框
![](https://images.gitee.com/uploads/images/2019/0928/151240_ad6fef3d_5267594.png "push3.png")
### 2.3.拉取Pull
当工作组里面的其它人写了一段代码，你需要获取时，就需要用到Pull操作。
![](https://images.gitee.com/uploads/images/2019/0928/151449_37533e46_5267594.png "pull1.png")
选好远端分支，确定即可。
![](https://images.gitee.com/uploads/images/2019/0928/151144_9578719e_5267594.png "pull2.png")

本教程来源于网上(https://www.cnblogs.com/maojunyi/p/7735723.html)