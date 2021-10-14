# Lucius Colorscheme fro VSCode

This is an implementation of the *low contrast* profile of the [Lucius](https://github.com/jonathanfilip/vim-lucius) colorscheme for VSCode.
For some small details in syntax coloring, it deviates from the original because the syntax token categories are just different in VS code than in Vim.
Note that the implementation is still very premature and not at all final and polished.

For the moment, I only paid attention to rudimentarily support for C/C++ and LaTeX so I don't know how it looks on other languages.
I will adapt and extend the scheme as I go along.

## Install

Copy it into the `<user home>/.vscode/extensions` folder and restart Code.

At some point, I might publish this on the marketplace.

## TODO

* Add more languages
* Write a generator to also generate the other Lucius variants
