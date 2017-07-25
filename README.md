# 01-setup

### Start Here
- https://c9.io/new

### Fill out UI
- Name: -Whatever you want-
- Public
- Template: Blank

### Ruby & Rails Setup
```
rvm install 2.4.1
rvm use 2.4.1
rvm gemset create alpha
rvm use 2.4.1@alpha --default
gem install rails pry
```

### Config Files
```
cd ~
rm .bash_aliases .gitconfig
wget https://raw.githubusercontent.com/chyld/devops/master/dotfiles/c9/.bash_aliases
wget https://raw.githubusercontent.com/chyld/devops/master/dotfiles/c9/.gitconfig
```

### Final
- Edit the `~/.gitconfig` file in your home directory
- Close all Terminal windows and reopen
