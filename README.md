This project was originally created by [boombuler](https://github.com/boombuler)

## Introduction

This is a simple snippet plugin for the [Micro](https://github.com/zyedidia/micro) editor.

The plugin comes with some snippet files which are taken from [vim-snippets](https://github.com/honza/vim-snippets)

Have a look at those repositories for their license and additional information!

Other [plugins](https://github.com/micro-editor/plugin-channel) for Micro editor

## Check which version of micro editor you have.

```bash
micro --version
```

## Install Snippet Plugin

### From Micro Version 1

<kbd>Ctrl</kbd> <kbd>e</kbd>

'plugin install snippets'

### From Micro Version 2

```bash
mkdir ~/.config/micro/plug
git clone -b micro-v2 https://github.com/tommyshem/micro-snippets-plugin.git ~/.config/micro/plug/snippets
```


When installed, to view the help file.

<kbd>Ctrl</kbd> <kbd>e</kbd>

`help snippets`
