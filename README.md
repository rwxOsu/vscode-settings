# VSCode Settings
The setup I use for VSCode

## Themes
- Tokyo Night
- Tikode.VisualOS
- Community Material Theme
- Dark Horizon
- Material Icon Theme
- vscode-icons
- SynthWave '84
- Synthwave x Fluoromachine

## Extensions
- C/C++ by Microsoft
- Debug Visualizer
- CMake
- GitLens
- Output Colorizer
- Path Intellisense
- Prettier - Code formatter
- Project Manager
- WSL
- YAML
- ESLint
- HTML CSS Support
- HTMLHint
- htmltagwrap
- Import Cost
- Live Server
- Stylelint



## Settings
```json
{
    //Autosave
    "files.autoSave": "afterDelay",
    "files.autoSaveDelay": 1000,
    "editor.formatOnSave": true,
    "editor.codeActionsOnSave": {
        "source.fixAll": "explicit",
        "source.sortImports": "explicit"
    },
    //Visuals
    "workbench.iconTheme": "material-icon-theme",
    "security.workspace.trust.banner": "never",
    "workbench.colorTheme": "VisualOS",
    //Editor-Verhalten
    "editor.guides.bracketPairs": "active",
    "editor.cursorSmoothCaretAnimation": "on",
    "editor.mouseWheelZoom": true,
    "editor.unicodeHighlight.nonBasicASCII": false,
    "editor.stickyScroll.enabled": false,
    "editor.minimap.enabled": false,
    //Intellisense
    "editor.parameterHints.enabled": true,
    "editor.inlineSuggest.enabled": true,
    "editor.suggestSelection": "first",
    "editor.suggest.snippetsPreventQuickSuggestions": false,
    "editor.suggest.insertMode": "replace",
    "editor.linkedEditing": true,
    //Explorer
    "workbench.startupEditor": "newUntitledFile",
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
    //Theme Custom Settings
    "workbench.colorCustomizations": {
        "[VisualOS]": {
            "statusBar.background": "#193b61",
            "statusBar.noFolderBackground": "#193b61",
            "statusBar.debuggingBackground": "#193b61",
            "statusBar.foreground": "#ffffff",
            "activityBar.foreground": "#ffffff"
        }
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
