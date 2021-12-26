
![logo][logo]

> It's the colorscheme we set that defines us. *(Batman)*

[![main](https://github.com/edubxb/vim-arkham/workflows/main/badge.svg?branch=master)](https://github.com/edubxb/vim-arkham/actions?query=workflow%3Amain)

Arkham is a vim colorscheme based in [Gotham](whatyouhide/vim-gotham) but **even darker**. It works in vim or neovim.

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

#### Terminal vim and 256 colors version

If you want to use Arkham in terminal vim, you should consider setting Arkham as
the colorscheme of your terminal emulator too. See the [relevant
section](#other).

If you're fine with not-so-faithful colors, a 256 colors version of Arkham is
available. To use it, just replace `arkham` with `arkham256` in your `vimrc`:

``` viml
colorscheme arkham256
```

Using `arkham256` (given that your terminal supports 256 colors) ensures that
the colors in vim are fixed and don't depend on the colorscheme of the terminal
emulator.

**Please**, use the 256 colors version only if you know what you're doing since
it looks "rougher" than the regular version.

#### Airline

Arkham supports [vim-airline][vim-airline] out of the box. When you use the
Arkham colorscheme, Airline should be able to pick it up and use it. If you want
to set it manually, you can use the `AirlineTheme` command for both the regular
version and the 256 colors version:

    :AirlineTheme arkham
    :AirlineTheme arkham256

Arkham by default emphasises the usage of insert mode by using a distinctive bright yellow color in
the airline mode segment. To change the color used for insert mode to a darker less emphasised color
add the following to your vimrc:

```viml
let g:arkham_airline_emphasised_insert = 0
```

#### Lightline

Arkham supports [lightline.vim][lightline.vim] too. To enable the colorscheme,
add one of the following lines to your `.vimrc`:

``` viml
let g:lightline = { 'colorscheme': 'arkham' }
let g:lightline = { 'colorscheme': 'arkham256' }
```

### <a name=other></a>Other

Arkham is available for other platforms too. If you want terminal vim to look as
good as GUI vim, you have to install the Arkham colorscheme for your terminal
emulator too.


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
[arkham-contrib]: https://github.com/edubxb/arkham-contrib
[vim-airline]: https://github.com/bling/vim-airline
[lightline.vim]: https://github.com/itchyny/lightline.vim
[contributors]: https://github.com/edubxb/vim-arkham/graphs/contributors
