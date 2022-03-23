# handy-git-commands
List of uncommon git commands that I might forget.

| Command | Function |
| ------- | -------- |
| `git checkout -- .` | Discard all unstaged local changes |
| `git checkout -- /path/to/file.xyz` | Discard unstaged local changes in `file.xyz` |
| `stat -c %Y .git/FETCH_HEAD` | Gives UNIX timestamp of the last git pull |
