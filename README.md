config-files
============

Base of my config files vimrc,etc

## Installation

Using ansible:
```bash
ansible-playbook -i "localhost," -c local vim.yaml
```

## Manual Installation
```bash
git submodule init
git submodule update
```
Than create symlinks for:
vim/vimconf.vimrc -> ~/.vimrc
vim/vimrc.first -> ~/.vimrc.first
vim/vimrc.last -> ~/.vimrc.last
vim/vimrc.plugins -> ~/.vimrc.plugins

Next run vim and do:
```vim
:PluginInstall
```


## Additional programs needed:
python-jedi
python3-jedi
exuberant-ctags
