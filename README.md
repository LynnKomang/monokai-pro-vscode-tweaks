# monokai-pro-vscode-tweaks
This repository contains settings that fix the annoying class coloring of new Monokai Pro versions after 1.1.14.

## The included changes:
- Green colored classes and interfaces
- Green colored React custom components
- Overall personal minor coloring changes

## Installation
1. Make sure to get the Monokai Pro theme from the [Visual Studio Code Marketplace](https://marketplace.visualstudio.com/items?itemName=monokai.theme-monokai-pro-vscode).
2. Once the extension is installed press `CTRL + SHIFT + P` and select the `Preferences: Open User Settings (JSON)` option.
3. Add to the end of the file the content of the [`settings.json`](https://github.com/LynnKomang/monokai-pro-vscode-tweaks/blob/master/settings.json) file (the `editor.tokenColorCustomizations` tag and its content).
4. That's it, Enjoy your improved Monokai Pro theme!

## Note
If you prefer the red custom components color and want to bring their original color back just remove from each `scope` tag in every theme in the file the following lines:
```json
"entity.name.tag support.class.component",
"entity.name.tag.js.jsx support.class.component.js.jsx"
```
