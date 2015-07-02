# Dotfiles for VIM/Conky/etc.

## F.A.Q.

Q: What i can find there?  
A: You can find there my settings for VIM/conky/etc. programms

Q: Can i steal this?  
A: Of course, you can use this easily

## How to install my VIM settings

1) Installing VIM lastest version (skip this step, if already installed):
```bash
sudo add-apt-repository ppa:fcwu-tw/ppa
sudo apt-get update
sudo apt-get install vim
```

2) Install [powerline-fonts](https://github.com/Lokaltog/powerline-fonts) for vim-airline

3) Install Vundle plugin
```bash
git clone https://github.com/gmarik/Vundle.vim.git ~/.vim/bundle/Vundle.vim
```

4) Clone my repository somewhere and copy settings:
```bash
git clone https://github.com/Relrin/dotfiles.git ~/Downloads/
cp -t ~/Downloads/dotfiles/vim/* ~/.vim/
mv ~/vim/.vimrc ~/
```

5) Run VIM and enter:
```bash
:PluginInstall
```

6) Restart VIM and get fun ;)

