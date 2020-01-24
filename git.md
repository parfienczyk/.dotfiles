# ~/.gitconfig

Edit file `vim ~/.gitconfig`

```
[alias]
  st = status
  br = branch
  co = checkout
  ls = ls-files
  lol = log --graph --decorate --pretty='format:%C(yellow)%h%Cgreen%d%Creset %s %C(white) (%an, %ar)%Creset' --abbrev-commit
  today = log --stat --since='1 Day Ago' --graph --pretty=oneline --abbrev-commit --date=relative
  undo = reset --soft HEAD^
  amend = commit --amend
  unstage = reset HEAD
  ctags = !.git/hooks/ctags
  commits-per-user = shortlog -s -n
  fr = "!f() { git fetch && git rebase origin/"$1"; }; f"
  cleanup = "!f() { git fetch -p && for branch in `git branch -vv --no-color | grep ': gone]' | awk '{print $1}'`; do git branch -D $branch; done; }; f"
```
