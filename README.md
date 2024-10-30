---
title: Clean up older revisions of snaps
---
# SnapClean

This is a script that uninstalled the old versions of snaps to recover space

It works by filtering out snaps that are disabled and removing them by revision number

## Installation

This is just an awk script, as such installation relatively simple~
- Download the code

[![download](https://raw.githubusercontent.com/Fuseteam/linus-proof/main/images/download.png)](https://github.com/fuseteam/snapclean/releases/latest/download/snapclean.zip)

- open a terminal
- run `unzip Downloads/snapclean.zip -d snapclean`
- run `snapclean/snapclean setup`
- ???
- profit

## Usage

- simply run the command and let it do its magic:
```
snapclean
```
