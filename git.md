# Random git commands I forgety

## Configuration

Set global username and email:
```
git config --global user.name "Ben Wells"
git config --global user.email "b.v.wells@gmail.com"
```

## Creating repos

Create repo:
```
git init repo-name
```

Clone repo:

```
git clone repo-url
```

## Making changes

Check status of changes:
```
git status
```

Stage file:
```
git add filename
```

Commit staged changes:
```
git commit -m "commit message"
```

Amend to last commit:
```
git commit --amend
```

Amend author in last commit:
```
git commit --amend --author="Ben Wells <b.v.wells@gmail.com>"
```

## Sychronize

Re-sync origin to master:
```
git checkout -B master origin/master
```

## Plumbing

Make file executable:
```
git update-index --chmod=+x foo.sh
```

## Merging commits

Rebase commits:
```
git rebase -i HEAD~n
```

Rebase to first commit:
```
git rebase -i --root master
```

Delete all branches apart from master
```
git branch | grep -v "master" | xargs git branch -D 
```
