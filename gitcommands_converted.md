# Git Commands and Outputs

A collection of Git commands and their respective outputs.

```
$ mkdir DevOps
$ cd DevOps
$ git init
Initialized empty Git repository in /home/bard/DevOps/.git/
$ touch index.txt
$ git add .
$ git commit -m "initial commit"
[master (root-commit) f0a048d] initial commit
1 file changed, 0 insertions(+), 0 deletions(-)
create mode 100644 index.txt
$ git checkout -b sadiq-new-branch
Switched to a new branch 'sadiq-new-branch'
$ git branch
* sadiq-new-branch
master
$ git checkout sadiq-new-branch
$ git merge B
fatal: The branch 'B' does not exist.
$ git branch -d sadiq-new-branch
Deleted branch sadiq-new-branch (was 6a55220).
$ git remote add origin https://github.com/kennyanju/gitlessonsdareio
$ git push origin sadiq-new-branch
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 8 threads: 100% (2/2), done.
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 247 bytes, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/kennyanju/gitlessonsdareio
* [new branch] sadiq-new-branch -> sadiq-new-branch
$ git clone https://github.com/kennyanju/gitlessonsdareio
Cloning into 'gitlessonsdareio'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (3/3), 247 bytes, done.
Resolving deltas: 100% (0/0), done.
Checking connectivity... done.
```
