# zsh-aliases-lsd

## Why?

This zsh plugin enables a number of aliases for `lsd` a modern replacement for `ls`, I had previously used [zsh-aliases-exa](https://github.com/DarrinTisdale/zsh-aliases-exa) until recently swapping to `lsd` and at the time of writing couldn't find an oh-my-zsh plugin for `lsd`

## Installation

Make sure you have [lsd](https://github.com/Peltoche/lsd) installed

### Using an oh-my-zsh plugin manager (recommended)

```
# for antigen
antigen bundle 'yuhonas/zsh-aliases-lsd'

# for zplug
zplug 'yuhonas/zsh-aliases-lsd'

# for zgen
zgen load 'yuhonas/zsh-aliases-lsd'

# for fisher
fisher install yuhonas/zsh-aliases-lsd

# for omf
omf install https://github.com/yuhonas/zsh-aliases-lsd

```

### Manually

Clone the repository and source it in your shell's rc file.

Restart your zsh session, and the aliases will be available.

## What aliases does this add?

See [zsh-aliases-lsd.plugin.zsh](./zsh-aliases-lsd.plugin.zsh)

## Thanks

This project was forked from and heavily inspired by [zsh-alises-exa](https://github.com/DarrinTisdale/zsh-aliases-exa)

