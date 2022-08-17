## Git and Git Branching Cheat Sheet


### Basic commands
* `git init` - initialize current directory with repository
* `git add .` - add all new  or changed files in current directory to git index, staging them for commit
* `git commit -m "some message"` - commit staged   changes to repository

### Info commands
* `git status` - who status of current working directory
* `git log` - show history of commits
* `git log --oneline` - show history of commits but only as commit message (compact)
* `git config -l` list local git configuration settings


### Branch commands
* `git branch` - List local branches, highlight current branch
* `git branch branchName` - create branch   `branchName`
* `git checkout branchName` - witch to branch  `branchName`
* `git checkout -n otherBranch` - switch to branch `otherBranch`, creating it if it doesn't exist

### Remote commands
* `git remote add origin someUrl` - connect local repo to remote repo   url   as `origin`
* `git push origin branchName` - push local commits to remote repo into branch `branchName`

### Other commands
* `git help` - list git subcommands and options
* `git config --help` - show options for  `git config`
