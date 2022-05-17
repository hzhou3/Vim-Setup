# Vim-Setup

#### 1. Vim Plug + Vim color

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



#### 2. Create ~/.vim/ and ~/.vim/colors/
#### 3. Copy ~/.vimrc and one of colors.vim downloaded
```sh
curl -fLo ~/.vimrc --create-dirs \
    https://raw.githubusercontent.com/hzhou3/Vim-Setup/main/.vimrc
```

```sh
curl -fLo ~/.vim/colors/color.vim --create-dirs \
    https://raw.githubusercontent.com/morhetz/gruvbox/master/colors/gruvbox.vim
```

#### 4. Do `:PlugInstall` in vim
