## Git Cheat Sheet

### Basic Commands
* 'git init' - Initalize local git repository
* 'git add' - Add all files in and under current directory to git index, staging them for commit
* 'git commit -m"message"' - Commit changes to local repo

### Information Commands
* 'git status' - Display current status of local working directory/repository
* 'git log' - List commit history
* 'git log --oneline' - list commit history, compact format

### Branching Commands
* 'git branch' - Lost local git branches
* 'git branch newBranch' - Create local branch 'newBranch'
* 'git checkout newBranch' - check out local 'newBranch'
* 'git branch -M otherBranch' - Rename current branch to 'otherBranch'

### Remote Commands
* 'git remote add origin remoteUrl' - Add alias "origin" for remote repository URL "remoteUrl"
* 'git push origin main' - Push locally-committed changes to 'main' branch on remote repository
* 'git push -u origin main' - Same, setting "origin main" as default for subsequent 'git push'
