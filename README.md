
## Trying Git and Github workflow

Git is a Version Control management system used to organize and keep track of code. Developed by Linus Torvalds, it was 
first thought to help with the development of the Linux Kernel. As the scope of the work done in the Kernel grew bigger,
massive collaboration of developers become difficult to  manage, so it was necessary to find a solution to this problem. 
At that moment there was a version control system called CVS, but Linus decided to design his own system.

Git allows to work not only with others but also helps in the development of personal projects. Long gone are the days of 
making multiple copies of the same files to keep track of content changes. Now, a git project keeps track of the different
changes in a folder called .git. Furthermore, it allows to work in different work environments called **branches**, so you 
can work in parallel different stages of your project.

For a first introduction it is advised to read the following `man` pages: `git`, `gittutorial`, and  `giteveryday`. Bellow
are some of the most used commands in Git.

### Basic commands

```
# Initialize git
git init

# Add all files in the current directory 
git add .

# View staged files
git status

# Commit staged files to currente branch with a brief message
git commit -m "Commit message"

# View commit log
git log
```

### Connect to Github

```
# Clone Github repo (SSH way)
git clone git@github.com:user_name/repo_name.git

# Get repo URL 
git remote -v

# Upload commited changes to the remote repo
git push
# git push origin main
```

### Branch manipulation

```
# git branch 
```
