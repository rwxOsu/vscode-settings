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
  "workbench.colorTheme": "Tokyo Night",
  "window.zoomLevel": 0,
  "editor.fontSize": 20,
  "editor.mouseWheelZoom": true,
  "editor.suggest.snippetsPreventQuickSuggestions": false,
  "editor.suggest.insertMode": "replace",
  "editor.formatOnSave": true,
  "editor.codeActionsOnSave": {
    "source.fixAll": true,
    "source.sortImports": true
  },
  "workbench.iconTheme": "vscode-icons",

  "typescript.suggest.paths": false,
  "javascript.suggest.paths": false,

  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "explorer.autoReveal": true,

  "liveServer.settings.CustomBrowser": "firefox",
  "liveServer.settings.NoBrowser": false,
  "liveServer.settings.ChromeDebuggingAttachment": true,
  "liveServer.settings.donotShowInfoMsg": true
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
