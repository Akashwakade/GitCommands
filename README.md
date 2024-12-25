# GitCommands

==> link for git official document
https://git-scm.com/doc

==> link for all video related to git
https://git-scm.com/videos


1) configure git globally for all repository
To set your name and email globally:

git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"

Verify congiguration

git config --global --list


2) Configure Git for a Specific Repository
To set your name and email only for a specific project/repository:

cd path/to/your-repo
git config user.name "Your Project Name"
git config user.email "your.project.email@example.com"

to Verify

git config --list

3) to config default branch
to set main as a default branch

git config --global init.defaultBranch main


4) to view all configuration
(global,local,system)

git config --list --show-origin

5) Example Final Configuration (~/.gitconfig)

6) to check remote repo already link
git remote -v

7)to set remote repo
git remote add origin <repository-url>

8) to push
git push -u origin main  (replace main with branch name)

9) check your local branch
git branch

10) if branch is not there create one 
git checkout -b branchname

11) to check status
git status

12) push the branch to remote repo
git push -u origin day1

13) verify remote branch
git branch -a

14) switch back to main
git checkout main



