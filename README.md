# rmsafe

Python tool to move files and/or directories to macOS Trash.

## Usage

`$ rmsafe [-h] [path [path ...]]`

+ `path`: pathname pattern of file or directory (e.g. *.pdf)
+ `-h`, `--help`: show this help message and exit

## Installation

### Homebrew

```bash
$ brew tap snoopython/formulae
$ brew install rmsafe
```

### Download ZIP

You can also download a ZIP and use bin/rmsafe as you like!

## Requirements

rmsafe is literally a tool for macOS and OS X
because it depends on system AppleScript and Python (>= 2.7)
so that things can be *put back* from macOS Trash.
