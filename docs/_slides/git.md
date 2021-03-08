---
---

## Setup

### Create a GitHub or GitLab Accout

To sync your local repository to a remote repository, 
you will need to create a remote repo on GitHub or GitLab.
See our [quickstart instructions here](https://cyberhelp.sesync.org/quickstart/creating-a-new-git-project.html).
To create a GiHub account please visit [GitHub](https://github.com).
To create a GitLab account please visit [GitLab](https://about.gitlab.com).

### Setup git

As of October 1, 2020, all new repositories created on GitHub will have a default branch called `main`. Previously, the default name was `master`. The [change](https://github.com/github/renaming) was made to promote inclusive language in the version control world. SESYNC is planning to update the GitLab server to match this new default. However, the git client will still default to `master` if you create a repository locally, unless you configure it as described below. You should also be aware that any documentation, tutorial, or StackOverflow post written before 2020 will assume your default branch is called `master`.

If you are doing this lesson on your local machine, we recommend setting the default branch name for new repositories you create to `main`. Enter the following into your terminal prompt. You can access the prompt from Jupyter Lab's Terminal tab.

```
git config --global init.defaultBranch main
```

Next, set your name and email in git by running the following commands on the terminal. 
```
git config --global user.name "FirstName LastName"
git config --global user.name "email@example.com"
```
**The email address used should match the email address of yout GitHub account.**

You can start the terminal form the JupyterLab launcher.

![]({% include asset.html path="images/terminal_jupyter.png" %}){:.nobox}
{:.captioned}

### Create a new repository

A GitHub repository is like a supercharged folder in the cloud. You can store
files, look at historical changes to these files, open issues, discuss changes 
and more. People typically create one repository per project. 

Create a repository on GitHub. Once created, you'll see a page like the one below.

![]({% include asset.html path="images/copy-repo-url.png" %}){:.nobox}
{:.captioned}

Copy the highlighted repository URL which you will use to clone your remote repository. 


