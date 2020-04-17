# mypets

Procedimento OK>

babyc@Note-Keli MINGW64 /c/mypet
$ git config --global user.mail brunomacobeba@gmail.com

babyc@Note-Keli MINGW64 /c/mypet
$ git config --global user.name "Bruno Cesar"

babyc@Note-Keli MINGW64 /c/mypet
$ ssh-keygen -t rsa -b 4096 -C brunomacobeba@gmail.com
Generating public/private rsa key pair.
Enter file in which to save the key (/c/Users/babyc/.ssh/id_rsa):
/c/Users/babyc/.ssh/id_rsa already exists.
Overwrite (y/n)? y
Enter passphrase (empty for no passphrase):
Enter same passphrase again:
Your identification has been saved in /c/Users/babyc/.ssh/id_rsa
Your public key has been saved in /c/Users/babyc/.ssh/id_rsa.pub
The key fingerprint is:
SHA256:EyEpki0Wf7WQpr/PowWTdeKpUaHgIz2oQU5LGPWgccw brunomacobeba@gmail.com
The key's randomart image is:
+---[RSA 4096]----+
|+O=+. oo+        |
|*+EBo.+= +       |
|o+ooB+o * .      |
| o ..+ = =       |
|.    .= S        |
|      .= .       |
|      ...        |
|      .o.        |
|      .oo.       |
+----[SHA256]-----+

babyc@Note-Keli MINGW64 /c/mypet
$ eval $(ssh-agent -s)
Agent pid 1532

babyc@Note-Keli MINGW64 /c/mypet
$ ssh-add ~/.ssh/id_rsa
Identity added: /c/Users/babyc/.ssh/id_rsa (brunomacobeba@gmail.com)

babyc@Note-Keli MINGW64 /c/mypet
$ ls

babyc@Note-Keli MINGW64 /c/mypet
$ cd..
bash: cd..: command not found

babyc@Note-Keli MINGW64 /c/mypet
$ ^C

babyc@Note-Keli MINGW64 /c/mypet
$ ls

babyc@Note-Keli MINGW64 /c/mypet
$ cd /c

babyc@Note-Keli MINGW64 /c
$ dir
$Recycle.Bin              mypet                  Python38
$SysReset                 OneDriveTemp           Recovery
Arquivos\ de\ Programas   pagefile.sys           swapfile.sys
Documents\ and\ Settings  PerfLogs               System\ Volume\ Information
DRIVERS                   Program\ Files         Users
hiberfil.sys              Program\ Files\ (x86)  Windows
Intel                     ProgramData
JS                        Python27

babyc@Note-Keli MINGW64 /c
$ cd documents
bash: cd: documents: No such file or directory

babyc@Note-Keli MINGW64 /c
$ cd /js
bash: cd: /js: No such file or directory

babyc@Note-Keli MINGW64 /c
$ cd js

babyc@Note-Keli MINGW64 /c/js
$ dir
myPet  nodeumbler  package-lock.json  Teste1  Teste2  Teste3  teste4

babyc@Note-Keli MINGW64 /c/js
$ cd /c

babyc@Note-Keli MINGW64 /c
$ mkdir docs

babyc@Note-Keli MINGW64 /c
$ cd docs

babyc@Note-Keli MINGW64 /c/docs
$ cd /c

babyc@Note-Keli MINGW64 /c
$ cd /docs
bash: cd: /docs: No such file or directory

babyc@Note-Keli MINGW64 /c
$ cd c/docs
bash: cd: c/docs: No such file or directory

babyc@Note-Keli MINGW64 /c
$ cd /c/docs

babyc@Note-Keli MINGW64 /c/docs
$ mkdir mypet

babyc@Note-Keli MINGW64 /c/docs
$ cd /mypet
bash: cd: /mypet: No such file or directory

babyc@Note-Keli MINGW64 /c/docs
$ cd /c/docs/mypet

babyc@Note-Keli MINGW64 /c/docs/mypet
$ git init
Initialized empty Git repository in C:/docs/mypet/.git/

babyc@Note-Keli MINGW64 /c/docs/mypet (master)
$ echo "# mypets" >> README.md

babyc@Note-Keli MINGW64 /c/docs/mypet (master)
$ git add README.md
warning: LF will be replaced by CRLF in README.md.
The file will have its original line endings in your working directory

babyc@Note-Keli MINGW64 /c/docs/mypet (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md


babyc@Note-Keli MINGW64 /c/docs/mypet (master)
$ git commit -m "first commit"
[master (root-commit) bb12fd6] first commit
 1 file changed, 1 insertion(+)
 create mode 100644 README.md

babyc@Note-Keli MINGW64 /c/docs/mypet (master)
$ git remote -v

babyc@Note-Keli MINGW64 /c/docs/mypet (master)
$ git remote add origin git@github.com:brunomacobeba/mypets.git

babyc@Note-Keli MINGW64 /c/docs/mypet (master)
$ git remote -v
origin  git@github.com:brunomacobeba/mypets.git (fetch)
origin  git@github.com:brunomacobeba/mypets.git (push)

babyc@Note-Keli MINGW64 /c/docs/mypet (master)
$ git status
On branch master
nothing to commit, working tree clean

babyc@Note-Keli MINGW64 /c/docs/mypet (master)
$ git push --set-upstream origin master
Warning: Permanently added the RSA host key for IP address '18.228.67.229' to the list of known hosts.
git@github.com: Permission denied (publickey).
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

babyc@Note-Keli MINGW64 /c/docs/mypet (master)
$ git push --set-upstream origin master
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 222 bytes | 222.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To github.com:brunomacobeba/mypets.git
 * [new branch]      master -> master
Branch 'master' set up to track remote branch 'master' from 'origin'.

babyc@Note-Keli MINGW64 /c/docs/mypet (master)
$
