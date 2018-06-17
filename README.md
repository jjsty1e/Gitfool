# Gitfool

Gitfool (or Gitfull) is a shell command for you to fulfill your git commit log.

> Gitfool is a trick, take care of what you are doing.

![](gitfool.png)

## USAGE

```bash
./gitfool [repo_path] [days] --push
```

**repo_path**

the repository path you want to add commits

**days**

the days you wish to add these commits

**--push**

with this option, Gitfool will push the commits to remote (execute `git push`)

> don't use `sh gitfool` syntax, and it will report an error.

## EXAMPLE

```bash
./gitfool ~/Code/acme 365 --push
```

## WARNING

you may be reported for abusing if you push these commits to Github.