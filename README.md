# First configuration MAC 2021

## Install programs with brew

[brew page](https://brew.sh/index_es)

## Install Brew
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

## Install Programs

[brew programs](https://formulae.brew.sh/)
```
brew install --cask google-chrome spotify github iterm2 postman visual-studio-code discord zoom slack
```

## Install zsh

[ohmyzsh](https://ohmyz.sh/)
```
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```
## Install NVM

```
brew install nvm
```
## Install and configuration Node LTS

* Open iterm2 and write the following code:
```
nvm install node --lts
```
* Then, We need to open the following file:
```
nano ~/.zshrc
```
* Add the following code inside and save it
```
export NVM_DIR=~/.nvm
 [ -s "$NVM_DIR/nvm.sh" ] && . "$NVM_DIR/nvm.sh"
 ```
* Finally, run the following code to save in terminal
 ```
source ~/.zshrc
```

## Add Alias to terminal

```
alias work="cd /Users/rafaelmogollon/Desktop/work"
```

## Install Powerlevel10k

[PowerLevel10k](https://github.com/romkatv/powerlevel10k)

* First, we need to clone the repository in our terminal
```
git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k
```
* Set PowerLevel10k in ~/.zshrc. Then, open this next file:

```
nano ~/.zshrc
```
* And we need to change the following code:
```
ZSH_THEME="powerlevel10k/powerlevel10k"
```

## Configuration VS CODE

* First, we need to download the following extension:
[Settings Sync](https://code.visualstudio.com/docs/editor/settings-sync)

* Also we need to link our account of github in this extension.

