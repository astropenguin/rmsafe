# macos-trash

macos-trash is a Python tool to move files and/or directories to macOS Trash.
It executes AppleScript's `delete` command so that the trashed things can be *put back*.

## Usage

`$ macos-trash [-h] [path [path ...]]`

+ `path`: pathname pattern of file or directory (e.g. spam.txt, *.pdf)
+ `-h`, `--help`: show this help message and exit

## Installation

```bash
$ brew tap snoopython/macos
$ brew install macos-trash
```

## Requirements

macos-trash is literally a tool for macOS and OS X.
It depends on system AppleScript and Python (>= 2.7).
