## My VS Code Settings :heart:
### Demo
![](https://i.imgur.com/bNCPkyQ.png)

### <3
- Font: OperatorMonoLigLight
- Theme: CodeSandbox
- Icon: Seedling Icon Theme

### Extention
- Atom One Dark Theme
- Auto Close Tag
- Babel Javascript
- Beautify css/sass/scss/less
- Better Comment
- Bracket Pair Colorize2
- CodeSandBox theme
- DotENV
- Elm Emmet
- ESLint
- GitLens - Git supercharged
- Live Server
- Markdown Preview Enhanced
- Path Intellisense
- Python
- Python for Vscode
- Seedling Icon Theme
- TSLint
- Vetur
- Vibrancy
- background

```json
{
    "editor.fontSize": 14,
    "editor.fontFamily": "OperatorMonoSSmLig-Light",
    "editor.letterSpacing": 0.05,
    "editor.fontLigatures": true,
    "editor.fontWeight": "100",
    "editor.lineHeight": 28,
    // version default
    // "workbench.colorCustomizations": {
    //   // 1 for codesandbox theme
    //   "statusBar.background": "#202123",
    //   // change color cursor
    //   "editorCursor.foreground": "#cccccc",
    //   // line :D
    //   // "editor.lineHighlightBorder": "#1C1F26",
    //   // "editor.lineHighlightBackground": "#1C1F26",
    //   "editor.lineHighlightBackground": "#03030300",
    //   "editor.lineHighlightBorder": "#03030300",
    //   "editorBracketMatch.background": "#00000000",
    //   "editorBracketMatch.border": "#2a6a6e",
    //   //
    //   // "sideBarSectionHeader.background": "#1d2022",
    //   // "sideBarSectionHeader.foreground": "#ff0000",
    //   // "sideBar.border": "#00000000",
    //   // "list.hoverBackground": "#1d2022",
    //   "list.activeSelectionBackground": "#202123",
    //   // "list.highlightForeground": "#ff0000",
    //   // "list.focusBackground": "#ff0000",
    //   // "list.focusForeground": "#ff0000",
    //   // "list.deemphasizedForeground": "#ff0000",
    //   "list.inactiveSelectionBackground": "#202123",
    // },
    // version 0 - horizon
    // "workbench.colorCustomizations": {
    //     "editorCursor.foreground": "#cccccc",
    //     "tab.activeBorder": "#A8A9A9",
    //     // line :D
    //     "editor.lineHighlightBorder": "#1c1f2600",
    //     "editor.lineHighlightBackground": "#1c1f2600",
    // },
    // version 1 - codesandbox
    "workbench.colorCustomizations": {
        // 1 for codesandbox theme
        "statusBar.background": "#111518",
        "statusBar.noFolderBackground": "#111518",
        "statusBar.debuggingBackground": "#111518",
        // "statusBar.noFolderBackground": "#0d0e0f",
        // "statusBar.debuggingBackground": "#0d0e0f",
        // "contrastBorder": "#1A1C231A",
        // change color cursor
        "editorCursor.foreground": "#cccccc",
        // line :D
        // "editor.lineHighlightBorder": "#1C1F26",
        // "editor.lineHighlightBackground": "#1C1F26",
        // for glass
        "editor.lineHighlightBackground": "#00000000",
        "editor.lineHighlightBorder": "#00000000",
        //
        // "list.hoverBackground": "#1C2022",
        // "list.activeSelectionBackground": "#1C2022",
        // "list.inactiveSelectionBackground": "#1C2022",
        // tab
        "tab.activeBackground": "#00000000",
        // "tab.unfocusedActiveBorder": "#1C2022",
        // "tab.inactiveBackground": "#1C2022",
        // "tab.border": "#1C2022",
        // "tab.activeBorderTop": "#715959",
        // "tab.inactiveModifiedBorder": "#1C2022",
        // color tab
        "tab.activeBorder": "#A8A9A9",
        // "tab.activeForeground": "#ff0000",
        //
        // "panelTitle.activeBorder": "#A8A9A9",
        // "editorWidget.foreground": "#161a1d",
        // suggest
        // "editorWidget.background": "#161a1d",
        // "editorSuggestWidget.background": "#ff0000"
        // "editorSuggestWidget.selectedBackground": "#22282c",
        // FOR GLASS //
        // "editorBracketMatch.background": "#00000000",
        // "editorBracketMatch.border": "#2a6a6e",
        // //
        // "sideBarSectionHeader.background": "#1d2022",
        // // "sideBarSectionHeader.foreground": "#ff0000",
        // //
        // "sideBar.border": "#00000000",
        // "list.hoverBackground": "#1d2022",
        // "list.activeSelectionBackground": "#1d2022",
        // FOR GLASS //
        // "list.activeSelectionForeground": "#e34242",
        // "list.highlightForeground": "#ff0000",
        // "list.focusBackground": "#ff0000",
        // "list.focusForeground": "#ff0000",
        // "list.deemphasizedForeground": "#ff0000",
        "list.inactiveSelectionBackground": "#1d2022",
    },
    // setting Vibracy
    "vscode_vibrancy.opacity": 0.0,
    "editor.semanticHighlighting.enabled": false,
    //fase
    // emmet config
    "emmet.syntaxProfiles": {
        "javascript": "jsx"
    },
    "emmet.includeLanguages": {
        "vue-html": "html",
        "javascript": "javascriptreact"
    },
    "emmet.triggerExpansionOnTab": true,
    // auto open new tab in vscode
    "workbench.editor.enablePreview": false,
    // disable warning plint
    // "python.linting.pylintPath": "venv/bin/pylint",
    // Editor Tweak
    "files.eol": "\n",
    "editor.insertSpaces": true,
    "editor.renderWhitespace": "none",
    // TS lint
    "tslint.autoFixOnSave": true,
    // Git Lens
    "gitlens.advanced.messages": {
        "suppressGitMissingWarning": true,
    },
    "gitlens.hovers.enabled": false,
    "gitlens.codeLens.enabled": false,
    "gitlens.statusBar.enabled": false,
    "gitlens.currentLine.enabled": false,
    "gitlens.blame.heatmap.enabled": false,
    "gitlens.mode.statusBar.enabled": false,
    "gitlens.blame.highlight.enabled": false,
    "gitlens.hovers.currentLine.over": "line",
    // Vetur
    "vetur.format.defaultFormatter.ts": "prettier",
    "vetur.format.defaultFormatter.js": "prettier",
    "vetur.format.defaultFormatter.css": "prettier",
    "vetur.format.defaultFormatter.less": "prettier",
    "vetur.format.defaultFormatter.scss": "prettier",
    "vetur.format.defaultFormatter.postcss": "prettier",
    "vetur.format.defaultFormatter.stylus": "stylus-supremacy",
    "editor.detectIndentation": false,
    "editor.multiCursorModifier": "ctrlCmd",
    // performance vscode
    "telemetry.enableTelemetry": false,
    "files.exclude": {
        "**/.git": true,
        "**/.DS_Store": true,
        "**/.vscode": true,
        "**/__pycache__": true,
        "**/.pytest_cache": true,
        "**/node_modules": true,
        "node_modules": true,
        "venv": true,
        "*.sublime-*": true,
        "env*": true,
        "**/.classpath": true,
        "**/.project": true,
        "**/.settings": true,
        "**/.factorypath": true
    },
    "search.exclude": {
        "**/node_modules": true,
        "**/bower_components": true,
        "**/env": true,
        "**/venv": true
    },
    "files.watcherExclude": {
        "**/.git/objects/**": true,
        "**/.git/subtree-cache/**": true,
        "**/node_modules/**": true,
        "**/env/**": true,
        "**/venv/**": true,
        "env-*": true
    },
    "editor.semanticTokenColorCustomizations": {
        "enabled": true
    },
    "terminal.integrated.inheritEnv": false,
    "files.associations": {
        "*.extension": "html"
    },
    "workbench.iconTheme": "vscode-seedling-icon-theme",
    "background.enabled": true,
    // eslint
    "eslint.format.enable": true,
    "editor.codeActionsOnSave": {
        "source.fixAll": true
    },
    // Default Style BG
    // "background.style": {
    //   "content": "''",
    //   "pointer-events": "none",
    //   "position": "absolute",
    //   "z-index": "99999",
    //   "width": "100%",
    //   "height": "100%",
    //   "background-position": "100% 100%",
    //   "background-repeat": "no-repeat",
    //   "opacity": 1
    // },
    "background.useDefault": true,
    "editor.suggestSelection": "first",
    "vsintellicode.modify.editor.suggestSelection": "automaticallyOverrodeDefaultValue",
    "editor.linkedEditing": true,
    "window.restoreWindows": "none",
    "editor.formatOnSave": true,
    "editor.formatOnPaste": true,
    "editor.formatOnType": true,
    "window.zoomLevel": 0.44,
    "window.titleBarStyle": "native",
    "workbench.colorTheme": "CodeSandbox",
    "workbench.productIconTheme": "fluent-icons",
    "workbench.editorAssociations": {
        "*.ipynb": "jupyter.notebook.ipynb"
    },
    "editor.inlineSuggest.enabled": true,
    "security.workspace.trust.untrustedFiles": "open",
    "cSpell.userWords": [
        "unstyled"
    ],
    "editor.tabSize": 2,
}
```

