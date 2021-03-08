---
---

## Command-line interface

If you prefer to use the command line for using git, here is how you can clone your remote repository, stage, commit, and push your local changes. 

### Create a new folder

1. Log in to the SESYNC's [Jupyter Server](https://jupyter.sesync.org/)
2. Open the Terminal: **File -> New Launcher -> Terminal**
3. Make a new project folder
```
userName@juplab00:~$ mkdir new-project-name
```

### Clone a repository

1. Navigate to your project folder
2. Clone your remote repository
3. If prompted, enter your GitHub username and password. We suggest you use SSH for the URL to avoid having to repeatedly enter your log-in credentials. If you’re not sure if you’ve set up SSH authentication, see these [GitHub instructions](https://docs.github.com/en/github/authenticating-to-github/connecting-to-github-with-ssh)
4. Navigate into the newly cloned repository by using the `cd` command

Let's clone your remote repository by running the following command using the remote repository's ulr:
```
git clone https://github.com/githubUserName/my-repo-name.git

ls # to see name of the cloned repository
cd my-cloned-repo # navigate into the clones repository
```

Congrats! You have successfully linked your remote and local repositories. 
Next we will go over how to add your notebooks and files to you newly created repository. 

### Push Notebooks to GitHub
Your repository is empty right now, let's push a notebook to it. 
1. In your project folder create a new notebook, go to: **File -> New Launcher -> Python3**
2. Name the Python notebook
3. Do your work in the notebook or script and save it
===
![]({% include asset.html path="images/save-notebook.png" %}){:.nobox}
{:.captioned}

4. Go to terminal and check the status of your repository
```
git status
```
Your file will be listed under untracked files:
===
![]({% include asset.html path="images/git-untracked.png" %}){:.nobox}
{:.captioned}

5. Stage your changes with `git add <filename>`
```
git add main.py
```
===
![]({% include asset.html path="images/git-add.png" %}){:.nobox}
{:.captioned}

You can check which files are being tracked with `git status`.

You can see that `main.ipynb` is being tracked. Let's commit the changes.

6. Commit your changes with `git commit -m "Commit Message Here"`
```
git commit -m "Descriptive statitics."
```
===
![]({% include asset.html path="images/git-commit.png" %}){:.nobox}
{:.captioned}

`commit` creates a checkpoint that you can revert back to at any time.

7. Pull down the current version of the repository from GitHub
```
git pull origin main
``` 

8. Push your changes to the project's Github repository
```
git push origin main
```
===
![]({% include asset.html path="images/git-push.png" %}){:.nobox}
{:.captioned}

You can visit the project's GitHub repository page and see your commits.
===
![]({% include asset.html path="images/git-push-2.png" %}){:.nobox}
{:.captioned}





