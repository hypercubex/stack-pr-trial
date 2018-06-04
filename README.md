# Stack PR Trial
Trial to reduce PR size by stacking up PR via branches.
Branches are kept for demo purpose.

# Procedures
1. branch out as `feature-branch`
1. code change
1. `git add --patch`
1. commit, push, and create PR for review
1. branch out from `feature-branch`
1. code change
1. `git add --patch`
1. commit, push, and create PR to merge into `feature-branch` for review

# References
- The demo is based on https://graysonkoonce.com/stacked-pull-requests-keeping-github-diffs-small/

- more on [git add --patch](https://johnkary.net/blog/git-add-p-the-most-powerful-git-feature-youre-not-using-yet/)