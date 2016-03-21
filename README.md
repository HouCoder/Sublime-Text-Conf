# Sublime-Text-Conf for OS X

Configuration for [Sublime Text 2](http://www.sublimetext.com/2).

## Setup

Follow [the instruction](https://packagecontrol.io/installation#st2) install the Package control for Sublime text 2.

Once you installed Package Control, close Sublime text and run following commands:

```shell
# Clone repo
$ git clone https://github.com/HouCoder/Sublime-Text-Conf.git ~/.Sublime-Text-Conf

# Backup your current settings
$ mv ~/Library/Application\ Support/Sublime\ Text\ 2/Packages/User ~/Library/Application\ Support/Sublime\ Text\ 2/Packages/User.original

# Create symbol link
$ ln -s ~/.Sublim-Text-2-Conf ~/Library/Application\ Support/Sublime\ Text\ 2/Packages/User
```

Then re-open Sublime Text again, after the Package Control completes install all plugins, it's all done.

## Installed plugins

- [Alignment](http://wbond.net/sublime_packages/alignment)
- [Better CoffeeScript](https://github.com/aponxi/sublime-better-coffeescript)
- [ColorHighlighter](https://github.com/Monnoroch/ColorHighlighter)
- [EditorConfig](https://github.com/sindresorhus/editorconfig-sublime)
- [Emmet](https://github.com/sergeche/emmet-sublime)
- [Jade](https://github.com/davidrios/jade-tmbundle)
- [LESS](https://github.com/danro/Less-sublime)
- [Markdown Extended](https://github.com/jonschlinkert/sublime-markdown-extended)
- [Theme - Afterglow](https://github.com/YabataDesign/afterglow-theme)
- [TypeScript](https://github.com/Microsoft/TypeScript-Sublime-Plugin)
- [Syntax Highlighting for Sass](https://github.com/P233/Syntax-highlighting-for-Sass)

## Keyboard Shortcuts

There are some useful default shortcuts in here: [Sublime Text 2 - Useful Shortcuts](https://gist.github.com/lucasfais/1207002#file-gistfile1-textile)

### Plugin related shortcuts:

**Alignment**

<kbd>Command</kbd> + <kbd>Shift</kbd> + <kbd>L</kbd> triggers the Alignment plugin.
