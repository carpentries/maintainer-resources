# Flight Rules

Below is a list of useful resources for working on your lesson.

## Update styles

To update your lesson to match the current version of the styles template, use the following steps:

1. checkout a new branch
2. pull the head branch of the styles repo (which is fetch and merge)
3. Fix any merge conflicts and commit the merge
4. push the new branch up to your repository and create a pull request

```bash
git checkout -b update-styles
git pull https://github.com/carpentries/styles
# FIX MERGE CONFLICTS
git push -u origin update-styles
```
  
## How to checkout a github pull request locally

e.g. checking out pull request `#25` into a branch called `pr-25`

```bash
git fetch origin pull/25/head:pr-25
git checkout pr-25
```
 
## Useful Links

- https://stackoverflow.com/a/30584951/2752888
- https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/checking-out-pull-requests-locally
- https://usethis.r-lib.org/articles/articles/pr-functions.html (in R).
