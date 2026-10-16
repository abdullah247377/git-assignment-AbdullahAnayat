## explain: Why did we commit A+B separately from C? When would you want to split commits this way?
## Answewr: **instead of making up a pile of commits together that look messy, we make it look neater when commits it separately.**
**It can be that file A and B may have the same kind of content and related wile C is different file. Also B and are can be completed while C is partially done and need further changes.**
## What would happen if you made a local commit first WITHOUT pulling? What command helps you check?
## Answer: **there will be conflicts as someone might have worked and made changes on that file already that you have commited, so pulling it and checking the git log commands is recommended to first check the changes/logs or we can see the if we are behind or ahead by git status command.**
##  In answers.md : Did this merge create a merge commit or was it a fast-forward? How can you tell?
## Answer: **it was a fast forward as it was mention in the output.**
