nerdtree-ripgrep-plugin
====================

A really rough integration of `:ripgrep` with nerdtree. Adds a `'g'` menu item that
prompts the user for a search pattern to use with `:ripgrep`. `:ripgrep` is run on the
selected dir (using the parent if a file is selected).

Originally written by [scrooloose](https://gist.github.com/scrooloose/205807),
enhanced by [masaakif](https://gist.github.com/masaakif/414375).

## Installation

For Pathogen

`git clone https://github.com/mafflerbach/nerdtree-ripgrep-plugin.git ~/.vim/bundle/nerdtree-ripgrep-plugin`

Now reload `vim`.

For Vundle

```
Plugin 'scrooloose/nerdtree'
Plugin 'mafflerbach/nerdtree-ripgrep-plugin'
```

For NeoBundle

```
NeoBundle 'scrooloose/nerdtree'
NeoBundle 'mafflerbach/nerdtree-ripgrep-plugin'
```

For Plug
```
Plug 'scrooloose/nerdtree'
Plug 'mafflerbach/nerdtree-ripgrep-plugin'
```
