## Git
It is a distributed open source version control system (VCS) which gives us an efficient control over our projects, it's a a file tracing system. The distributed system provides a platform for developers or partners to work on the same project without being in the same server. 

Git provides three working areas:

- Working directory or local copy - the files you are editing
- Staging area or index area - an intermediate space to store files scheduled for the next commit
- Repository - it is a sub-directory named .git and contains the whole history of your project

### Workflow of Git project

- Modify files in your working directory
- Add a file to the staging area
- Commit a file to the git directory

![Workflow of Git project](git_workflow.png){width=300}


### Installation and check version of git

``` bash
sudo apt-get install git-core
git --version
```

### Configuring git
It's mandatory to setup user name and email address, for credential purpose. 

Replace the username and email address with your own
``` bash
git config --global user.name [user name]
git config --global user.email [e-mail address]
# Checking configuration
git config --list
# To get help
git help
man git
man gitglossary
```
