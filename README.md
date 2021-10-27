
**Taro's personal memo**

Before work

```
git status
git fetch (fetch the remote version)
git pull (download the changes)
git stash (temporary remove the local changes)
```

After work
```
git status
git add -u
git commit -m “your message”
git push
```

Resolve conflicts
```
before your commit, “git stash” your change, and do a “git pull”.
“git stash apply” or “git stash pop” your previous change to your working directory. You might then see many conflicts.
Go inside the code and manually resolve those conflicts.
Commit your resolved files
git push
```
