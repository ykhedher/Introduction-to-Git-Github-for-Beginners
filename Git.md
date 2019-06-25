# Learning Git
## What is Git ?
- Keeps track of changes to code.

- Synchronizes code between different people.

- Test changes to code without losing the original.

- Revert back to old versions of code

## Commands
- git clone <URL>
   - Makes a copy of a repository* (folders that contains files that are tracked via git.).
   - Stores it on your computer.
   - A "fork" creates your own copy of someone else's repository.
  
- git add <file_name>
  - Adds a file to "staging area"
  - Tells git to include the file in the next revision to the repository.
  - " git add * ": adds all changed files
   
- git commit -m "message"
  - Saves the changes to a repository as a new revision (a commit).
  - Records a message.
  - " git commit -am "message" ": Adds and commit in the same time.
   
- git status
  - Shows current status of a repository.
  
- git push / git push origin master
  - Sends comitted changes to remote repository.

- git pull
  - Retrieves changes from remote repository.
 
 ## Merge Conflicts
 
- When two different commits can't be automatically merged.
- Need to be resolved.
 
- git reset
 - git reset --hard <commit> : revers code back to a previous commit.
 - git rest --hard origin/master : reverts code back to remote repository.
  
## Branching

- What's a Branch ?
  - Branch is a version of the repository.
  - Each branch has its own commit history and current version.
 
- git branch
  - Shows all branches of code.
  - Create a branch with a " git branch <branch_name> ".
  - Switch to ("checkout") a new branch with " git checkout <branch_name> ".
  - " git branch -d " : Delete the branch.

- git merge
  - " git merge <branch_name> " merges the branch <branch_name> with current branch.

## Pull Request
 - Submit a request to the rep owner to merge your edits with the original branch (master).
 - The rep Owner will review and see the changes.
  
 
