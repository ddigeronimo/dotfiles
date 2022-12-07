# Installation
Run `chezmoi init https://github.com/$GITHUB_USERNAME/dotfiles.git`

# Favorite software

These are some of my favorite applications that I use day to day.

Ideally, these will be installed on a new machine before running the chezmoi install, but they aren't prerequisites.

Without them, some errors may get thrown as some of the configs in my dotfiles reference them.

For example, my .zshrc will try to source fzf config files that may not yet be installed.


bat https://github.com/sharkdp/bat

ripgrep https://github.com/BurntSushi/ripgrep

ranger https://github.com/ranger/ranger

fzf https://github.com/junegunn/fzf

fd https://github.com/sharkdp/fd

lazygit https://github.com/jesseduffield/lazygit

delta https://github.com/dandavison/delta

k9s https://github.com/derailed/k9s

glow https://github.com/charmbracelet/glow

lazydocker https://github.com/jesseduffield/lazydocker

# Configs not managed through Chezmoi

Currently, my [Vim](https://github.com/ddigeronimo/myvim), [Neovim](https://github.com/ddigeronimo/nvim), and [Emacs](https://github.com/ddigeronimo/.emacs.d) configs are all managed through separate GitHub repositories. I don't use these editors terribly often, so changes there are rare.
