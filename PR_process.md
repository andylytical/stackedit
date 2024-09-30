
# Collaboration Process
## Overview
![Git Workflow](https://github.com/andylytical/stackedit/blob/access/ctt-222/Git%20Workflow.png)
## Workflow
1. Create a branch
    * Naming convention: ticket/username/short-description
1. Do work, Make changes, Commit often, Test frequently
1. Pull Request
    * Fix any issues
1. Rebase to main
    * `git go main`
    * `git go BRANCH`
    * `git rebase -i main`
      * "pick" 1st commit
      * "squash" all the others
    * test again
1. Merge to main
    * Should be a fast forward
      * Repo settings enforce "only FF merges to main" ?
    * Delete branch
1. Deploy production
    * Restricted to "Maintainer" ?

# References
* [GitHub flow](https://docs.github.com/en/get-started/using-github/github-flow)
* [GitHub flow explained](https://scottchacon.com/2011/08/31/github-flow/)

<!--stackedit_data:
eyJoaXN0b3J5IjpbNjkxMTQ0Mjc3LC05NzczMjIyMDMsLTE2Mz
UwNjgwMTcsMjkxNDI3MDcxLDU0MzExNjc1NSwtMzc5NTQzMTk0
LC0yMDg4NzQ2NjEyLC0zMzI0NTUzNjNdfQ==
-->