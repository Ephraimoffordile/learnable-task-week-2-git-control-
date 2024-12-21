# VERSION CONTROL

Version control is a system that tracks and manages changes to your files over time, allowing you to:

* Revert to past versions
* Collaborate effectively
* Track changes made by different team members or reviewers

## DIFFERENCE BETWEEN GIT AND GITHUB

* **Git:** is a version control system that tracks changes in code.
* **GitHub:** is a web-based platform that hosts Git repositories, providing features like collaboration, issue tracking, and code review.

## GIT ALTERNATIVES

* Mercurial
* Subversion (SVN)
* Concurrent version system (CVS)

## DIFFERENCE BETWEEN A GIT FETCH AND A GIT PULL

* **Git Fetch:** Downloads the latest changes from a remote repository to your local repository without merging them into the current branch. This allows you to review the changes before integrating them.
* **Git Pull:** Combines `git fetch` and `git merge` into a single step. It downloads the latest changes from the remote repository and immediately merges them into your current branch.

## GIT REBASE AND ITS COMMAND

Git rebase rearranges the commit history of your current branch onto another branch. This creates a cleaner, more linear history.

**Command:**

```bash
git rebase <target-branch>
GIT CHERRY-PICK AND ITS COMMAND
Git cherry-pick allows you to select a specific commit from one branch and apply it to another branch.
Command:
Bash
git cherry-pick <commit-hash>
