---
---

## Point-and-click interface

SESYNC's Jupyter Lab server has the [JupyterLab git extension](https://github.com/jupyterlab/jupyterlab-git#readme) enabled. The extension is a user-friendly add-on for JupyterLab that lets you do basic git actions with a point-and-click interface. Access the extension by simply clicking on the git icon on the left-hand side of your screen in Jupyter Lab (you should see something like the screenshot below).

![]({% include asset.html path="images/git-extension.png" %}){:.nobox}
{:.captioned}

### Create a new folder

1. Click on the **New Folder** and name it
2. Navigate to the new folder 
![]({% include asset.html path="images/ui-new-folder.png" %})

### Create a local git repository
1. Clik the Git tab
2. Click Initialize a Repository
![]({% include asset.html path="images/ui-git-init.png" %})
3. Click yes to confirm and initialize the folder as a git repository

Congrats! You have initialized a new git repository by using the git extension.

Now, it is time to do some work by adding a new notebook. 
1. Go to: **File -> New Launcher -> Python3** and start a new notebook
![]({% include asset.html path="images/ui-new-notebook.png" %})
2. Work, edit, and save your notebook
![]({% include asset.html path="images/ui-workbook-save.png" %})

### Stage, Commit, and Push your work to your git local repository
You are now ready to commit your work.

1. Click the git extension tab on the side panel  
![]({% include asset.html path="images/ui-git-extension.png" %})
2. Track your notebook by clicking on the plus sign next to its name
![]({% include asset.html path="images/ui-git-track.png" %})
You have staged your notebook. You will notice that it is now under the Staged section. 
![]({% include asset.html path="images/ui-git-staged.png" %})
4. Add a title and a brief message description
5. Click Commit
![]({% include asset.html path="images/ui-git-commit.png" %})
6. If prompted enter your name and email. Once the commit is succesfully completed you will see a green message box popup from the bottom right corner. 

Congrats! You have now succesfully completed your first commit!

### Link your local repository to your GitHub repository
1. Under the Git tab click Add Remote Repository
![]({% include asset.html path="images/ui-git-add-remote.png" %})
2. Paste the remote repository's url and click ok
![]({% include asset.html path="images/ui-remote-url.png" %})
3. Go to the Git tab and click Push to Remote
![]({% include asset.html path="images/ui-git-push-remote.png" %})
4. If prompted, enter your username and password for your remote repository and click ok

You wil see a successful push message once the push has been completed.
![]({% include asset.html path="images/ui-git-successful-push.png" %})

You can visit the project's GitHub repository and see your commits. 
![]({% include asset.html path="images/ui-check-commits.png" %})

### Push Notebooks to GitHub
Let's say you have added new changes to your notebook and you would like to commit these changes.

1. Follow the previous instructions to stage, commit and push to your local repository.
2. Push your chnages to your remote repository by clicking on the cloud icon with the up arrow
![]({% include asset.html path="images/ui-commit-changes-remote.png" %})
3. If promted, enter your username and password.

Congrats! You have successfully made changes to your notebook and pushed these changes to the project's local and remote repositories.






