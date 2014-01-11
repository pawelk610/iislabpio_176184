Welcome to Git (version 1.8.3-preview20130601)


Run 'git help git' to display the help index.
Run 'git help <command>' to display help for specific commands.

admin@GX620 ~ (master)
$ cd ~c\Documents and Settings\admin\Pulpit\gitub
sh.exe": cd: ~cDocuments: No such file or directory

admin@GX620 ~ (master)
$ cd ~c\gitub
sh.exe": cd: ~cgitub: No such file or directory

admin@GX620 ~ (master)
$ cd ~c\\gitub
sh.exe": cd: ~c\gitub: No such file or directory

admin@GX620 ~ (master)
$ cd ~ c\github

admin@GX620 ~ (master)
$ git init
Reinitialized existing Git repository in C:/Documents and Settings/admin/.git/

admin@GX620 ~ (master)
$ touch README.md

admin@GX620 ~ (master)
$ cd ~c\github
sh.exe": cd: ~cgithub: No such file or directory

admin@GX620 ~ (master)
$ cd ~ c\github

admin@GX620 ~ (master)
$ git init
Reinitialized existing Git repository in C:/Documents and Settings/admin/.git/

admin@GX620 ~ (master)
$ cd ..

admin@GX620 /c/Documents and Settings
$ cd..
sh.exe": cd..: command not found

admin@GX620 /c/Documents and Settings
$ cd ..

admin@GX620 /c
$ cd ~ c\github

admin@GX620 ~ (master)
$ git init
Reinitialized existing Git repository in c:/Documents and Settings/admin/.git/

admin@GX620 ~ (master)
$ cd /c/github

admin@GX620 /c/github
$ git init
Initialized empty Git repository in c:/github/.git/

admin@GX620 /c/github (master)
$ touch README.md

admin@GX620 /c/github (master)
$ git add README.md

admin@GX620 /c/github (master)
$ git status
# On branch master
#
# Initial commit
#
# Changes to be committed:
#   (use "git rm --cached <file>..." to unstage)
#
#       new file:   README.md
#

admin@GX620 /c/github (master)
$ git config user.name "Pawel Karnecki"

admin@GX620 /c/github (master)
$ git config user.email "pawelk610@gmail.com"

admin@GX620 /c/github (master)
$ git commit -m "first commit"
[master (root-commit) 140b1dd] first commit
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 README.md

admin@GX620 /c/github (master)
$ git remote add origin https://github.com/pawelk610/iislabpio_176184.git

admin@GX620 /c/github (master)
$ git push -u origin master
Username for 'https://github.com': pawelk610
Password for 'https://pawelk610@github.com':
Counting objects: 3, done.
Writing objects: 100% (3/3), 216 bytes | 0 bytes/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/pawelk610/iislabpio_176184.git
 * [new branch]      master -> master
Branch master set up to track remote branch master from origin.

admin@GX620 /c/github (master)
$ git pull origin master
remote: Counting objects: 5, done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 3 (delta 0), reused 0 (delta 0)
Unpacking objects: 100% (3/3), done.
From https://github.com/pawelk610/iislabpio_176184
 * branch            master     -> FETCH_HEAD
Updating 140b1dd..43a7e97
Fast-forward
 README.md | 1 +
 1 file changed, 1 insertion(+)

admin@GX620 /c/github (master)
$
