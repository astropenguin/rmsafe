# trash

trash is a simple Python tool to move files and/or directories to macOS Trash.

## Usage

`$ trash [-h] [path [path ...]]`

+ `path`: pathname pattern of file or directory (e.g. *.pdf)
+ `-h`, `--help`: show this help message and exit

## Installation

### Homebrew

```bash
$ brew tap snoopython/macos
$ brew install trash
```

### Download ZIP

You can also download a ZIP and use bin/trash as you like!

## Requirements

trash is literally a tool for macOS and OS X
because it depends on system AppleScript and Python (>= 2.7)
so that things can be *put back* from macOS Trash.