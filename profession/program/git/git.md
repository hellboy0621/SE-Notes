# git 使用记录
***
git 在我看来是很重要的，怎么重要现在我的概念还不是太清楚，等我用一段时间以后补充
***

## 下面是一些git的使用心得

### 一、git 的初步使用基本配置步骤：
#### 1.git 的初始化：用户名和邮箱的配置（自己先申请一个git账号）
```
设置命令和方法如下：
```
```
git config --global user.name "这里填写你的用户名"
git config --global user.email "这里填写你的邮箱"
```
```
这样就配置好了用户
```

#### 2.创建版本库
```
到你想要将其内容上传git的目录下，运行下面的命令：
```
```
git init
```
```
我来演示一下，我是window系统，安装的是 git for window ，通过下面的步骤完成创建：
```
```
比如我想让 D:\tmp\test 这个目录创建版本库，想进入 D:\tmp\test 目录下：
```
![init1](./photo/init1.jpg)
```
然后鼠标右键，弹出如下的鼠标菜单选项：
```
![init2](./photo/init2.jpg)
```
简单的就是选择 GitExt Create new repository 生成版本库就行···········
但为了装一波，你得学会命令行的操作啊！点击Git Bash Here，输入 git init 出现像下面一样
的界面：
```
![init3](./photo/init3.jpg)
```
成功后生成 .git 的隐藏文件：
```
![init4](./photo/init4.jpg)

#### 3.添加文件
```
使用下面的命令添加该目录下的所有文件, "." 代表当前目录：
```
```
git add .
```

#### 4.提交至本地版本库中
```
把添加的文件提交到本地的版本库中，使用下面的命令：
```
```
git commit
```
```
会出现下面的界面叫你输入描述信息，这个其实随便输一点就行了,然后保存退出，就提交成功了
```
![init5](./photo/init5.jpg)
![init6](./photo/init6.jpg)

#### 5.连接远程版本库
```
你得把本地版本库和远程版本库连接起来，让本地版本库的文件能提交到远程版本库上，像下面这样
```
```
git remote add origin 你的远程版本库地址
```

#### 6.提交到远程版本库
```
git push origin master
```
```
后面加force是强制覆盖
```
```
git push origin master --force
```

## 强烈推荐链接
[http://mp.weixin.qq.com/s?__biz=MzA4NTQwNDcyMA==&mid=2650661735&idx=1&sn=9aceac07d272e9202d1b5294f857a5ff&scene=23&srcid=0527tuPapv7riaNZFSHQGe4w#rd](http://mp.weixin.qq.com/s?__biz=MzA4NTQwNDcyMA==&mid=2650661735&idx=1&sn=9aceac07d272e9202d1b5294f857a5ff&scene=23&srcid=0527tuPapv7riaNZFSHQGe4w#rd)

[http://mp.weixin.qq.com/s?__biz=MzA4NTQwNDcyMA==&mid=2650661762&idx=1&sn=8282241cf7414030f4e1d315a173beb1&scene=23&srcid=0527o8THYaNT8wb7pcE8JS5G#rd](http://mp.weixin.qq.com/s?__biz=MzA4NTQwNDcyMA==&mid=2650661762&idx=1&sn=8282241cf7414030f4e1d315a173beb1&scene=23&srcid=0527o8THYaNT8wb7pcE8JS5G#rd)

[http://www.admin10000.com/document/5374.html](http://www.admin10000.com/document/5374.html)
