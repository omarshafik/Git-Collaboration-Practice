# Git-Collaboration-Practice
#### The following steps show you how to collaborate with teammates in a github repo:  
1. Clone this repo using `git clone https://github.com/omarshafik/Git-Collaboration-Practice.git`, this will copy all the contents of all branches in this repo.  
2. Before adding changes use `git checkout -b new_branch old_branch`, this will create and switch to a new local branch with name new_branch that has all contents of old_branch branch, when using `git checkout -b new_branch` the new branch will copy contents of master branch.   
3. After finishing your changes add and commit your changes then switch to the branch you wish adding changes to using `git checkout old_branch`, and use `git pull origin old_branch` to update your local branch with online github branch.  
4. You can now merge your changes in the new branch (new_branch) you created with the contents of the current branch, to merge use the command `git merge new_branch`.  
5. Update the upstream(online) branch with the new changes using `git push origin old_branch`.   
