Koki Ota
The contents of .gitconfig

```sh
[alias]    
  ap = add --patch    
  df = diff    
  bb = branch    
  ss = status    
  st = stash    
  lg = log --graph    
  lo = log --oneline    
  lgo = log --graph --oneline    
  cc = checkout    
  cm = commit -m    
  co = commit    
  cp = cherry-pick    
  tt = log --graph --pretty=format:'%x09%C(auto) %h %Cgreen %ar %Creset%x09by "%C(cyan ul)%an%Creset" %x09%C(auto)%s %d'    
  ps  = push origin HEAD    
  psu = push origin -u HEAD    
  pl  = !git pull origin $(git rev-parse --abbrev-ref HEAD)  
```
