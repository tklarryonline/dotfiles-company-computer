# Dotfiles for Company's computer
A minimal dotfiles setup for a new company's computer. This setup should use familiar tools and things from my dotfiles repo.

## Command-line Tools

### Homebrew

Follow the instructions on [brew.sh] and run this in terminal.

```sh
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

### iTerm2 and terminal

```sh
# Installs iTerm2
brew install --cask iterm2
```

#### Appearances

```sh
# Installs fonts
brew tap homebrew/cask-fonts
# Two of my favorite fonts
brew install --cask font-fira-code-nerd-font
brew install --cask font-jetbrains-mono-nerd-font
```
