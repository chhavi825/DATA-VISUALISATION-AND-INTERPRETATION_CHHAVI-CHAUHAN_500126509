Last login: Sun Aug 17 19:00:49 on ttys000
(base) chhavi@Chhavis-MacBook-Air ~ % cd /Users/chhavi/Documents/DATA-VISUALISATION-AND-INTERPRETATION_CHHAVI-CHAUHAN_500126509

(base) chhavi@Chhavis-MacBook-Air DATA-VISUALISATION-AND-INTERPRETATION_CHHAVI-CHAUHAN_500126509 % ls -a

.				EMAIL SPAM DETECTION
..				IRIS FLOWER CLASSIFICATION
.DS_Store			MNIST
.git				kaggle
Cars93
(base) chhavi@Chhavis-MacBook-Air DATA-VISUALISATION-AND-INTERPRETATION_CHHAVI-CHAUHAN_500126509 % git remote add origin https://github.com/chhavi825/DATA-VISUALISATION-AND-INTERPRETATION_CHHAVI-CHAUHAN_500126509.git

error: remote origin already exists.
(base) chhavi@Chhavis-MacBook-Air DATA-VISUALISATION-AND-INTERPRETATION_CHHAVI-CHAUHAN_500126509 % git remote -v

origin	https://github.com/chhavi825/DATA-VISUALISATION-AND-INTERPRETATION_CHHAVI-CHAUHAN_500126509.git (fetch)
origin	https://github.com/chhavi825/DATA-VISUALISATION-AND-INTERPRETATION_CHHAVI-CHAUHAN_500126509.git (push)
(base) chhavi@Chhavis-MacBook-Air DATA-VISUALISATION-AND-INTERPRETATION_CHHAVI-CHAUHAN_500126509 % git add .

(base) chhavi@Chhavis-MacBook-Air DATA-VISUALISATION-AND-INTERPRETATION_CHHAVI-CHAUHAN_500126509 % git commit -m "Initial commit: Add MNIST and main folder files"

On branch main
Your branch and 'origin/main' have diverged,
and have 1 and 2 different commits each, respectively.
  (use "git pull" to merge the remote branch into yours)

nothing to commit, working tree clean
(base) chhavi@Chhavis-MacBook-Air DATA-VISUALISATION-AND-INTERPRETATION_CHHAVI-CHAUHAN_500126509 % git pull origin main --allow-unrelated-histories

From https://github.com/chhavi825/DATA-VISUALISATION-AND-INTERPRETATION_CHHAVI-CHAUHAN_500126509
 * branch            main       -> FETCH_HEAD
hint: You have divergent branches and need to specify how to reconcile them.
hint: You can do so by running one of the following commands sometime before
hint: your next pull:
hint: 
hint:   git config pull.rebase false  # merge
hint:   git config pull.rebase true   # rebase
hint:   git config pull.ff only       # fast-forward only
hint: 
hint: You can replace "git config" with "git config --global" to set a default
hint: preference for all repositories. You can also pass --rebase, --no-rebase,
hint: or --ff-only on the command line to override the configured default per
hint: invocation.
fatal: Need to specify how to reconcile divergent branches.
(base) chhavi@Chhavis-MacBook-Air DATA-VISUALISATION-AND-INTERPRETATION_CHHAVI-CHAUHAN_500126509 % git push origin main

To https://github.com/chhavi825/DATA-VISUALISATION-AND-INTERPRETATION_CHHAVI-CHAUHAN_500126509.git
 ! [rejected]        main -> main (non-fast-forward)
error: failed to push some refs to 'https://github.com/chhavi825/DATA-VISUALISATION-AND-INTERPRETATION_CHHAVI-CHAUHAN_500126509.git'
hint: Updates were rejected because the tip of your current branch is behind
hint: its remote counterpart. Integrate the remote changes (e.g.
hint: 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
(base) chhavi@Chhavis-MacBook-Air DATA-VISUALISATION-AND-INTERPRETATION_CHHAVI-CHAUHAN_500126509 % git pull origin main --allow-unrelated-histories --no-rebase

From https://github.com/chhavi825/DATA-VISUALISATION-AND-INTERPRETATION_CHHAVI-CHAUHAN_500126509
 * branch            main       -> FETCH_HEAD
CONFLICT (modify/delete): MNIST/DVI_04.ipynb deleted in ddbfd9ab1f6d3d91b9f0d19da2a269c35f97d1e9 and modified in HEAD.  Version HEAD of MNIST/DVI_04.ipynb left in tree.
Automatic merge failed; fix conflicts and then commit the result.
(base) chhavi@Chhavis-MacBook-Air DATA-VISUALISATION-AND-INTERPRETATION_CHHAVI-CHAUHAN_500126509 % git push origin main

To https://github.com/chhavi825/DATA-VISUALISATION-AND-INTERPRETATION_CHHAVI-CHAUHAN_500126509.git
 ! [rejected]        main -> main (non-fast-forward)
error: failed to push some refs to 'https://github.com/chhavi825/DATA-VISUALISATION-AND-INTERPRETATION_CHHAVI-CHAUHAN_500126509.git'
hint: Updates were rejected because the tip of your current branch is behind
hint: its remote counterpart. Integrate the remote changes (e.g.
hint: 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
(base) chhavi@Chhavis-MacBook-Air DATA-VISUALISATION-AND-INTERPRETATION_CHHAVI-CHAUHAN_500126509 % git push origin main --force

Enumerating objects: 8, done.
Counting objects: 100% (8/8), done.
Delta compression using up to 10 threads
Compressing objects: 100% (5/5), done.
Writing objects: 100% (5/5), 370.08 KiB | 23.13 MiB/s, done.
Total 5 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/chhavi825/DATA-VISUALISATION-AND-INTERPRETATION_CHHAVI-CHAUHAN_500126509.git
 + ddbfd9a...ed9a756 main -> main (forced update)
(base) chhavi@Chhavis-MacBook-Air DATA-VISUALISATION-AND-INTERPRETATION_CHHAVI-CHAUHAN_500126509 % nano README.md


  UW PICO 5.09                    File: README.md                     Modified  




# DATA-VISUALISATION-AND-INTERPRETATION_CHHAVI-CHAUHAN_500126509

## Overview
This repository contains projects and datasets related to **data visualization $

- `MNIST/` folder: Contains the MNIST dataset for digit recognition tasks.
- Other datasets and notebooks used for data analysis and visualization (if any$

---

## Project Structure






^G Get Help  ^O WriteOut  ^R Read File ^Y Prev Pg   ^K Cut Text  ^C Cur Pos   
^X Exit      ^J Justify   ^W Where is  ^V Next Pg   ^U UnCut Text^T To Spell  
