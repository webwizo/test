local Git tag
-------------

git tag -d v1.0

## Delete a remote Git tag
git push origin :refs/tags/v1.0

## Delete a local Git branch
git branch -d branchName

## Delete a remote Git branch
git push origin :branchName


## Create branch via Tag
git checkout -b branchName tagName
git checkout -b version2 v2.0.0

## Merge a 'develop' branch into master?
git checkout master
git merge develop


