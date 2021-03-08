---
---

## Command-line interface
If you prefer to use the command line for using git, here is how you can clone your remote repository, stage, commit, and push your local changes. 

### Create a new folder
1. Log in to the SESYNC's [Jupyter Server](https://jupyter.sesync.org/)
2. Open the Terminal: **File -> New Launcher -> Terminal**
3. Make a new project folder
```
agarcia@juplab00:~$ mkdir new-project-name
```

### Clone a repository
1. If needed, `cd` to your project folder
2. Clone your remote repository

Let's clone your remote repository by running the following command using the remote repository's ulr:
```
git clone https://github.com/githubUserName/my-repo-name.git
```

3. If prompted, enter your GitHub username and password. We suggest you use SSH for the URL to avoid having to repeatedly enter your log-in credentials. If you’re not sure if you’ve set up SSH authentication, see these [GitHub instructions](https://docs.github.com/en/github/authenticating-to-github/connecting-to-github-with-ssh)
4. Navigate into the newly cloned repository by using the `cd` command
```
ls # to see name of the cloned repository
cd my-cloned-repo
```

Congrats! You have successfully linked your remote and local repositories. 
Next we will go over how to add your notebooks and files to you newly created repository. 


### Push Notebooks to GitHub

