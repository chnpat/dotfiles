# Installation for MacOS

## 1. Install CLI

1.1 Download and install CLI application like Ghostty or Wezterm (Personally I used WezTerm)

1.2 Ensure that the z-shell (zsh) is used, by using the command:
```sh
which $SHELL
```
If you’re using the z-shell, you should see the output as `/bin/zsh`. Otherwise, you need to set the z-shell as our default terminal by using the following command:

```sh
chsh -s $(which zsh)
```

If the z-shell is not already installed on your computer, you can install it using Homebrew with the following command:

```sh
brew install zsh
```

## 2. Set Up

2.1 To clone this repository to your home directory, use the following command:
```sh
git clone https://github.com/chnpat/dotfiles/zsh ~
```

2.2 Install all the necessary dependencies using Homebrew’s command as follows:

```sh
brew install neovim eza bat fd fzf zoxide starship ripgrep
```

2.3 Execute the configuration using the following command:

```sh
source ~/.config/zsh/.zshrc
```
