---
---

## Develop in a branch

Let’s say you are working on a large project spanning multiple days but you want to periodically push work in progress commits. The way you do that is by creating a feature branch. Each repository has a default branch called "main" that stores most up-to-date versions of completed work. Each member of your team can create their own feature branches to store their work in progress commits. When their work in a feature branch is ready to be shared they can create a pull request for peer review and subsequently merge the feature branch into main. Let’s unpack that with concrete steps. 

1. In the terminal, create a new branch using the `git checkout` command.
```
git checkout -b new_branch_name
```
![]({% include asset.html path="images/new-branch.png" %})
2. Create and/or edit some notebooks and files. Save the changes to current notebooks.
![]({% include asset.html path="images/branch-changes.png" %})
3. When you are ready to commit your work in progress, do the usual `git add`, `git commit`, `git push` show in the previous section. Since the branch does not exist on Github yet, you will need to push the branch first.
```
# push branch
git push --set-upstream origin new_branch_name
# now add, commit, and push changes
userName@juplab00:~/jupyter/jupyter-lab-lesson$ git add .
userName@juplab00:~/jupyter/jupyter-lab-lesson$ git commit -m "added fox."
userName@juplab00:~/jupyter/jupyter-lab-lesson$ git push
```

Your branch local  and remote branches are now up to date and you can now submit a pull request.

