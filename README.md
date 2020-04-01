# My GIT Work
git clone URL - to make a local copy of the file 
ls - to list all files in the directory
cd Directoryname - to change to that directory
git status - to find the state of the file like whether committed or not
git add filename - to add the file to the staging area
git commit -m 'Message' - commit the code to the local version control Database and -m represents Message
git push - to push the file to GitHub(cloud)
git log - log of all commit history ie commit id
git checkout --filename - undo uncommitted changes 
git checkout --. - to undo uncommitted changes to all files  
git revert commit_id - undo committed changes ie revert the changes and commit
git revert -n commit_id - revert and review the reverted changes and then commit ie requires explicit commit
                      :q - should be entered to confirm revert operation 
git reset --hard commit_id - resetting changes
git branch - list all the branches available
git branch newBranchName - create a new branch
git checkout BranchName - switch to mentioned branch name
git checkout -b BranchName - create a new branch and switch to mentioned branch name
git checkout -d BranchName - delete branch
git difftool HEAD HEAD~1 - compare the changes in the Most recent commit in the branch and previous one of the most recent commit in the branch
git checkout commit_id - to switch to the older version of the file
touch .gitignore - to create a .gitignore file to include the files to be ignored for committing to the repository
git push --set-upstream orgin Filename
