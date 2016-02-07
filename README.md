[![License GPL 3][badge-license]](http://www.gnu.org/licenses/gpl-3.0.txt)

## About

gruvbox dark for GNU Emacs is a direct port of the popular
[gruvbox](https://github.com/morhetz/gruvbox) theme for vim, developed by Pavel
Pertsev.  It is my opinion that it's one of the finest low-contrast color themes
out there.

This theme uses the new built-in theming support available starting with Emacs
24.

## Installation

### Manual

Download `gruvbox-dark-theme.el` to the directory `~/.emacs.d/themes/`.  Add
this to your `.emacs`:

```lisp
(add-to-list 'custom-theme-load-path "~/.emacs.d/themes/")
```

Now you can load the theme with the interactive function `load-theme` like this:

`M-x load-theme RET gruvbox-dark`

### Using `package.el`

Not supported yet.

## Terminal users

Terminal users require a 256-color terminal with appropriate gruvbox colors.
See the
[gruvbox wiki](https://github.com/morhetz/gruvbox/wiki/Terminal-specific#a-256-color-gruvbox-palette-shellscript)
for details.

## Bugs and imporvements

Please, report any problems that you find on the projects integrated issue
tracker. If you've added some improvements and you want them included upstream
don't hesitate to send me a patch or even better -- a GitHub pull request.

In the future I will be adding suppor for more modes.  However, since I cannot
feasibly use and test all popular modes, contributions would be greatly
appreciated.  Additionally, I will be adding some customizations to the theme
(italic comments and/or strings among other things).

[badge-license]: https://img.shields.io/badge/license-GPL_3-green.svg
