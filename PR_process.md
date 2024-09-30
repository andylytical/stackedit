
# Collaboration Process
## Overview
![Git Workflow](https://github.com/andylytical/stackedit/blob/access/ctt-222/Git%20Workflow.png)
## Workflow
1. Create a branch
    * Naming convention: ticket/username/short-description
    * `git branch {your/branch/name}`
    * `git commit -u origin {your/branch/name}`
      * where `{your/banch/name}` is the actual name of your branch, without the curly braces
#### CODE
1. Edit
   * `vim file1`
   * `vim file2`
1. Commit
   * `git status`
   * `git add file1 file2`
   * `git commit -m "updated file1 & file2"`
1. Push
   * `git push`
1. Test
   * Test according to the procedures specific to the project you are working on
1. Repeat EDIT > COMMIT > PUSH > TEST cycle until changes are complete and fully tested
#### REVIEW
1. Pull Request
   * Github.com > Project site > Pull requests > New pull request
   * base: main :arrow_left: compare:{your/branch/name} > Create pull request
   * Add a title
   * Add a description
   * Assignees > assign yourself (you are responsible to merge this once approved)
   * (optional) Assign Reviewers
   * Create pull request
1. Review
   * Participate in the review commentary
   * Fix any issues following the EDIT > COMMIT > PUSH > TEST cycle until all review items are complete and fully tested
#### MERGE
1. Rebase
   * `git checkout main`
   * `git pull`
   * `git checkout {your/branch/name}`
   * `git rebase -i main`
     * "pick" the 1st commit
     * "squash" all the others
   * `git push -f origin {your/branch/name}`
   * test again
1. Merge to main
   * `git checkout main`
   * `git pull`
   * `git merge {your/branch/name}`
     * (Note: Repo settings will only allow a fast forward merge)
1. Delete your branch
   * `git branch -d {your/branch/name}`
   * `git push origin :{your/branch/name}`

# References
* [GitHub flow](https://docs.github.com/en/get-started/using-github/github-flow)
* [GitHub flow explained](https://scottchacon.com/2011/08/31/github-flow/)
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE1ODA2NzEzNTEsMTMwNzM0NDU1NiwtMT
QxMTA4MjkyOCwtNTUyNDg1NDUzLDM4OTgzNjM1MSwyMDM4ODQ0
MjIwLC05NzczMjIyMDMsLTE2MzUwNjgwMTcsMjkxNDI3MDcxLD
U0MzExNjc1NSwtMzc5NTQzMTk0LC0yMDg4NzQ2NjEyLC0zMzI0
NTUzNjNdfQ==
-->