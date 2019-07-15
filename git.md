# Git Commands Cheat sheet

### Git Log

**Git history of a file**
```
git log -p  <<FILE_PATH>>
```

### Git config

**Change user name and user email globally**
```
git config --global user.name "John Doe"
git config --global user.email "johndoe@example.com"
```

**Change user name and user email locally**
```
git config user.name "John Doe"
git config user.email "johndoe@example.com"
```

### Git Tag

**Add a new tag with a message**
```
git tag -a tagName -m "Tag Message"
```

**List all tags with its messages**
```
git tag -n
```

**Push all tags to origin**
```
git push <remote-origin> <branch-name> --tags
```
