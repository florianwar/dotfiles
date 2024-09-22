# Dotfiles

My personal dotfiles provided as is and in a constant state of flux. Feel free to use them as a reference or copy them as you see fit.

## Tools used

- [Kitty](https://sw.kovidgoyal.net/kitty/) - Terminal emulator
- [Zsh](https://www.zsh.org/) - Shell
- [Neovim](https://neovim.io/) - Text editor

- [fzf](https://github.com/junegunn/fzf.vim) - Fuzzy finder
- [ripgrep](https://github.com/BurntSushi/ripgrep) - grep alternative
- [fdfind](https://github.com/sharkdp/fd) - find alternative
- [bat](https://github.com/sharkdp/bat) - cat alternative
- [zoxide](https://github.com/ajeetdsouza/zoxide) - directory navigation and autojumping
- [exa](https://github.com/ogham/exa) - ls alternative
- [yazi](https://github.com/sxyazi/yazi) - filemanager
- [Github Copilot](https://docs.github.com/en/copilot/github-copilot-in-the-cli/using-github-copilot-in-the-cli) - shell suggestions

- [lazygit](https://github.com/jesseduffield/lazygit) - git terminal UI
- [lazydocker](https://github.com/jesseduffield/lazydocker) - docker terminal UI
- [k9s](https://github.com/derailed/k9s) - kubernetes terminal UI

## Installation

Assuming you have [GNU Stow](https://www.gnu.org/software/stow/) installed, and cloned into ~/projects/dotfiles you can symlink the dotfiles to your home directory with the following command:

WARNING: This will overwrite any existing files in your home directory with the same name as the dotfiles.

```bash
stow -S --adopt -d ~/projects/personal -t ~ dotfiles
```

## Neovim

-> see the [dedicated repo](https://github.com/florianwar/nvim) for more information
