# Understanding Git and GitHub / BitBucket
Created by Prashanth for experimenting with Git etc.

## Creating a project
git init

## Commit workflow
- git add filename
- git commit -m "the commit message goes in here"

## Checking status
git status

## Checking commit history
git log

## Adding and checking remotes
- git remote add remote_name remote_url
- Generally the default remote is called ```origin```
- git remote -v

## Pushing
- First time
```
git push -u remote_name remote_branch_name_to_track
```
Example
```
git push -u origin master
```
- Later on
```
git push
```

## Downloads and references
- https://git-scm.com/