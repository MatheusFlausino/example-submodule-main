# How to use Git Submodules

## Commands

### Add submodule
```bash
git submodule add git@github.com:Org/repo path_name
```
### Clone repo:
```bash
$ git clone --recursive git@github.com:Org/repo
```
OR
```bash
$ git clone git@github.com:Org/repo
$ git submodule update --init --remote
```

### Fetch update submodule
```bash
$ git submodule update --remote
```

## Git Submodules basic explanation

[gitaarik/git_submodules.md](https://gist.github.com/gitaarik/8735255)
