PULLING FROM GITHUB

git init
git remote add origin https://github.com/myName/myRepository
git pull origin main

PUSHING TO GITHUB FOR THE FIRST TIME

gh auth login
git remote set-url origin https://github.com/myName2/myRepository2
git add .
git commit -m "added files"
git push --set-upstream origin main

PUSHING TO GITHUB

git add .
git commit -m "updated files"
git push

VIEWING BRANCHES

git branch

CREATING A BRANCH

git branch myBranch

SWITCH TO A BRANCH

git switch myBranch

MERGING BRANCHES

git switch main
git merge myBranch

DELETING A BRANCH

git branch -d myBranch
