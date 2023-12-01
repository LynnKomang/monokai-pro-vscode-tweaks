# monokai-pro-vscode-tweaks
This repository contains settings that fix the annoying class coloring of new Monokai Pro versions after 1.1.14.

## Note
If you want to remove React custom components custom color just remove from each `scope` tag in every theme in the file the following lines:
```json
"entity.name.tag support.class.component",
"entity.name.tag.js.jsx support.class.component.js.jsx"
```
