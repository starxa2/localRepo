# This is my Local Repo

The general workflow is 
1. Github Repo
2. clone
3. changes
4. add
5. commit
6. push

git branch (to check branch) <br>
git branch -M main (to rename branch)<br>
git checkout <-branch name-> (to navigate)<br>
git checkout -b <-new branch name-> (to create new branch)<br>
git branch -d <-branch name-> (to delete branch)<br>

This is a new feature after shifting to feature1 branch

## Merging code

WAY_1 <br>
git diff <-branch name-> (to compare commits, branches, files & more) <br>
git merge <-branch name-> (to merge 2 branches) <br>

WAY_2 <br>
PR (pull request)

git pull origin main

used to fetch and download content from a remote repo and immediately update the local repo to match that content


## Undoing changes
Case 1 : staged changes <br>
git reset <-filename-> <br>
git reset <br>

Case 2 : commited changes(for one commit)<br>
git reset HEAD-1<br>

Case 3 : commited changes (for many commits)<br>
git reset <-commit hash-><br>
git reset --hard <-commit hash-><br>

## Fork
A fork is a new repository that shares code and visibility settings with the original "upstream" repository<br>
Fork is a rough copy.