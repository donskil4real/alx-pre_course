git init
git add .
git commit -m "first commit"
git push
git pull
git checkout -b "branch name"
git status

C:\Users\CHIDI DAVID>cd Desktop

C:\Users\CHIDI DAVID\Desktop>cd alx-pre_course

C:\Users\CHIDI DAVID\Desktop\alx-pre_course>git add .

C:\Users\CHIDI DAVID\Desktop\alx-pre_course>git commit -m "first commit"
[main e1bd150] first commit
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 GIT TASK.c

C:\Users\CHIDI DAVID\Desktop\alx-pre_course>git push
Enumerating objects: 27, done.
Counting objects: 100% (27/27), done.
Delta compression using up to 4 threads
Compressing objects: 100% (18/18), done.
Writing objects: 100% (27/27), 2.18 KiB | 124.00 KiB/s, done.
Total 27 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), done.
To https://github.com/donskil4real/alx-pre_course.git
 * [new branch]      main -> main

C:\Users\CHIDI DAVID\Desktop\alx-pre_course>git add .

C:\Users\CHIDI DAVID\Desktop\alx-pre_course>git commit -m "first commit"
[main b761074] first commit
 7 files changed, 13 deletions(-)
 delete mode 100644 0x01-git/READ.md
 delete mode 100644 0x01-git/bash/alx
 delete mode 100644 0x01-git/bash/school
 delete mode 100644 0x01-git/c/c_is_fun.c
 delete mode 100644 GIT TASK.c
 delete mode 100644 README.MD
 delete mode 100644 up_to_date

C:\Users\CHIDI DAVID\Desktop\alx-pre_course>git push
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 4 threads
Compressing objects: 100% (1/1), done.
Writing objects: 100% (2/2), 230 bytes | 76.00 KiB/s, done.
Total 2 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/donskil4real/alx-pre_course.git
   e1bd150..b761074  main -> main

C:\Users\CHIDI DAVID\Desktop\alx-pre_course>git add .

C:\Users\CHIDI DAVID\Desktop\alx-pre_course>git commit -m "first commit"
[main e4fe920] first commit
 7 files changed, 13 insertions(+)
 create mode 100644 0x01-git/READ.md
 create mode 100644 0x01-git/bash/alx
 create mode 100644 0x01-git/bash/school
 create mode 100644 0x01-git/c/c_is_fun.c
 create mode 100644 GIT TASK.c
 create mode 100644 README.MD
 create mode 100644 up_to_date

C:\Users\CHIDI DAVID\Desktop\alx-pre_course>git push
Enumerating objects: 30, done.
Counting objects: 100% (30/30), done.
Delta compression using up to 4 threads
Compressing objects: 100% (20/20), done.
Writing objects: 100% (30/30), 2.47 KiB | 76.00 KiB/s, done.
Total 30 (delta 3), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (3/3), done.
To https://github.com/donskil4real/alx-pre_course.git
 * [new branch]      main -> main

C:\Users\CHIDI DAVID\Desktop\alx-pre_course>git add .

C:\Users\CHIDI DAVID\Desktop\alx-pre_course>git commit -m "first commit"
[main 07c744a] first commit
 1 file changed, 0 insertions(+), 0 deletions(-)
 rename 0x01-git/{READ.md => README.md} (100%)

C:\Users\CHIDI DAVID\Desktop\alx-pre_course>git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 476 bytes | 95.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/donskil4real/alx-pre_course.git
   e4fe920..07c744a  main -> main

C:\Users\CHIDI DAVID\Desktop\alx-pre_course>git add .

C:\Users\CHIDI DAVID\Desktop\alx-pre_course>git commit -m "Starting to code today, so cool"
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

C:\Users\CHIDI DAVID\Desktop\alx-pre_course>git push
Everything up-to-date

C:\Users\CHIDI DAVID\Desktop\alx-pre_course>git add .

C:\Users\CHIDI DAVID\Desktop\alx-pre_course>git commit -m "Starting to code today, so cool"
[main dfba756] Starting to code today, so cool
 1 file changed, 1 insertion(+), 1 deletion(-)

C:\Users\CHIDI DAVID\Desktop\alx-pre_course>git push
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (4/4), 522 bytes | 104.00 KiB/s, done.
Total 4 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/donskil4real/alx-pre_course.git
   07c744a..dfba756  main -> main

C:\Users\CHIDI DAVID\Desktop\alx-pre_course>git checkout update_script
error: Your local changes to the following files would be overwritten by checkout:
        0x01-git/bash/alx
        0x01-git/bash/school
Please commit your changes or stash them before you switch branches.
error: The following untracked working tree files would be overwritten by checkout:
        0x01-git/bash/98
Please move or remove them before you switch branches.
Aborting

C:\Users\CHIDI DAVID\Desktop\alx-pre_course>git checkout update_script
error: Your local changes to the following files would be overwritten by checkout:
        0x01-git/bash/alx
        0x01-git/bash/school
Please commit your changes or stash them before you switch branches.
Aborting

C:\Users\CHIDI DAVID\Desktop\alx-pre_course>git checkout update_script
Switched to branch 'update_script'

C:\Users\CHIDI DAVID\Desktop\alx-pre_course>git add .

C:\Users\CHIDI DAVID\Desktop\alx-pre_course>git commit -m "My personal work"
[update_script e4bee4d] My personal work
 2 files changed, 2 insertions(+), 1 deletion(-)
 create mode 100644 0x01-git/README.md

C:\Users\CHIDI DAVID\Desktop\alx-pre_course>git push
fatal: The current branch update_script has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin update_script


C:\Users\CHIDI DAVID\Desktop\alx-pre_course>git push origin update_script
To https://github.com/donskil4real/alx-pre_course.git
 ! [rejected]        update_script -> update_script (non-fast-forward)
error: failed to push some refs to 'https://github.com/donskil4real/alx-pre_course.git'
hint: Updates were rejected because the tip of your current branch is behind
hint: its remote counterpart. Integrate the remote changes (e.g.
hint: 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

C:\Users\CHIDI DAVID\Desktop\alx-pre_course>git push update_script
fatal: 'update_script' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

C:\Users\CHIDI DAVID\Desktop\alx-pre_course>git push --set-upstream origin update_script
To https://github.com/donskil4real/alx-pre_course.git
 ! [rejected]        update_script -> update_script (non-fast-forward)
error: failed to push some refs to 'https://github.com/donskil4real/alx-pre_course.git'
hint: Updates were rejected because the tip of your current branch is behind
hint: its remote counterpart. Integrate the remote changes (e.g.
hint: 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

C:\Users\CHIDI DAVID\Desktop\alx-pre_course>git push
fatal: The current branch update_script has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin update_script


C:\Users\CHIDI DAVID\Desktop\alx-pre_course>git push update_script
fatal: 'update_script' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

C:\Users\CHIDI DAVID\Desktop\alx-pre_course>git branch
  main
* update_script

C:\Users\CHIDI DAVID\Desktop\alx-pre_course>git checkout update_script
Already on 'update_script'

C:\Users\CHIDI DAVID\Desktop\alx-pre_course>git push origin
fatal: The current branch update_script has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin update_script


C:\Users\CHIDI DAVID\Desktop\alx-pre_course>git push origin update_script
To https://github.com/donskil4real/alx-pre_course.git
 ! [rejected]        update_script -> update_script (non-fast-forward)
error: failed to push some refs to 'https://github.com/donskil4real/alx-pre_course.git'
hint: Updates were rejected because the tip of your current branch is behind
hint: its remote counterpart. Integrate the remote changes (e.g.
hint: 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

C:\Users\CHIDI DAVID\Desktop\alx-pre_course>git pull
From https://github.com/donskil4real/alx-pre_course
 + 89d45c5...dfba756 update_script -> origin/update_script  (forced update)
There is no tracking information for the current branch.
Please specify which branch you want to merge with.
See git-pull(1) for details.

    git pull <remote> <branch>

If you wish to set tracking information for this branch you can do so with:

    git branch --set-upstream-to=origin/<branch> update_script


C:\Users\CHIDI DAVID\Desktop\alx-pre_course>git push --force
fatal: The current branch update_script has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin update_script


C:\Users\CHIDI DAVID\Desktop\alx-pre_course>git push origin update_script
To https://github.com/donskil4real/alx-pre_course.git
 ! [rejected]        update_script -> update_script (non-fast-forward)
error: failed to push some refs to 'https://github.com/donskil4real/alx-pre_course.git'
hint: Updates were rejected because the tip of your current branch is behind
hint: its remote counterpart. Integrate the remote changes (e.g.
hint: 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

C:\Users\CHIDI DAVID\Desktop\alx-pre_course>git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

C:\Users\CHIDI DAVID\Desktop\alx-pre_course>git pull
Already up to date.

C:\Users\CHIDI DAVID\Desktop\alx-pre_course>git push
Everything up-to-date

C:\Users\CHIDI DAVID\Desktop\alx-pre_course>git checkout update_script
Switched to branch 'update_script'

C:\Users\CHIDI DAVID\Desktop\alx-pre_course>git add .

C:\Users\CHIDI DAVID\Desktop\alx-pre_course>git commit -m "My personal work"
On branch update_script
nothing to commit, working tree clean

C:\Users\CHIDI DAVID\Desktop\alx-pre_course>git push
fatal: The current branch update_script has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin update_script


C:\Users\CHIDI DAVID\Desktop\alx-pre_course>