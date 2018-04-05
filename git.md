  先建立好一个仓库，然后自己的本地电脑随地找个方便的地方建立一个文件夹
  通过  git clone http:\\xxxxx 会把仓库以文件夹的形式在本地建立，把需要上传的文件拖进仓库文件夹里，执行
   git add .
   git commit -m ''
   git push

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
fatal: HttpRequestException encountered.
   发送请求时出错。
Username for 'https://github.com': 123907186@qq.com
Password for 'https://123907186@qq.com@github.com':
Counting objects: 3, done.
Delta compression using up to 8 threads.
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 2.86 KiB | 586.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/InitialMe/python-note.git
 * [new branch]      master -> master
PS C:\Users\12390\Desktop\python\python-note>
```
