## vimrc
Just an another Vimrc with minimal configuration 
## Clone the repo
```
git clone https://github.com/Mysthological/vimrc
```
# Install VimPlug 
==> for more info [junegunn/vim-plug](https://github.com/junegunn/vim-plug?tab=readme-ov-file).
```
curl -fLo ~/.vim/autoload/plug.vim --create-dirs \
    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
```
# copy hotkeys to ~/.vim
```
mv hotkey ~/.vim
```

# Install all plugins in Vim
`type "PlugInstall" in normal mode`

# For installing other extension : search CocInstall extension_name 
# For example:

# For using c++ :
`CocInstall coc-clangd` \
`CocCommand clang.install`

