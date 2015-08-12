# dotfiles
```
for i in `ls dotfiles`;do unlink ~/.${i}; rm -rf ~/.${i}; ln -s ~/dotfiles/${i} ~/.${i}; done
```
