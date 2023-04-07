# git pull

**git pull** updates your current local working branch, and all of the remote tracking branches. It's a good idea to run **git pull** regularly on the branches you are working on locally.

# git fetch

**git fetch** updates all the remote tracking branches in local repository. No changes are actually reflected on any of the local working branches.

# git pull and git fetch

**git pull**, a combination of **git fetch** + **git merge**, updates some parts of your local repository with changes from the remote repository. To understand what is and isn't affected by **git pull**, you need to first understand the concept of remote tracking branches. When you clone a repository, you clone one working branch, main, and all of the remote tracking branches. **git fetch** updates the remote tracking branches. **git merge** will update your current branch with any new commits on the remote tracking branch.

If you do use **git fetch** instead of **git pull**, make sure you remember to **git merge**. Merging the remote tracking branch into your own branch ensures you will be working with any updates or changes.

---

_Sources_

https://www.freecodecamp.org/news/git-pull-explained/#git-fetch-plus-git-merge

https://github.com/git-guides/git-pull
