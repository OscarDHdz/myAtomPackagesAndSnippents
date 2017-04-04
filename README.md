# **JS Atom**

## **Atom Packages**

### Atom Must Have
```
apm file-icons imdone-atom advanced-open-file atom-beautify docblockr emmet keybinding-cheatsheet pigments sync-settings atom-alignment auto-detect-indentation autoclose-html autocomplete-css autocomplete-html browser-plus color-picker glowing-cursor highlight-line javascript-snippets  minimap minimap-highlight-selected open-recent quick-highlight  sort-lines toggle-quotes you-complete-me  active-power-mode markdown-preview markdown-scroll-sync dockblocker  selection-highlight

```
#### Sources
* [file-icons](https://atom.io/packages/file-icons)
* [imdone-atom](https://atom.io/packages/imdone-atom)
* [advanced-open-file](https://atom.io/packages/advanced-open-fil)
* [atom-beautify](https://atom.io/packages/atom-beautify)
* [docblockr](https://atom.io/packages/docblockr)
* [emmet](https://atom.io/packages/emmet)
* [keybinding-cheatsheet](https://atom.io/packages/keybinding-cheatsheet)
* [pigments](https://atom.io/packages/pigments)
* [sync-settings](https://atom.io/packages/sync-settings) - Sync Atom configs with GitHub
* [atom-alignment](https://atom.io/packages/atom-alignment) - Aligng Your code with square indentations
* [auto-detect-indentation](https://atom.io/packages/auto-detect-indentation)
* [autoclose-html](https://atom.io/packages/autoclose-html)
* [autocomplete-css](https://atom.io/packages/autocomplete-css)
* [autocomplete-html](https://atom.io/packages/autocomplete-html)
* [browser-plus](https://atom.io/packages/browser-plus) - Open browser inside atom
* [color-picker](https://atom.io/packages/color-picker)
* [glowing-cursor](https://atom.io/packages/glowing-cursor)
* [highlight-line](https://atom.io/packages/highlight-line)
* [javascript-snippets](https://atom.io/packages/javascript-snippets)
* [minimap-highlight-selected](https://atom.io/packages/minimap-highlight-selected)
* [open-recent](https://atom.io/packages/open-recent)
* [quick-highlight](https://atom.io/packages/quick-highlight)
* [selection-highlight](https://atom.io/packages/selection-highlight)
* [sort-lines](https://atom.io/packages/sort-lines)
* [toggle-quotes](https://atom.io/packages/toggle-quotes)
* [you-complete-me](https://atom.io/packages/you-complete-me)
* [active-power-mode](https://atom.io/packages/active-power-mode) - Combo and Window Earthquake
* [markdown-preview](https://atom.io/packages/markdown-preview)
* [markdown-scroll-sync](https://atom.io/packages/markdown-scroll-sync)


### Git

```
apm install git-time-machine merge-conflicts
```
#### Sources
* [git-time-machine](https://atom.io/packages/git-time-machine) - See Side by Side with timeline commits
* [merge-conflicts](https://atom.io/packages/merge-conflicts) - Handle with merge conflicts by UI at Atom

### Angular 2

#### One Line
 ```
 apm install angular-2-typeScript-snippets atom-bootstrap3 atom-typescript  platformio-ide-terminal v-bootstrap4 autocomplete-js-import file-icons linter
 ```
###### platformio-ide-terminal
Let Atom open in-terminals
![TerminalCap](./img/terminal.png)

###### autocomplete-js-import
Let Atom suggest autocomplete while importing modules.   
It needs this configuration:
![Imports](./img/imports.png)

## **Atom Snippets**

### Log formatted JSON Object
```
'JSON.log':
  'prefix': 'JSONlog'
  'body': 'console.log( JSON.stringify(${1:data}, undefined, 2) );'
```

### Let Node log with colors
```
'log.cyan':
  'prefix': 'log.cyan'
  'body': 'console.log("\x1b[36m%s\x1b[0m", ${1:message});'

'log.green':
  'prefix': 'log.green'
  'body': 'console.log("\x1b[32m%s\x1b[0m", ${1:message});'

'log.red':
  'prefix': 'log.red'
  'body': 'console.log("\x1b[31m%s\x1b[0m", ${1:message});'

'log.yellow':
  'prefix': 'log.yellow'
  'body': 'console.log("\x1b[33m%s\x1b[0m", ${1:message});'
```
