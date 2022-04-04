# dev-machine-setup
This is a quick checklist for setting up a machine

# iTerm

- ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
- brew cask install iterm2
- brew install zsh
- sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
- git clone https://github.com/zsh-users/zsh-autosuggestions $ZSH_CUSTOM/plugins/zsh-autosuggestions
- add zsh-autosuggestions to: ~/.zshrc
- git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
- add zsh-syntax-highlighting to: ~/.zshrc

# z

- https://github.com/rupa/z
- brew install z
- add z to plugins in: ~/.zshrc

# Font:

- brew tap homebrew/cask-fonts
- brew cask install font-fira-code
- Navigate to ITerm2 | Preferences | Profiles | Text
- Change font to fira code
- Select Use Ligatures
- source ~/.zshrc to reload the terminal

