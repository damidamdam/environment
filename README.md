# Настройка окружения

## ITerm2
1) `brew install iterm2`
2) `sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"`
3) `brew install powerlevel10k`
4) `echo "source $(brew --prefix)/share/powerlevel10k/powerlevel10k.zsh-theme" >> ~/.zshrc`
5) `git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions`
6) `git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting`
7) Добавить в ~/.zshrc строку `plugins=(git zsh-autosuggestions zsh-syntax-highlighting)`


## NVIM
1) `brew install neovim`
2) Добавить скопировать содержимое папки nvim в ~/.config/nvim
3) Скачать [шрифт](https://github.com/ryanoasis/nerd-fonts/releases/download/v3.4.0/3270.zip)


