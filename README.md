# truedark256-vim

Fork of bratpeki's [truedark-vim](https://github.com/bratpeki/truedark-vim) vim color scheme.

I like original implementation, but i dont want to install iterm on my mac to have true color support. Since original scheme is literally in 256 colors but in hex codes - I forked it.

This colorscheme now also works in Neovim.

- Vim keeps the original `t_Co=256` behavior.
- Neovim disables `termguicolors` while the scheme is active so the existing `cterm` highlights render correctly.

