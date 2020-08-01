
下载一个刚刚创建的Repositories
D:\github>md prokyle

D:\github>cd prokyle

D:\github\prokyle>git clone https://github.com/prokyle
Cloning into 'prokyle'...
remote: Not Found
fatal: repository 'https://github.com/prokyle/' not found

D:\github\prokyle>git clone https://github.com/prokyle.git
Cloning into 'prokyle'...
remote: Not Found
fatal: repository 'https://github.com/prokyle.git/' not found

D:\github\prokyle>git clone https://github.com/prokyle/Python.git
Cloning into 'Python'...
Username for 'https://github.com': prolee@prokyle.com
Password for 'https://prolee@prokyle.com@github.com':
warning: You appear to have cloned an empty repository.

D:\github\prokyle>dir
 驱动器 D 中的卷没有标签。
 卷的序列号是 74CE-7376

 D:\github\prokyle 的目录

2020/08/01  13:15    <DIR>          .
2020/08/01  13:15    <DIR>          ..
2020/08/01  13:15    <DIR>          Python
               0 个文件              0 字节
               3 个目录 822,174,916,608 可用字节

创建一个新的仓库，!!!需要在网页上先创建一个repositories，否则无法提交！！！
D:\github\prokyle>md test

D:\github\prokyle>cd test

D:\github\prokyle\test>dir
 驱动器 D 中的卷没有标签。
 卷的序列号是 74CE-7376

 D:\github\prokyle\test 的目录

2020/08/01  13:25    <DIR>          .
2020/08/01  13:25    <DIR>          ..
               0 个文件              0 字节
               2 个目录 822,175,023,104 可用字节

D:\github\prokyle\test>git init
Initialized empty Git repository in D:/github/prokyle/test/.git/

D:\github\prokyle\test>echo #test >README.md

D:\github\prokyle\test>echo #test >README.md

D:\github\prokyle\test>git commit -m "first commit"
On branch master

Initial commit

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md

nothing added to commit but untracked files present (use "git add" to track)

D:\github\prokyle\test>git add README.md

D:\github\prokyle\test>git commit -m "first commit"
[master (root-commit) a0bc70b] first commit
 1 file changed, 1 insertion(+)
 create mode 100644 README.md

D:\github\prokyle\test>git remote add origin https://github.com/prokyle/test.git

D:\github\prokyle\test>git push -u origin master
Username for 'https://github.com': prolee@prokyle.com
Password for 'https://prolee@prokyle.com@github.com':
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 214 bytes | 214.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/prokyle/test.git
 * [new branch]      master -> master
Branch 'master' set up to track remote branch 'master' from 'origin'.

D:\github\prokyle\test>





















