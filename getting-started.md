
# Getting Started with Git


After installing git,
```bash
sudo apt install git
```

you should set some configuration settings:
```git
git config --global init.defaultBranch main
```


#### Git Autocompletion
---

You can source a git command autocompletion script in your .shellrc file. The autocompletion script can be found on the git repo site: [github.com/git/git](https://www.github.com/git/git) under ./contrib/completion.



#### Viewing Commits
---

Viewing all commits with info:
```git
git log
```

Limiting the `number` most recent commits:
```git
git log -n `number`
```

Filtering by time:
```git
git log --since=yyyy-mm-dd
```
shows all commits since given date.


<br>

```git
git log --until=yyyy-mm-dd
```
opposite of `since` option.


Filtering by author:
```git
git log --author="<greppable string>"
```

Filtering by commit message:
```git
git log --grep="<portion of commit message>"
```



