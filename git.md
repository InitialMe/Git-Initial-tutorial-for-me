		使用git要先安装git并添加好环境变量路径，环境变量路径可以在安装时选择自动添加或者自己手动添加
		先建立好一个仓库，然后自己的本地电脑随地找个方便的地方建立一个文件夹
		在文件夹的地址栏输入powershell，或者cmd
		在终端输入git clone http:\\xxxxx (在clone or download那里可以复制地址)会把仓库以文件夹的形式在本地文件夹建立
		把需要上传的文件拖进仓库文件夹里执行
		git add .  //"."代表上传所有文件，.\xxxx.xx代表上传的具体文件名
		git commit -m ''
		git push
		剩下的输入账号密码
		亦可以尝试使用客户端GitKraken,比官方客户端好用系列
		建议所有笔记markdown记录 下载地址：[下载地址](http://markdownpad.com/download.html)
		人家整理的常用markdown语法      [别人的博客](https://www.jianshu.com/p/82e730892d42)
					      [别人的博客2](https://blog.csdn.net/kaitiren/article/details/38513715)

```powershell
PS C:\Users\12390\Desktop\python> git clone https://github.com/InitialMe/python-note.git
Cloning into 'python-note'...
warning: You appear to have cloned an empty repository.
PS C:\Users\12390\Desktop\python> cd python-note
PS C:\Users\12390\Desktop\python\python-note> git add .\基础笔记.py
PS C:\Users\12390\Desktop\python\python-note> git commit -m 'add'
[master (root-commit) 64e663c] add
 1 file changed, 166 insertions(+)
 create mode 100644 "\345\237\272\347\241\200\347\254\224\350\256\260.py"
PS C:\Users\12390\Desktop\python\python-note> git push
```
```powershell
git status   #进入git项目的本地文件夹，将自己的项目复制到这个git 文件夹，查看状态，提交所有的新文件
git add -A  
git commit -a -m"first commit"
git push 
git add -A  //提交所有变化  
git add -u  //提交被修改(modified)和被删除(deleted)文件，不包括新文件(new)  
git add .  //提交新文件(new)和被修改(modified)文件，不包括被删除(deleted)文件
```
