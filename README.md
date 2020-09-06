# VsCode-Like-Vim-Setting

## How to config

1. Install neovim and termial tool:
```bash
brew install neovim fzf fd lazygit
```

2. Install vim-plugins  :

```bash
sh -c 'curl -fLo "${XDG_DATA_HOME:-$HOME/.local/share}"/nvim/site/autoload/plug.vim --create-dirs \
       https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim'
```

Use this command to fix if the termial complains the network issue:

```
echo "199.232.28.133 raw.githubusercontent.com" >> /etc/hosts 
````

3. Install ranger:
```bash
pip3 install ranger-fm pynvim
```

4. Replace the vim setting file and  ranger-setting file

* Copy the `init.vim` and `coc-setting.json` to the `~/.config/nvim`

* Copy the `ranger` floder to the `~./config`

5. Install Vim Plugins and Coc plugins

Go into the nvim editor and switch to the command mode:

```bash
//Install vim plugins
:PluginsIntall
//Install the coc plugin
:CocInstall coc-rust-analyzer coc-snippets coc-git coc-floaterm
```
