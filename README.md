## git-assignment

 create a new repository on the command line
echo "# git-assignment" >> README.md
## initalizing new repo
git init
## adding file to repo
git add README.md
## commiting changes
git commit -m "first commit"
## creating new branch
git branch -M main
## seting remote repo
git remote add origin https://github.com/Sulochanaakki/git-assignment.git
## pushing code to remote repo and branch main
git push -u origin main
## checking git status
git status

## checking out for new branch
 git checkout -b develop1
## another way of adding files to git
git add. 

## to push code to new branch develop1
git push --set-upstream origin develop1

## to clean untraked files

git clean

## to clone the existing repo
git clone remote rpo name

## Passing the --amend flag to git commit lets you amend the most recent commit. This is very useful when you forget to stage a file or omit important information from the commit message.
git commit --amend

## A convenient way to set configuration options for your Git installation
git config

## Fetching downloads a branch from another repository, along with all of its associated commits and files
git fetch

## Lets you explore the previous revisions of a project. It provides several formatting options for displaying committed snapshots.
git log

#
