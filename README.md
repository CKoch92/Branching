## Git Cheat Sheet

Brief reference of various git commands. Also practice with git branching.

* `git init` - Initialize a local git repo in working directory
* `git status` - Show state of local repo
* `git log` - List commit history
* `git log --oneline` - Compact commit history
* `git config -l` - list git and repo configuration
* `git add .` - Stage current directory in git index
* `git commit -m "msg"` - Commit work to local repo with commit message "msg"
* `git diff sha` - Show diffsbetween current commit and commit id `sha`
* `git diff oneBranch otherBranch` - Show diffs between `oneBranch` and `otherBranch`

### Branching
* `git branch` - list local branches
* `git branch new branch` create local branch `newBranch`
* `git checkout newBranch` - Move to branch `newBranch`

### Remote Repos
* `git remote add alias url` - Add `alias` as name for remote repo `url` in project configuration
* `git push alias aBranch` - push local commits to remote repo `alias`'s branch `aBranch`
* `git pull alias aBranch` - pull remote `aBranch` from `alias` into current local branch
* 
