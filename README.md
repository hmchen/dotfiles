dotfiles.git
============

[Generating SSH Keys](https://help.github.com/articles/generating-ssh-keys)

Clone this on a new Mac
```sh
cd ~/
git clone git@github.com:hmchen/dotfiles.git
```

Setup git
```sh
ln -s dotfiles/.gitignore_global .
git config --global core.excludesfile ~/.gitignore_global
git config --global user.name "Your Name"
git config --global user.email you@example.com
```

Setup bash
```sh
ln -s dotfiles/.bash_profile .
ln -s dotfiles/.bashrc .
ln -s dotfiles/.bashrc_custom .
```
