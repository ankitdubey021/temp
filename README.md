# temp


Administrator@admin-PC MINGW64 /d/delete (master)
$ git init
Reinitialized existing Git repository in D:/delete/.git/

Administrator@admin-PC MINGW64 /d/delete (master)
$ git remote add origin https://github.com/ankitdubey021/temp.git

Administrator@admin-PC MINGW64 /d/delete (master)
$ git add . # this adds all the files
warning: LF will be replaced by CRLF in .gitignore.
The file will have its original line endings in your working directory.

Administrator@admin-PC MINGW64 /d/delete (master)
$ git commit -a -m "Initial commit" #i've commited
[master (root-commit) 63aa1ef] Initial commit
 5 files changed, 40 insertions(+)
 create mode 100644 .classpath
 create mode 100644 .gitignore
 create mode 100644 .project
 create mode 100644 .settings/org.eclipse.jdt.core.prefs
 create mode 100644 src/dfgfdgfd/zxc.java

Administrator@admin-PC MINGW64 /d/delete (master)
$ git push -u origin --all
Counting objects: 10, done.
Delta compression using up to 2 threads.
Compressing objects: 100% (6/6), done.
Writing objects: 100% (10/10), 1.11 KiB | 568.00 KiB/s, done.
Total 10 (delta 0), reused 0 (delta 0)
To https://github.com/ankitdubey021/temp.git
 * [new branch]      master -> master
Branch 'master' set up to track remote branch 'master' from 'origin'.

