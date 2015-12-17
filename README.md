# Learning-Git

My first attempt at Git Version Control

Learning the basics of Git. Committing and pushing. Previous line committed but not pushed.
Will now push the changes.

**confusion of staging before committing. Required me to add the file again after the first commit to make the second commit. will try again.

Results:
Only commited changes are pushed. The above statement was not committed before the first push so the changes were not reflected online. And you need to stage (add the file) before committing.  

*changed through new branch

Results:
Creating a branch makes changes to local files but allows you to create separate branch online where you may or may not merge with the master branch. You commit normally in new branch and then push the changes. Now push can behave in two different ways:

Matchng (set using command git config --global push.config matching) : Git will push the changes to the branch with the same name in online repostory and not the master branch
Simple (default set using push.config simple): Gitwill push changes to the branch wfrom which you have pulled or cloned( may or may not be master branch)

Branching allows you to work on your code and make changes but you may dicard the changes if they do not work by not pushing the changes to master branch. Thus it is like making a copy of your code and then working on it.

i will be pushing this result using simple and hence this result should not be available in the test-branch
