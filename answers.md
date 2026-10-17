# Part 1

## 1
**file explorer is UI base that let us navigate and manage files through clicks and keys press but a terminal is a command base, which let us do that with commands.**
**ls -la, mkdir project, cd project**
**cd changes directory to the specific folder you mention in commands e.g: cd "C/users/downloads/assignment" and cd~ takes to the user home directory**
## 2
**version control help us to see track and review the changes. it help us in minimizing the errors that can be caused by overlaping when multiple peopple working on the same project files**
**Git is a version control tool and github is a online hosting site. Yes Git can work without github (locally).it just need to connect with the other cloud servers storage providers if you are using cloud storage.**
**pull requests/merge requests
automating tasks eg: conflicts resolve
tracking and project management**
**a repo is a project file containing its data, a remote repo is that resides remotely on a cloud server such as github and others can also access it while local one is in your own computer or personal server**
## 2
**its a reference that points towards the current branch. when we switch branches head moves to he selected branch**
**A .gitignore is a file which tells git to not track it for version control. git will ignore this file.**

# Part 2
## explain: Why did we commit A+B separately from C? When would you want to split commits this way?
**instead of making up a pile of commits together that look messy, we make it look neater when commits it separately.**
**It can be that file A and B may have the same kind of content and related wile C is different file. Also B and are can be completed while C is partially done and need further changes.**

## What would happen if you made a local commit first WITHOUT pulling? What command helps you check?
**there will be conflicts as someone might have worked and made changes on that file already that you have commited, so pulling it and checking the git log commands is recommended to first check the changes/logs or we can see the if we are behind or ahead by git status command.**

# Part 3

##  In answers.md : Did this merge create a merge commit or was it a fast-forward? How can you tell?
**it was a fast forward as it was mention in the output.**
## Why did this conflict happen? (Reference the rule: same file, same line)
**conflict happened because changes were done on the same lines of the file by both branches main and feature/update-motto**
## Would there have been a conflict if the two branches edited different lines of team.txt ?
**No, as the changes woud have been to the different lines, git can handle this**
## Would there have been a conflict if one branch edited team.txt and the other edited about.md ?
**No, as the both files are different**
# Part 4
## What is the purpose of a pull request? Why not just merge directly?
**it allows changes to be reviewed and test before merging. doing it directly skip this part so more prone to errors.**

## Name two things a reviewer should check in a pull request.
**check if the changes are accurate and needed. run the test and see results to evaluate the functionality.**

## What is the difference between a merge commit and a fast-forward merge?
**merge commit preserves 2 different branches separate history by creating a new commit.FFM creates a linear history with no new merge commit.**

# Part 5

## A
**NO overlaping so there will be no conflict**

## B
**No.Both editied 2 different files**

## C
**yes. same file, same line so there will be conflict. it will show markers for Dev A as <<<< changes ===== and for Dev B as <<<< changes**

## D
**open the file, find the conflicts, choose the changes to keep, merge then git add index.html, git commit -m "conflicts resolve, kept this change"**

## E
**Yes, it keeps your local branch updated with the changes. if you skip it then i can create conflicts. though it would be better if you check status first git status to see if your are behind and then git fetch to see info about commits without merging them**
