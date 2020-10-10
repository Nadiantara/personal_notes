
### Working with local branch  
- Manage branches: git branch  
- Deletes the branch: git branch -d <name>  
- Forcibly deletes the branch: git branch -D <name>
- Creates new branch: git branch <name>  
- Switches to a branch : Switches to a branch.
- Creates a new branch and switches to it : git checkout -b <branch>
- Merge joins branches together: git merge <branch>
- If there are merge conflicts (meaning files are incompatible), --abort can be used to abort the merge action. : git merge --abort  
- This shows a summarized view of the commit history for a repo : git log --graph --oneline

### Working with remote repository
- Lists remote repos: git remote 
- List remote repos verbosely: git remote -v 
- Describes a single remote repo: Describes a single remote repo
- Fetches the most up-to-date objects: git remote update
- Downloads specific objects: git fetch
- Lists remote branches; can be combined with other branch arguments to manage remote branches: git branch -r 
