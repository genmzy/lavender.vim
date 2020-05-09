# space-vim-theme - Vim Colorscheme

<a href="https://github.com/liuchengxu/space-vim"><img src="https://rawgit.com/liuchengxu/space-vim/master/assets/space-vim-badge.svg" alt="badge"></a>

dark                                                                                  | light
:----:                                                                                | :----:
![](https://raw.githubusercontent.com/liuchengxu/img/master/space-vim-theme/dark.png) | ![](https://raw.githubusercontent.com/liuchengxu/img/master/space-vim-theme/light.png)

[kitty](https://github.com/kovidgoyal/kitty) with `set termguicolors`

[liuchengxu/space-vim-theme](https://github.com/liuchengxu/space-vim-theme) is a greet theme from sapceemacs, [986299679/space-vim-theme](https://github.com/986299679/space-vim-theme) is theme with less perference for bold and italic, just keep bold of javaDocTitle/vimDocTitle and TODOs.
Besides, I change [liuchengxu/space-vim-theme](https://github.com/liuchengxu/space-vim-theme) background to #282a36, which is also the background color of [snazzy](https://github.com/connorholyday/vim-snazzy) and [dracula](https://github.com/dracula/vim)

## Installation

Use [vim-plug](https://github.com/junegunn/vim-plug):

```vim
Plug '986299679/space-vim-theme'
```

```vim
" Recommand airline_theme, it's color is not my flavor, but this airline theme has strong compatibility for many vim themes.
let g:airline_theme='lucius'
set background=dark
colorscheme space_vim_theme
" Recommand comment color, but i don't want change the original comment color.
hi Comment guifg=#5C637f ctermfg=248
```

## Usage

```vim
colorscheme space_vim_theme

```

`:h space_vim_theme` for detailed information.

- [Colortemplate](https://github.com/lifepillar/vim-colortemplate)
- `templates` is based on [vim-gruvbox8](https://github.com/lifepillar/vim-gruvbox8)
