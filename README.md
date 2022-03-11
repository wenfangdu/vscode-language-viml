<p align="center">
    <img height="200" src="https://github.com/XadillaX/vscode-language-viml/raw/master/assets/README.png" />
</p>

<p align="center">
    <a href="https://marketplace.visualstudio.com/items?itemName=XadillaX.viml">
        <img src="https://vsmarketplacebadge.apphb.com/version-short/XadillaX.viml.svg?style=for-the-badge&colorA=FF7800&colorB=CC5600&label=VS%20MARKETPLACE" />
    </a>
    <a href="https://marketplace.visualstudio.com/items?itemName=XadillaX.viml">
        <img src="https://vsmarketplacebadge.apphb.com/downloads-short/XadillaX.viml.svg?style=for-the-badge&colorA=5DDB61&colorB=4BC74F&label=DOWNLOADS" />
    </a>
    <a href="https://marketplace.visualstudio.com/items?itemName=XadillaX.viml">
        <img src="https://vsmarketplacebadge.apphb.com/rating-star/XadillaX.viml.svg?style=for-the-badge&colorA=FBBD30&colorB=F2AA08" />
    </a>
</p>

## What does this extension do?

[**VimL**](https://en.wikipedia.org/wiki/Vim_(text_editor)#Vim_script) (Also known as **Vim Language**, **VimScript**) support for [VSCode](https://code.visualstudio.com/).

Syntax Highlighting is synchronized from [Atom VimL](https://github.com/Alhadis/language-viml) with ❤ by [vscode-grammar-update-tool](https://github.com/XadillaX/vscode-update-grammar-tool).

Language Server Protocol depends on [vim-language-server](https://github.com/iamcco/vim-language-server).

> Thanks to [Alhadis/language-viml](https://github.com/Alhadis/language-viml), [iamcco/vim-language-server](https://github.com/iamcco/vim-language-server) and [XadillaX/vscode-update-grammar-tool](https://github.com/XadillaX/vscode-update-grammar-tool).

## Features

+ Language Server Protocol (Refer to [vim-language-server](https://github.com/iamcco/vim-language-server)):
  - Auto completion;
  - Function signature help;
  - Hover document;
  - Go to definition;
  - Go to references;
  - Document symbols;
  - Folding range;
  - Select range;
  - Rename;
  - Snippets;
  - Diagnostic;
+ Syntax highlighting for
  - **VimL files** (`*.vim`, `*.vimrc`, `_vimrc`, `*.gvimrc`, `*.ideavim`, `.ideavim`, `.ideavimrc`, `*.exrc`, etc);
  - **Vim Help files** (`*.txt` with matching a certain RegExp in file);
  - **Vim Snippet files** (`*.snip`, `*.snippet`, `*.snippets`, etc);
+ Syntax highlighting for embedding **Vim related syntaxes** (see above) in **Markdown files**.

## Contribution

Pull requests and Issues are welcomed.
