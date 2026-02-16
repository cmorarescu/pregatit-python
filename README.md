# PregatIT 2026 Python exercises repo

## 1. This repo will be used to provide code 'challenges' for the students attending the PregatIT 2026 programme.

## Branching requirements:

Before pushing any piece of code to remote you will need to setup your own branch based on 'main' branch
Follow these steps:

`git checkout main` switch to main branch

`git pull` - update your local main branch with latest code from main (there might be some changes as we go)

while on the main branch `git checkout -b YOUR_BRANCH_NAME` to create your own branch, based on main branch

once you are on your own branch you can start working on the week's assignment

when you think you are done, or you have done some progress, remember to commit the changes

to check the state of your branch and which files are in the 'staging area' or you have changed (created, modified) you can run 
`git status`

this will show you a list of changed or created files, list of files aready staged for commit etc.

choose which files you want to add to the staging area of the commit and run `git add` for each of them
ex. `git add src/week1/week1_practice.py`

to stage all modified files, you can also run `git add .` - it will stage the entire project folder - Beware of this, you might add unwanted files

after staging all files for commit, create the commit and add a message 

`git commit -m "YOUR_COMMIT_MESSAGE'`

create as many commits as you want. after you are happy with the state of your application, push the changes: `git push`
usually you will also need to setup a remote branch if it's not configured to do so automatically.

go to github and create a Pull Request YOUR_BRANCH_NAME -> MAIN
