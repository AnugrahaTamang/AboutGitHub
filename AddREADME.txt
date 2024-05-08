GIT : version control system is a tools that helps to track changes in code. GIT is a version control system. It is popular free & open source fast & scalable tool.
How I can used github & git ? what is the purpose of it?
-Track the history
-collborate
Imp Note: Research about the git and github....|| Difference ||
-GIT (inside system) 
-GITHUB(inside github web)

THis is about the Git and GitHub command....
<br>
1. configuring Git
-git config --global user.name "GitHubName"
-git config --global user.email "github email"
-git config --list

2. Clone and Status
- git clone <- repository http link->
-git Status 
-cd (change directory)
-ls (list file)

About File...
1. Untracked (new files that git doesn't yet track)
2. modified (change)
3. staged(file is ready to be commited)
4. unmodified(unchanged)

3. Add & commited
-git add <-filename->
or
-git add .

-git commit -m "update message"

4. Push command
push -upload local repo content to remote repo 
-git push origin main


5. Init command(यसको मतलब हामिले मेसिनमा लेखेको कोड अथवा प्रोजेक्ट GitHub मा upload गर्नु हो)
-init(used to create new git repo)
-git init
-git remote add origin <-link->
-git remote -v (to verify remote)
-git branch
-git branch -m main (to rename branch)
-git push origin main || git push -u origin main 

Default folder बाट बहिर निस्कनलाई cd..
mkdir <-folder name-> (folder create गर्नलाई)

6. Git branches
-git branch (to check the branch)
-git  branch -m main (to rename the branch)
-git checkout <-branchname-> (to navigate)
-git checkout -b <-new branch name -> (to create new branch)
-git branch -d <-branch name ->

7. Merging code
way 1.
-git diff <branchname-> (to compare commits,branches,files and more)
-git merge <-branch name-> (to merge 2 branches)

way 2.
-create a PR 
-pull command
-git push origin main

8. Undoing changes
case 1: staged changes 
-git reset <-filename->
-git reset

case 2: commited changes (for one commit)
-git reset HEAD-1

case 3 : commited changes (for many commits)
-git reset <-commit hase->
-git reset --hard 



