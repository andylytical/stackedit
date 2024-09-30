
# Collaboration Process
## Overview
![Git Workflow](https://github.com/andylytical/stackedit/blob/access/ctt-222/Git%20Workflow.png)
## Workflow
1. Create a branch
    * Naming convention: ticket/username/short-description
1. Do work
	1. EDIT
	   * vim \<file1\>
	   * vim \<file2\>
	1. COMMIT
	1. PUSH
	1. TEST
3. Pull Request
    * Fix any issues
4. Rebase to main
    * `git go main`
    * `git go BRANCH`
    * `git rebase -i main`
      * "pick" 1st commit
      * "squash" all the others
    * test again
5. Merge to main
    * Should be a fast forward
      * Repo settings enforce "only FF merges to main" ?
    * Delete branch
6. Deploy production
    * Restricted to "Maintainer" ?

# References
* [GitHub flow](https://docs.github.com/en/get-started/using-github/github-flow)
* [GitHub flow explained](https://scottchacon.com/2011/08/31/github-flow/)

<!--stackedit_data:
eyJoaXN0b3J5IjpbMzQyNTE2MzcyLC05NzczMjIyMDMsLTE2Mz
UwNjgwMTcsMjkxNDI3MDcxLDU0MzExNjc1NSwtMzc5NTQzMTk0
LC0yMDg4NzQ2NjEyLC0zMzI0NTUzNjNdfQ==
-->