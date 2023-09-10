# configurations
In this repo you can find my configuration files for zsh, p10k, nvim and more

# ZSH AND OH-MY-ZSH INSTALLATION
Use use these commands in the following order
```
sudo apt install zsh;
```
```
sudo apt install git wget // if you haven't git
```
```
chsh -s $(which zsh) // changes your default shell
```
```
reboot // reboot your PC for confirming changes
```

```
wget https://github.com/robbyrussell/oh-my-zsh/raw/master/tools/install.sh -O - | zsh
```
```
cp ~/.oh-my-zsh/templates/zshrc.zsh-template ~/.zshrc // copying template of oh-my-zsh file to your home catalogue
```

# P10K installation
For p10k installation, you should use next commands in terminal:
```
git clone --depth=1 https://gitee.com/romkatv/powerlevel10k.git ~/powerlevel10k
echo 'source ~/powerlevel10k/powerlevel10k.zsh-theme' >>~/.zshrc
```
If you want further config of p10k, use
```
p10k configure
```

For reloading p10k and loading changes maded, use
```
p10k reload
```
