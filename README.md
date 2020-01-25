3-way-merge

Step 8:
$ git log --oneline --graph --all
* afe729e (HEAD -> master) README.md
| * b5beb03 (greeting) greeting.txt
|/
* c961c6c Add content to greeting.txt
* d2c775f Add file greeting.txt

basic-commits

Step 2:
$ git log
fatal: your current branch 'master' does not have any commits yet

Step 4:
$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        test.txt

nothing added to commit but untracked files present (use "git add" to track)

Step 6:
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   test.txt

Step 8:
$ git status
On branch master
nothing to commit, working tree clean

Step 10:
$ git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   test.txt

no changes added to commit (use "git add" and/or "git commit -a")

Step 12:
$ git status
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   test.txt

Step 15:
$ git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   test.txt

$ git log
commit 20496edb7f07e71789b7fbd5dde3860e6c30bb5c (HEAD -> master)
Author: DBelen <dbelen@uci.edu>
Date:   Fri Jan 24 17:14:21 2020 -0800

    modified test.txt

commit efca4e75ce0db0290c1903825543a31936dc709f
Author: DBelen <dbelen@uci.edu>
Date:   Fri Jan 24 17:11:06 2020 -0800

    adding test.txt
