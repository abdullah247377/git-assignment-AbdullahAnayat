# Part 2
## explain: Why did we commit A+B separately from C? When would you want to split commits this way?
## Answer:
**instead of making up a pile of commits together that look messy, we make it look neater when commits it separately.**
**It can be that file A and B may have the same kind of content and related wile C is different file. Also B and are can be completed while C is partially done and need further changes.**
## What would happen if you made a local commit first WITHOUT pulling? What command helps you check?
## Answer:
**there will be conflicts as someone might have worked and made changes on that file already that you have commited, so pulling it and checking the git log commands is recommended to first check the changes/logs or we can see the if we are behind or ahead by git status command.**
# Part 3
##  In answers.md : Did this merge create a merge commit or was it a fast-forward? How can you tell?
## Answer:
**it was a fast forward as it was mention in the output.**
## Why did this conflict happen? (Reference the rule: same file, same line)
** **
## Would there have been a conflict if the two branches edited different lines of team.txt ?
** **
## Would there have been a conflict if one branch edited team.txt and the other edited about.md ?
** **
# Part 4
## What is the purpose of a pull request? Why not just merge directly?
## Answer:
**it allows changes to be reviewed and test before merging. doing it directly skip this part so more prone to errors.**
## Name two things a reviewer should check in a pull request.
## Answer:
**check if the changes are accurate and needed. run the test and see results to evaluate the functionality.**
## What is the difference between a merge commit and a fast-forward merge?
**merge commit preserves 2 different branches separate history by creating a new commit.FFM creates a linear history with no new merge commit.**
# part 5
## A
**NO overlaping so there will be no conflict**
## B
**No.Both editied 2 different files**
## C
**yes. same file, same line so there will be conflict. it will show markers for Dev A as <<<< changes ===== and for Dev B as <<<< changes**
## D
**open the file, find the conflicts, choose the changes to keep, merge then git add index.html, git commit -m "conflicts resolve, kept this change" **
## E
**Yes, it keeps your local branch updated with the changes. if you skip it then i can create conflicts. though it would be better if you check status first git status to see if your are behind and then git fetch to see info about commits without merging them**
