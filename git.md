# Random git commands I forgety

## Set global username and email

```
git config --global user.name "Ben Wells"
git config --global user.email "b.v.wells@gmail.com"
```

## Amend author in last commit

```
git commit --amend --author="Ben Wells <b.v.wells@gmail.com>"
```

## Re-sync origin to master
```
git checkout -B master origin/master
```

## Make file executable

```
git update-index --chmod=+x foo.sh
```