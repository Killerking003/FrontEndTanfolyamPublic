# FrontEndTanfolyamPublic

git parancsok, létrehozás:

git status
fatal: not a git repository (or any of the parent directories): .git

mtomi@DESKTOP-ULOUNMO MINGW64 /f/Tanfolyam/Code
$ git init .
Initialized empty Git repository in F:/Tanfolyam/Code/.git/

mtomi@DESKTOP-ULOUNMO MINGW64 /f/Tanfolyam/Code (master)
$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        index.html
        src/

nothing added to commit but untracked files present (use "git add" to track)

mtomi@DESKTOP-ULOUNMO MINGW64 /f/Tanfolyam/Code (master)
$ git add index.html
warning: in the working copy of 'index.html', LF will be replaced by CRLF the next time Git touches it

mtomi@DESKTOP-ULOUNMO MINGW64 /f/Tanfolyam/Code (master)
$ git add .

mtomi@DESKTOP-ULOUNMO MINGW64 /f/Tanfolyam/Code (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   index.html
        new file:   src/assets/html.png


mtomi@DESKTOP-ULOUNMO MINGW64 /f/Tanfolyam/Code (master)
$ git commit -m "Initial commit"
[master (root-commit) 1661623] Initial commit
 2 files changed, 121 insertions(+)
 create mode 100644 index.html
 create mode 100644 src/assets/html.png

mtomi@DESKTOP-ULOUNMO MINGW64 /f/Tanfolyam/Code (master)
$ git log --stat
commit 1661623fe1540ec6a55f801d3ee4711038e60193 (HEAD -> master)


    Initial commit

 index.html          | 121 ++++++++++++++++++++++++++++++++++++++++++++++++++++
 src/assets/html.png | Bin 0 -> 19761 bytes
 2 files changed, 121 insertions(+)

mtomi@DESKTOP-ULOUNMO MINGW64 /f/Tanfolyam/Code (master)
$ git remote add origin https://github.com/Killerking003/FrontEndTanfolyamPublic.git

mtomi@DESKTOP-ULOUNMO MINGW64 /f/Tanfolyam/Code (master)
$ git push origin master:master

Nem kezelt kivétel: System.ComponentModel.Win32Exception: Érvénytelen ablakleíró
   a következő helyen: MS.Win32.ManagedWndProcTracker.HookUpDefWindowProc(IntPtr hwnd)
   a következő helyen: MS.Win32.ManagedWndProcTracker.OnAppDomainProcessExit()
   a következő helyen: MS.Internal.ShutDownListener.HandleShutDown(Object sender, EventArgs e)
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 8 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 21.70 KiB | 10.85 MiB/s, done.
Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/Killerking003/FrontEndTanfolyamPublic.git
 * [new branch]      master -> master

mtomi@DESKTOP-ULOUNMO MINGW64 /f/Tanfolyam/Code (master)
$ git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   index.html

no changes added to commit (use "git add" and/or "git commit -a")

mtomi@DESKTOP-ULOUNMO MINGW64 /f/Tanfolyam/Code (master)
$ git add
Nothing specified, nothing added.
hint: Maybe you wanted to say 'git add .'?
hint: Turn this message off by running
hint: "git config advice.addEmptyPathspec false"

mtomi@DESKTOP-ULOUNMO MINGW64 /f/Tanfolyam/Code (master)
$ git st
git: 'st' is not a git command. See 'git --help'.

The most similar commands are
        status
        reset
        stage
        stash
        svn

mtomi@DESKTOP-ULOUNMO MINGW64 /f/Tanfolyam/Code (master)
$ git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   index.html

no changes added to commit (use "git add" and/or "git commit -a")

mtomi@DESKTOP-ULOUNMO MINGW64 /f/Tanfolyam/Code (master)
$ git commit -m "footer kiegeszites"
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   index.html

no changes added to commit (use "git add" and/or "git commit -a")

mtomi@DESKTOP-ULOUNMO MINGW64 /f/Tanfolyam/Code (master)
$ git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   index.html

no changes added to commit (use "git add" and/or "git commit -a")


mtomi@DESKTOP-ULOUNMO MINGW64 /f/Tanfolyam/Code (master)
$ git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   index.html

no changes added to commit (use "git add" and/or "git commit -a")


mtomi@DESKTOP-ULOUNMO MINGW64 /f/Tanfolyam/Code (master)
$ git add index.html
warning: in the working copy of 'index.html', LF will be replaced by CRLF the next time Git touches it

mtomi@DESKTOP-ULOUNMO MINGW64 /f/Tanfolyam/Code (master)
$ git commit -m "footer kiegeszites"
[master 1289ac5] footer kiegeszites
 1 file changed, 3 insertions(+), 3 deletions(-)

mtomi@DESKTOP-ULOUNMO MINGW64 /f/Tanfolyam/Code (master)
$ git push origin master:master
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 341 bytes | 341.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/Killerking003/FrontEndTanfolyamPublic.git
   1661623..1289ac5  master -> master

mtomi@DESKTOP-ULOUNMO MINGW64 /f/Tanfolyam/Code (master)
