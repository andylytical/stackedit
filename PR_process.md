
# Collaboration Process
1. Create a branch
	* Naming convention: ticket/username/short-description
1. Commit often, test frequently
    * IMG
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
eyJoaXN0b3J5IjpbNjM2NjIwOTgzLDI5MTQyNzA3MSw1NDMxMT
Y3NTUsLTM3OTU0MzE5NCwtMjA4ODc0NjYxMiwtMzMyNDU1MzYz
XX0=
-->