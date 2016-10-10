git is a version control system.
git is a free software

======创建版本库
$ mkdir learngit
$ cd learngit
$ pwd

$ git init
Initialized empty Git repository in /Users/michael/learngit/.git/
$ git add readme.txt

$ git commit -m "wrote a readme file"
[master (root-commit) cb926e7] wrote a readme file
 1 file changed, 2 insertions(+)
 create mode 100644 readme.txt
 
$ git add file1.txt
$ git add file2.txt file3.txt
$ git commit -m "add 3 files."

初始化一个Git仓库，使用git init命令。

添加文件到Git仓库，分两步：

第一步，使用命令git add <file>，注意，可反复多次使用，添加多个文件；

第二步，使用命令git commit，完成。