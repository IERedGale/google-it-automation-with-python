# Introduction to Git and GitHub - Week 2

## Advanced Git interaction

### Git Commands Cheatsheet

* git commit -a: Stages files automatically
* git log -p: Produces patch text
* git show: Shows various objects
* git diff: Is similar to the Linux `diff` command, and can show the differences in various commits
* git diff --staged: An alias to --cached, this will show all staged files compared to the named commit
* git add -p: Allows a user to interactively review patches to add to the current commit
* git mv: Similar to the Linux `mv` command, this moves a file
* git rm: Similar to the Linux `rm` command, this deletes, or removes a file

---

## Undoing Things

### Git Revert Cheatsheet

* git checkout: Used to switch branches
* git reset: Resets the repo by throwing away some changes
* git commit --amend: Make changes to commits after-the-fact, which can be useful for making notes about a given commit
* git revert:  Makes a new commit which effectively rolls back a previous commit. It’s a bit like an undo command

### Ammeding Commits

Avoid amending commits that have already been made public.

### Identifying a Commit

The commit ID is the 40 character long string after the word commit generated by SHA1 algorithm. Git doesn't use these hashes for security. Instead, they're used to guarantee the consistency of our repository.

---

## Credit

* [Coursera - Introduction Git Github Week 2](https://www.coursera.org/learn/introduction-git-github/home/week/2)