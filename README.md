# Git Handbook

## Complete Playlist

- **English**\
[Anisul Islam](https://www.youtube.com/playlist?list=PLgH5QX0i9K3qAW8DT6I0XOxC23qnA4FL) ,[Anisul Islam](https://www.youtube.com/playlist?list=PLgH5QX0i9K3qAW8DT6I0XOxC23qnA4FL) ,

- **Bengali**\
[Anisul Islam](https://www.youtube.com/playlist?list=PLgH5QX0i9K3qAW8DT6I0XOxC23qnA4FL) , [Anisul Islam](https://www.youtube.com/playlist?list=PLgH5QX0i9K3qAW8DT6I0XOxC23qnA4FL) ,

## Topics

- **Repository**
- **Git clone**
Git clone is a command for downloading existing source code from a remote repository (like Github, for example). In other words, Git clone basically makes an identical copy of the latest version of a project in a repository and saves it to your computer.\
&emsp;&emsp; `git clone <https://name-of-the-repository-link>`\
English : [channel name 1](https://www.youtube.com/playlist?list=PLgH5QX0i9K3qAW8DT6I0XOxC23qnA4FL) , [channel name 2](https://www.youtube.com/playlist?list=PLgH5QX0i9K3qAW8DT6I0XOxC23qnA4FL)\
Bengali : [channel name 1](https://www.youtube.com/playlist?list=PLgH5QX0i9K3qAW8DT6I0XOxC23qnA4FL) , [channel name 2](https://www.youtube.com/playlist?list=PLgH5QX0i9K3qAW8DT6I0XOxC23qnA4FL)

- **Git status**
The Git status command gives us all the necessary information about the current branch.\
&emsp;&emsp; `git clone status` 
- **Git add**
When we create, modify or delete a file, these changes will happen in our local and won't be included in the next commit (unless we change the configurations).
We need to use the git add command to include the changes of a file(s) into our next commit.\
&emsp;&emsp; `git add .`\
Bangli: [channel name: Anisul Islam](https://www.youtube.com/watch?v=IDhgZX4esQQ&list=PLgH5QX0i9K3qAW8DT6I0XOxC23qnA4FL-&index=5)
- **Git commit**
This is maybe the most-used command of Git. Once we reach a certain point in development, we want to save our changes (maybe after a specific task or issue).\
&emsp;&emsp; `git commit -m "write your meaningfull message"`\
Bangla: [channel name: Anisul Islam](https://www.youtube.com/watch?v=gmBKbxKGcn8&list=PLgH5QX0i9K3qAW8DT6I0XOxC23qnA4FL-&index=7)
- **Git pull**
The git pull command is used to get updates from the remote repo.\
&emsp;&emsp; `git pull <remote>`\
Bangla : [channel : Anisul Islam](https://www.youtube.com/watch?v=UXEoCfYwI1Q&list=PLgH5QX0i9K3qAW8DT6I0XOxC23qnA4FL-&index=14)
- **Git push**
After committing your changes, the next thing you want to do is send your changes to the remote server. Git push uploads your commits to the remote repository.\
&emsp;&emsp; `git push <remote> <branch-name>`\
Bangla: [channel name: Anisum Islam](https://www.youtube.com/watch?v=UXEoCfYwI1Q&list=PLgH5QX0i9K3qAW8DT6I0XOxC23qnA4FL-&index=14)
- **Git revert**
The git revert command is used for undoing changes to a repository's commit history.\
&emsp;&emsp; `git revert main`  
- **Git branch**
Branches are highly important in the git world. By using branches, several developers are able to work in parallel on the same project simultaneously.\
&emsp;&emsp; `git branch <branch-name>`\
Bangali : [channel name: Anisul Islam](https://www.youtube.com/watch?v=3k8Bq_usPsk&list=PLgH5QX0i9K3qAW8DT6I0XOxC23qnA4FL-&index=15)
- **Git checkout**
This is also one of the most used Git commands. To work in a branch, first you need to switch to it. We use git checkout mostly for switching from one branch to another. We can also use it for checking out files and commits.\
&emsp;&emsp; `git checkout <name-of-your-branch>`
- **Git merge**
When you've completed development in your branch and everything works fine, the final step is merging the branch with the parent branch (dev or master). This is done with the git merge command.\
&emsp;&emsp; `git merge <branch-name>`\
Bangali : [channel name: Anisul Islam](https://www.youtube.com/watch?v=3k8Bq_usPsk&list=PLgH5QX0i9K3qAW8DT6I0XOxC23qnA4FL-&index=15)
- **Fork**
A fork is a copy of a repository. Forking a repository allows you to freely experiment with changes without affecting the original project.\
Bangali [channel name: Anisul Islam](https://www.youtube.com/watch?v=FH0wptOLukk&list=PLgH5QX0i9K3qAW8DT6I0XOxC23qnA4FL-&index=23)
- **Pull Request**
Pull requests let you tell others about changes you've pushed to a branch in a repository on GitHub. Once a pull request is opened, you can discuss and review the potential changes with collaborators and add follow-up commits before your changes are merged into the base branch.\
Bangali: [channel name: Anisul Islam](https://www.youtube.com/watch?v=UXEoCfYwI1Q&list=PLgH5QX0i9K3qAW8DT6I0XOxC23qnA4FL-&index=14)

## Git Commands

### Getting & Creating Projects

| Command | Description |
| ------- | ----------- |
| `git init` | Initialize a local Git repository |
| `git clone ssh://git@github.com/[username]/[repository-name].git` | Create a local copy of a remote repository |

### Basic Snapshotting

| Command | Description |
| ------- | ----------- |
| `git status` | Check status |
| `git add [file-name.txt]` | Add a file to the staging area |
| `git add -A` | Add all new and changed files to the staging area |
| `git commit -m "[commit message]"` | Commit changes |
| `git rm -r [file-name.txt]` | Remove a file (or folder) |

### Branching & Merging

| Command | Description |
| ------- | ----------- |
| `git branch` | List branches (the asterisk denotes the current branch) |
| `git branch -a` | List all branches (local and remote) |
| `git branch [branch name]` | Create a new branch |
| `git branch -d [branch name]` | Delete a branch |
| `git push origin --delete [branch name]` | Delete a remote branch |
| `git checkout -b [branch name]` | Create a new branch and switch to it |
| `git checkout -b [branch name] origin/[branch name]` | Clone a remote branch and switch to it |
| `git branch -m [old branch name] [new branch name]` | Rename a local branch |
| `git checkout [branch name]` | Switch to a branch |
| `git checkout -` | Switch to the branch last checked out |
| `git checkout -- [file-name.txt]` | Discard changes to a file |
| `git merge [branch name]` | Merge a branch into the active branch |
| `git merge [source branch] [target branch]` | Merge a branch into a target branch |
| `git stash` | Stash changes in a dirty working directory |
| `git stash clear` | Remove all stashed entries |

### Sharing & Updating Projects

| Command | Description |
| ------- | ----------- |
| `git push origin [branch name]` | Push a branch to your remote repository |
| `git push -u origin [branch name]` | Push changes to remote repository (and remember the branch) |
| `git push` | Push changes to remote repository (remembered branch) |
| `git push origin --delete [branch name]` | Delete a remote branch |
| `git pull` | Update local repository to the newest commit |
| `git pull origin [branch name]` | Pull changes from remote repository |
| `git remote add origin ssh://git@github.com/[username]/[repository-name].git` | Add a remote repository |
| `git remote set-url origin ssh://git@github.com/[username]/[repository-name].git` | Set a repository's origin branch to SSH |

### Inspection & Comparison

| Command | Description |
| ------- | ----------- |
| `git log` | View changes |
| `git log --summary` | View changes (detailed) |
| `git log --oneline` | View changes (briefly) |
| `git diff [source branch] [target branch]` | Preview changes before merging |

## References

- Git Topics : [freeCodeCamp](https://www.freecodecamp.org/news/10-important-git-commands-that-every-developer-should-know/)
- Git Commands : [Joshua Hibbert](https://github.com/joshnh/Git-Commands)
