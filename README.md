# pwndbg-themes [![license](https://img.shields.io/github/license/mashape/apistatus.svg?maxAge=2592000)](https://github.com/pwndbg/pwndbg-themes/blob/master/LICENSE)

Collection of beautiful [pwndbg](https://github.com/pwndbg/pwndbg) themes.


## How?

The theme files can be sourced from `.gdbinit` after loading
[pwndbg](https://github.com/pwndbg/pwndbg).  Each theme is stored in a separate
folder and may contain sub variants (like a dark) and a screenshot.

Example:
```
source /usr/share/pwndbg/gdbinit.py
source /usr/share/pwndbg-themes/example/dark.pwndbg

set hexdump-bytes 128
```

## What?

Only theme related style options should be set, any usage of other config options
like the amount of printed lines (f.e. `set nearpc-lines 20`), screen clearing,
show flags or other behaviour should not be altered within a theme.
