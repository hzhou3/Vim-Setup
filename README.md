# Vim-Setup

#### 1. Vim Plug

###### Unix, Linux

```sh
curl -fLo ~/.vim/autoload/plug.vim --create-dirs \
    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
```

###### Windows (PowerShell)

```powershell
iwr -useb https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim |`
    ni $HOME/vimfiles/autoload/plug.vim -Force
```



#### 2. Create ~/.vim/
#### 3. Copy ~/.vimrc
#### 4. Do `:PlugInstall` in vim
