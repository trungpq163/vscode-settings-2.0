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
  "editor.letterSpacing": 0.5,
  "editor.fontLigatures": true,
  "editor.fontWeight": "normal",
  "editor.lineHeight": 26, // 24
  "editor.fontFamily": "OperatorMonoSSmLig-Light",
  "workbench.colorCustomizations": {
    "statusBar.background": "#0d0e0f",
    "statusBar.noFolderBackground": "#0d0e0f",
    "statusBar.debuggingBackground": "#0d0e0f",
    "contrastBorder": "#1A1C231A",
    // change color cursor
    "editorCursor.foreground": "#cccccc"
  },
  // setting Vibracy
  "vscode_vibrancy.opacity": 0,
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
  // eslint
  "eslint.format.enable": true,
  // auto open new tab in vscode
  "workbench.editor.enablePreview": false,
  // disable warning plint
  "python.pythonPath": "/Users/quoctrung163/opt/miniconda3/envs/tensorflow/bin/python",
  "python.linting.pylintPath": "venv/bin/pylint",
  // Editor Tweak
  "files.eol": "\n",
  "editor.tabSize": 2,
  "editor.insertSpaces": true,
  "editor.renderWhitespace": "none",
  // TS lint
  "tslint.autoFixOnSave": true,
  // Git Lens
  "gitlens.advanced.messages": {
    "suppressShowKeyBindingsNotice": true
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
  // System
  "window.zoomLevel": 0,
  "editor.detectIndentation": false,
  "editor.multiCursorModifier": "ctrlCmd",
  "editor.formatOnPaste": true,
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
    "env*": true
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
  "liveServer.settings.donotShowInfoMsg": true,
  "terminal.integrated.rendererType": "dom",
  "editor.formatOnType": true,
  "editor.formatOnSave": true,
  "terminal.integrated.inheritEnv": false,
  "workbench.colorTheme": "CodeSandbox",
  "files.associations": {
    "*.extension": "html"
  },
  "workbench.iconTheme": "vscode-seedling-icon-theme",
  "background.enabled": true
}
```

