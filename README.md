# base16-weechat

**the template isn't finished yet (more like haven't started :D) so bare with me**

This repository provide [base16][1] colorschemes for [weechat][2].

It is meant to be used along with the [new implementation][3] of base16 colorscheme
project, which propose a modular approach, by separating templates, schemes and
builder into different repositories.

### installation
Download the [theme.py][4] script to your `.weechat/python` directory and load it `/script load theme.py`.
Run `/theme installfile [absolute_path]` where absolute_path points to the chosen colorscheme in the `build_scheme` directory.

[1]: https://chriskempson.github.io/base16/
[2]: https://weechat.org/
[3]: https://github.com/chriskempson/base16A
[4]: https://weechat.org/files/temp/theme/theme.py
