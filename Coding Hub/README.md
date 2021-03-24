# Coding Hub 
## Git cheatsheet
| Task | Git Command |
| -------- | -------- |
| Tell Git your name | ```git config --global user.name "Sam Smith" ```|
| Tell Git your email | ``` git config --global user.email sam@example.com ```|
| Create a new local repository | ```git init```|
| Create new branch | ```git checkout -b <branch_name> ```|
| List all branches | ``` git branch```|
| Switch to branch | ``` git switch <branch_name>```|
| Switch to branch and merge with previous branch| ```git checkout <branch_name>```|
| Delete branch | ``` git branch -d <branch_name> ```|
| Commit to branch | ```git commit -m "Your Commit message"```|
| Merge current branch with other branch | ```git merge <other_branch_name> ```
| Add files to commit| ```git add <filename>``` or ```git add * ```|
| Commit all files | ```git commit -a```|
| Add remote repository | ```git remote add <server_name> <server_address>```|
| List all remotes | ```git remote -v ```|
| Delete remote | ```git remote rm <server_name>```|
| Git Status | ```git status```|
| Push local branch to remote branch| ```git push <server_name> <branch_name>```|
| Push all branches to remote repository | ```git push --all origin```|
| Push local branch to other remote branch | ```git push <remote> <local_branch>:<remote_branch>```|
| Push local branch to remote repository | ```git push --set-upstream <server_name> <branch_name>```|
| Push local branch to remote branch (if current local branch is available in remote repository) | ```git push```|
|Update branch from remote repository| ```git pull```|
| Get new copy of data from remote repository| ```git fetch <server_name>```|
| Get Git logs| ```git log```|
| Add tag to branch | ```git tag -a v1.4 -m "my tag version 1.4"``` |
| Show tags | ```git tags```|
| Delete tag | ```git tag -d <tag_version>```|
| Delete tag from remote repository | ```git push <server_name> :refs/tags/<tag_version>``` or ```git push <server_name> --delete <tag_version>```|
| Push all tags to remote repository | ```git push <server_name> --tags ```|
| Push single tag to remote repository| ```git push <server_name> <tag_version>```|
| Fetch all tags from remote repository| ```git fetch --tags```|
| Checkout tags to current branch | ```git checkout <tag_version>```|
| Create tag from commit reference | ```git tag <tag_version> <reference_of_commit>```|
| Create new branch from tag | ```git checkout -b <new_branch_name> <tag_version>```|


Hey Coder, you can read more about Git [here](https://git-scm.com/doc)
