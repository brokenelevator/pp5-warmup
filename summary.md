#Git overview
Following summary may help to understand daily work with git.

## Section name
Description of command
```sh
command itself
```

## Creation

Initialize new repository structure in current working directory
```sh
git init
```

## Local changes

Show current repository status
```sh
git status
```

Show difference between revisions
```sh
git diff
```

Add files to be tracked
```sh
git add [filenames]
```

Add all 'add'ed changes to new revision and open editor to supply a comment
```sh
commit
```

Add tracked and changed files to new revision and open editor to supply a comment
```sh
commit -a
```

Add tracked and changed files to new revision and use "mycomment" as a comment
```sh
commit -a -m "mycomment"
```

##History Management

List all commits in reverse chronological order
```sh
git log
```
