---
---

## Create a pull request

You’ve been working on feature branch for a while and it’s ready to be merged with the main branch. Most likely, you’d want to first share your work with your peers to get their feedback before merging it into main branch. That’s what pull requests are for.

1. Create a pull request in the GitHub website by loggin in and going to: **Project page -> Pull request tab -> New pull request**
![]({% include asset.html path="images/new-pull-request.png" %})
2. Chose the branch you would like to merge into main and click **Create pull requet**
![]({% include asset.html path="images/pull-merge-branch.png" %})
3. Provide a tile and brielfy describe the changes
4. Click **Create pull request**
![]({% include asset.html path="images/create-pull-request.png" %})
5. Once your changes are approved you can merge them by clicking on **Merge pull request** or by running `git merge` and `git push` from the command line
![]({% include asset.html path="images/merge-pull.png" %})
```
userName@juplab00:~/jupyter/jupyter-lab-lesson$ git merge branch_name
userName@juplab00:~/jupyter/jupyter-lab-lesson$ git push
```

GitHub pull request are fantastic for peer review as they let you see changes side-by-side, write comment to seek clarification or provide feedback, and finally merge the changes once approved.

To revert back to a previous commit:
```
git checkout -b old-state
```
![]({% include asset.html path="images/git-revert.png" %})

When you are ready to commit your changes, do the usual `git add`, `git commit`, `git push` 


