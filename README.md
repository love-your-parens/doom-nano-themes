# Doom N Λ N O Themes

This package contains an attempt to replicate [N Λ N O
Theme](https://github.com/rougier/nano-theme) using Doom themes framework.
Hence, it can work properly when using Doom Emacs.

This is a personal fork that deviates in meaningful (breaking) ways from the upstream, but continues its goal of implementing the principles of the original _N Λ N O Theme_.

## Installation

First, copy the files to `~/.doom.d/themes/` or
`~/.config/doom/themes/` depending on your local setup.

If you are using Doom Emacs, add the following to your `config.el`:

```emacs-lisp
(setq doom-theme 'doom-nano-light))
```

or

```emacs-lisp
(setq doom-theme 'doom-nano-dark))
```

depending on the theme variant you like.

If you are not using Doom Emacs, just select the theme inside `use-package` call
as mentioned in [doom-themes documentation](https://github.com/doomemacs/themes).

## Screenshot

### Light theme

![Screenshot-Light](./screenshots/screenshot_light.png)

### Dark theme

![Screenshot-Dark](./screenshots/screenshot_dark.png)
