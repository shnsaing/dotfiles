# Kitty

```
curl -L https://sw.kovidgoyal.net/kitty/installer.sh | sh /dev/stdin
```

# Homebrew

```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

# Tools

```
brew install colima
brew install docker docker-compose docker-Buildx
brew install git
brew install neovim
brew install zsh
brew install --cask brave-browser
brew install --cask discord
brew install --cask obs
brew install --cask visual-studio-code
```

# Neovim plugin manager

```
git clone --depth 1 https://github.com/wbthomason/packer.nvim\
 ~/.local/share/nvim/site/pack/packer/start/packer.nvim
```

## Set .local directory ownership

```
sudo chown -R $USER ~/.local
```

# Oh My Zsh

```
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

## Install plugins

1. [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions/blob/master/INSTALL.md#oh-my-zsh)
2. [zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting/blob/master/INSTALL.md#oh-my-zsh)

# Powerlevel10k
## Install fonts

https://github.com/romkatv/powerlevel10k#meslo-nerd-font-patched-for-powerlevel10k

## Install theme

https://github.com/romkatv/powerlevel10k#oh-my-zsh

## Restart Zsh

```
exec zsh
```

# yabai

1. [Disable System Integrity Protection](https://github.com/koekeishiya/yabai/wiki/Disabling-System-Integrity-Protection)
2. Install with `brew install koekeishiya/formulae/yabai`
3. [Configure](https://github.com/koekeishiya/yabai/wiki/Installing-yabai-(latest-release)#configure-scripting-addition)
4. Start service with `yabai --start-service`

# skhd

```
brew install koekeishiya/formulae/skhd
skhd --start-service
```

# Docker

[macOS configuration](https://smallsharpsoftwaretools.com/tutorials/use-colima-to-run-docker-containers-on-macos/)
