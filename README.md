# VSCode Settings
All of the Setup I use for VSCode

##Themes

##Extensions

## Settings
'''
{
  "workbench.colorTheme": "Default Dark+",
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
'''


##Keybindings
'''
// Place your key bindings in this file to override the defaults
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
'''
