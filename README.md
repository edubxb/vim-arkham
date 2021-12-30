
![logo][logo]

> It's the colorscheme we set that defines us. *(Joker)*

[![main](https://github.com/edubxb/vim-arkham/workflows/main/badge.svg?branch=master)](https://github.com/edubxb/vim-arkham/actions?query=workflow%3Amain)

Arkham is a vim colorscheme based on [Gotham](whatyouhide/vim-gotham) but **even darker**. It works in vim or neovim.

![screenshot][screenshot]


## Installation

I moved to [vim-plug][vim-plug] a while ago and never looked back. Anyway, you
can install Arkham with whatever package manager you use. For example:

``` viml
" vim-plug
Plug 'edubxb/vim-arkham'
" NeoBundle
NeoBundle 'edubxb/vim-arkham'
" Vundle
Plugin 'edubxb/vim-arkham'
" dein.vim
call dein#add('edubxb/vim-arkham')
```

If you don't use a plugin manager just copy the content of `vim/colors/` to
`~/.vim/colors`.

When you have the plugin installed, you can set it in your `vimrc`:

``` viml
colorscheme arkham
```

### Color Palette


| Color Base    | Hex           | Other Colors  | Hex           |
| ------------- | ------------- | ------------- | ------------- |
| Base 0        | `#0c1014`     | Red           | `#c23127`     |
| Base 1        | `#11151c`     | Orange        | `#d26937`     |
| Base 2        | `#091f2e`     | Yellow        | `#edb443`     |
| Base 3        | `#0a3749`     | Magenta       | `#888ca6`     |
| Base 4        | `#245361`     | Violet        | `#4e5166`     |
| Base 5        | `#599cab`     | Blue          | `#195466`     |
| Base 6        | `#99d1ce`     | Cyan          | `#33859E`     |
| Base 7        | `#d3ebe9`     | Green         | `#2aa889`     |


## Contributing

All forms of contribution are welcome: bug reports, bug fixes, pull requests and
simple suggestions. Thanks!

### List of contributors

You can find the list of contributors [here][contributors].


## License

MIT &copy; 2021 Eduardo Bellido Bellido, see [the license][license-file].


[logo]: https://i.imgur.com/szikQ8b.png "Logo"
[screenshot]: http://i.imgur.com/NfRuHFN.png "A vim screenshot"
[license-file]: LICENSE.txt

[vim-plug]: https://github.com/junegunn/vim-plug
[contributors]: https://github.com/edubxb/vim-arkham/graphs/contributors
