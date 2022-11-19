# Git commit browser for Kitty

This is to be a Git commit browser for [kitty](https://sw.kovidgoyal.net/kitty/).

Put git-hash-hints.py in ~/.config/kitty

Put the following in kitty.conf:

    map ctrl+shift+p>g kitten hints --customize-processing git-hash-hints.py