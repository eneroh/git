# git

## Summary
The beginning of my git journey and inspiration for this repo: https://pages.github.com/

```git
git clone <repository>
```
Downloads a github repository copy for you on your local machine

```git
git add *
git add --all
```
Adds updates to push upstream

```git
git commit -m "<updates>"
```
Adds to the update a message stating information
Input message on what has changed

```git
git push -u origin main
```
Pushes the changes to the main repository and updates the file

```git
git pull
```
Pulls the content from a remote repository and then updates your local repository to reflect the remote repo

```git
git rebase 
```
Pulls latest updates to repo while maintaining your current edits


```git
git fetch -all
```
Fetchs all versions available

```git
git push -f origin main
```
Resolves rebase constant git pull error

```git
git checkout <version>
```

```git
git checkout
```
Provides basic information on whats happening with errors

```git
git stash
git pull origin main
git stash apply 0
```
If prompted with: Merge with strategy ort failed.
<br>
Saves working dir and allows for updates to push forward
<br>
Finally git push -u origin main, problem is solved

```git
git reset --hard
```
If you've made some massive changes that have messed too many things up, use this command to revert to the remote branch (working repo)
