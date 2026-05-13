## Git Aliases

Add the following aliases to your Git config:

```ini
[alias]
  lg = log --color --graph --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset' --abbrev-commit --
  l = log --graph --all --pretty=format:'%C(yellow)%h%C(cyan)%d%Creset %s %C(white)- %an, %ar%Creset' -n 20
  gl = log --graph --all --pretty=format:'%C(yellow)%h%C(cyan)%d%Creset %s %C(white)- %an, %ar%Creset' -n 10
  a = add
  aa = add --all
  c = commit -m
  ca = commit --amend
  co = checkout
  cob = checkout -b
  cp = cherry-pick
  cpa = cherry-pick --abort
  cpc = cherry-pick --continue
  d = diff
  f = fetch
  fa = fetch --all
  m = merge
  p = pull
  pr = pull --rebase
  prp = pull --rebase=preserve
  rb = rebase
  rba = rebase --abort
  rbc = rebase --continue
  rbs = rebase --skip
  s = status
  rs = reset --hard
```


## Git Config Commands

```bash
git config --global alias.lg "log --color --graph --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset' --abbrev-commit --"
git config --global alias.l "log --graph --all --pretty=format:'%C(yellow)%h%C(cyan)%d%Creset %s %C(white)- %an, %ar%Creset' -n 20"
git config --global alias.gl "log --graph --all --pretty=format:'%C(yellow)%h%C(cyan)%d%Creset %s %C(white)- %an, %ar%Creset' -n 10"
git config --global alias.a "add"
git config --global alias.aa "add --all"
git config --global alias.c "commit -m"
git config --global alias.ca "commit --amend"
git config --global alias.co "checkout"
git config --global alias.cob "checkout -b"
git config --global alias.cp "cherry-pick"
git config --global alias.cpa "cherry-pick --abort"
git config --global alias.cpc "cherry-pick --continue"
git config --global alias.d "diff"
git config --global alias.f "fetch"
git config --global alias.fa "fetch --all"
git config --global alias.m "merge"
git config --global alias.p "pull"
git config --global alias.pr "pull --rebase"
git config --global alias.prp "pull --rebase=preserve"
git config --global alias.rb "rebase"
git config --global alias.rba "rebase --abort"
git config --global alias.rbc "rebase --continue"
git config --global alias.rbs "rebase --skip"
git config --global alias.s "status"
git config --global alias.rs "reset --hard"
```
