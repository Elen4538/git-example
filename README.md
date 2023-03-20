# git-example
example of work with Git

each branch I should name as task number

Here I train such commands as (and some marks for me):
-git clone (SSH)
-git pull
-git push
-git commit -m "what I have done today:)"
-git add.
-git log (watch info about commits)




notes:
-git cherry pick :  to choose a commit from one branch and apply it onto another
(This is in contrast with other ways such as merge and rebase which normally 
apply many commits onto another branch. Two steps:
            -Make sure you are on the branch you want to apply the commit to.
            -Execute : git cherry-pick <commit-hash> )


-git rebase: is the process of moving or combining a sequence of commits to 
a new base commit. Rebasing is most useful and easily visualized in 
the context of a feature branching workflow.