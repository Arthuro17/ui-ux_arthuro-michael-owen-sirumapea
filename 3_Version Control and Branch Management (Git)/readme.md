# Summary Version Control and Branch Management (Git)
## 1. Introduction and Instalation
Berisikan pengenalan tentang apa itu Versioning  dan Git serta cara menginstall git. 
- Versioning berarti mengatur versi dari source code program. 
- Git adalah salah satu version control system populer yang digunakan para developer untuk mengembangkan software secara bersama-sama (Git terdistribusi bukan tersenralisasi).

## 2. Setting up and Push
Berisikan cara melakukan setting up, saving changes, inspecting repository, dan syncing.
### Setting Up
#### git config 
- $ git config --global user name "John Done" 
- $ git config --global user email "johndone@email.com"
#### start with init 
- $ git init $ git remote add <remote_name> <remote_repo_url> 
- $ git push-u <remote_name> <local_branch_name>
#### start with existing project, start working on the project 
- $ git clone ssh://john@example.com/path/to/my-project.git 
- $ cd my-project

### Saving Changes
- working directory (git add) -> staging area (git commit) -> repository

- $ git status

- $ git add <directory> 
- $ git add hello.py 
- $ git add.

- $ git commit -m "add config file"
  
#### git diff, change file, add staging area 
- $ git diff --staged
#### stashing your work 
- $ git stash
#### re-applying your stashed changes 
- $ git stash apply

## 3. Branch and Conflict

### Branches
#### show all branch 
- $ git branch --list
#### create a new branch called <branch> 
- $ git branch <branch>
#### force delete the specified branch 
- $ git branch -D <branch>
#### list remote branch 
- $ git branch -a
#### Start a new feature 
- $ git checkout -b new-feature master
#### Edit some files 
- $ git add <file> 
- $ git commit -m "Start a feature" 
####### Edit some files 
- $ git add <file> 
- $ git commit -m "Finish a feature"
#### Merge in the new feature branch 
- $ git checkout master 
- $ git merge new feature 
- $ git branch -d new-feature
  
### Pull Request
### Workflow Collaboration
  
