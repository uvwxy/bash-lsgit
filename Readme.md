# lsgit

Show status about git repositories in the current directory.

## Usage

### Show git status

```
# lsgit
Repo                              Branch                     Changes   Stash Count
bash-lsgit                        master                           2   0  
repo1                             master                           0   0  
repo2                             testing                          0   1
```

### Update git status

`# lsgit update` will call `git remote update` in every repository before displaying information.

![lsgit screenshot](https://github.com/uvwxy/bash-lsgit/raw/master/lsgit.png "lsgit Screenshot")
