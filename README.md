# VSCode Settings
The setup I use for VSCode

## Themes
### Tokyo Night
Id: enkia.tokyo-night
Description: A clean Visual Studio Code theme that celebrates the lights of Downtown Tokyo at night.
Version: 0.9.8
Publisher: enkia
VS Marketplace Link: https://marketplace.visualstudio.com/items?itemName=enkia.tokyo-night

## Extensions
### Auto Rename Tag
Id: formulahendry.auto-rename-tag
Description: Auto rename paired HTML/XML tag
Version: 0.1.10
Publisher: Jun Han
VS Marketplace Link: https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag


## Settings
```json
{
  //Autosave
  "files.autoSave": "afterDelay",
  "files.autoSaveDelay": 1000,
  //Visuals
  "workbench.colorTheme": "GitHub Dark Default",
  "workbench.iconTheme": "material-icon-theme",
  //Editor
  "window.zoomLevel": 0,
  "editor.fontSize": 15,
  "editor.cursorSmoothCaretAnimation": "on",
  "editor.guides.bracketPairs": "active",
  "editor.mouseWheelZoom": true,
  "editor.stickyScroll.enabled": true,
  "editor.inlineSuggest.enabled": true,
  "editor.suggestSelection": "first",
  "editor.suggest.snippetsPreventQuickSuggestions": false,
  "editor.suggest.insertMode": "replace",
  "editor.formatOnSave": true,
  "editor.codeActionsOnSave": {
    "source.fixAll": true,
    "source.sortImports": true
  },
  "explorer.autoReveal": true,
  "workbench.editor.closeOnFileDelete": true,
  "workbench.list.smoothScrolling": true,
  "files.insertFinalNewline": true,
  "search.exclude": {
    "**/.git": true,
    "**/.github": true,
    "**/.nuxt": true,
    "**/.output": true,
    "**/.pnpm": true,
    "**/.vscode": true,
    "**/.yarn": true,
    "**/bower_components": true,
    "**/dist/**": true,
    "**/logs": true,
    "**/node_modules": true,
    "**/out/**": true,
    "**/package-lock.json": true,
    "**/pnpm-lock.yaml": true,
    "**/tmp": true,
    "**/yarn.lock": true
  },
  //Terminal
  "terminal.integrated.cursorBlinking": true,
  "terminal.integrated.cursorStyle": "line",
  "terminal.integrated.fontWeight": "300",
  "terminal.integrated.tabs.enabled": true,
  //Liveserver Extension
  "liveServer.settings.CustomBrowser": "firefox",
  "liveServer.settings.NoBrowser": false,
  "liveServer.settings.ChromeDebuggingAttachment": true,
  "liveServer.settings.donotShowInfoMsg": true,
}

```


## Keybindings
```json
[
    {
        "key": "ctrl+n",
        "command": "explorer.newFile",
        "when": "explorerViewletFocus"
    },
    {
        "key": "ctrl+shift+n",
        "command": "explorer.newFolder",
        "when": "explorerViewletFocus"
    },
    {
        "key": "ctrl+shift+n",
        "command": "workbench.action.newWindow",
        "when": "!explorerViewletFocus"
    }

]
```
