#Git Commands Reference
#Basic Commands
git init # Initialize a new Git repository
git clone <url> # Clone a repository from a URL
git status # Show the status of the working directory
git add <file> # Stage changes to a file
git commit -m "<message>" # Commit staged changes with a message
Branching
git branch # List all branches
git branch <branch-name> # Create a new branch
git checkout <branch-name> # Switch to a branch
git merge <branch-name> # Merge a branch into the current branch
git branch -d <branch-name> # Delete a branch
Remote Repositories
git remote -v # List remote repositories
git remote add <name> <url> # Add a new remote repository
git push <remote> <branch> # Push changes to a remote branch
git pull <remote> <branch> # Pull changes from a remote branch
Viewing History
git log # Show commit history
git diff # Show changes between commits
git show <commit> # Show details of a specific commit
git blame <file> # Show who changed each line in a file
Undoing Changes
git reset <file> # Unstage a file
git checkout -- <file> # Discard changes in a working directory
git revert <commit> # Create a new commit that undoes a previous commit
Tagging
git tag <tag-name> # Create a new tag
git tag -d <tag-name> # Delete a tag
git push origin --tags # Push tags to remote
Stashing Changes
git stash # Stash changes
git stash pop # Apply stashed changes
git stash list # List stashed changes
