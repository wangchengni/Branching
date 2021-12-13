## Git Cheat Sheet

Personal reference for Git commands.

## Basic Commands
*`git init` -Initialize local Git repository
*`git add .` -Add all files in and under current directory to git index, staging them for commit
*`git commit -m"Message"` - Commit changes
to local repo with commit message "Message"


### Information Commands
*`git status` -display current status of local working irectory /repository
*`git log`-list commit history
*`git log --oneline` -list commit history, compact format

### Branching Commands
*`git branch` -List of local git branches
*`git branch newBranch`- Create local branch `newBranch`
*`git checkout newBranch` - Check out local branch `newBranch`
*`git branch -M otherBranch` -Rename current branch to `otherBranch`

### Remote Commands
*`git remote add origin remoteUrl` -Add alias "origin" for remote repository
Url "remoteUrl"
*`git push origin main` -Push locally-committed changes to  `main` branch on remote
repository
*`git push -u origin main` -Same, setting "origin main" as default for subsequent  
`git push`
