# vscode-settings

```json
{
  "workbench.colorTheme": "Cobalt2",
  "workbench.iconTheme": "material-icon-theme",
  "workbench.productIconTheme": "developer-icons",

  "editor.fontFamily": "cascadia code, JetBrains Mono, Fira Code, Operator Mono",
  "editor.fontLigatures": true,
  "editor.formatOnSave": true,
  "editor.wordWrap": "on",
  "editor.linkedEditing": true,
  "editor.selectionHighlight": true,
  "editor.fontSize": 16,
  "editor.fontWeight": "bold",
  "editor.experimentalInlineEdit.backgroundColoring": true,
  "editor.experimentalInlineEdit.enabled": true,
  "editor.cursorStyle": "line",
  "editor.acceptSuggestionOnCommitCharacter": true,
  "editor.acceptSuggestionOnEnter": "on",
  "editor.quickSuggestionsDelay": 10,
  "editor.suggestOnTriggerCharacters": true,
  "editor.tabCompletion": "off",
  "editor.suggestSelection": "first",
  "editor.wordBasedSuggestions": "matchingDocuments",
  "editor.formatOnPaste": true,
  "editor.formatOnType": true,
  "editor.smoothScrolling": true,
  "editor.scrollbar.verticalScrollbarSize": 6,
  "editor.scrollbar.horizontalScrollbarSize": 6,
  "editor.cursorSmoothCaretAnimation": "on",
  "editor.cursorBlinking": "expand",
  "editor.quickSuggestions": {
    "other": true,
    "comments": false,
    "strings": false
  },
  "editor.semanticTokenColorCustomizations": {
    "[Rouge]": {
      "enabled": true,
      "rules": {
        "*.declaration": { "bold": true }
      }
    }
  },
  "editor.tokenColorCustomizations": {
    "textMateRules": [
      {
        "scope": "comment",
        "settings": {
          "fontStyle": "bold"
        }
      }
    ]
  },

  "window.zoomLevel": 2,

  "liveServer.settings.donotVerifyTags": true,
  "liveServer.settings.donotShowInfoMsg": true,
  "liveServer.settings.CustomBrowser": "chrome",

  "cloudcode.duetAI.project": "prefab-setting-408017",
  "cloudcode.updateChannel": "Insiders",
  "cloudcode.duetAI.inlineSuggestions.enableAuto": true,
  "cloudcode.duetAI.languages": [
    "html",
    "json",
    "css",
    "git-commit",
    "javascript",
    "javascriptreact",
    "powershell",
    "typescript",
    "typescriptreact",
    "sass",
    "scss",
    "markdown"
  ],

  "gitlens.views.repositories.showIncomingActivity": true,
  "git.terminalGitEditor": false,
  "git.enableSmartCommit": true,
  "git.confirmSync": false,
  "git.autofetch": true,

  "tailwindCSS.colorDecorators": true,
  "tailwindCSS.suggestions": true,
  "tailwindCSS.includeLanguages": {
    "plaintext": "html"
  },

  "liveSassCompile.settings.watchOnLaunch": true,
  "liveSassCompile.settings.formats": [
    {
      "format": "expanded",
      "extensionName": ".css",
      "savePath": null,
      "savePathReplacementPairs": null
    }
  ],

  "javascript.suggest.autoImports": true,
  "javascript.suggest.enabled": true,
  "typescript.suggest.autoImports": true,
  "typescript.suggest.enabled": true,

  "html-css-class-completion.enableEmmetSupport": true,
  "html-css-class-completion.CSSLanguages": ["css", "sass", "scss"],
  "html-css-class-completion.JavaScriptLanguages": [
    "javascript",
    "javascriptreact",
    "typescriptreact"
  ],

  "background.customImages": ["https://i.postimg.cc/05WJbHbM/rihad.png"],
  "background.enabled": true,
  "background.useFront": true,
  "background.style": {
    "content": "''",
    "pointer-events": "none",
    "position": "absolute",
    "z-index": "99999",
    "width": "100%",
    "height": "100%",
    "margin-left": "0%",
    "background-position": "top",
    "background-size": "cover",
    "background-repeat": "no-repeat",
    "opacity": 0.2,
    "left": "0rem",
    "top": "0rem"
  },

  "prettier.enable": true,
  "prettier.semi": true,
  "prettier.trailingComma": "es5",
  "prettier.singleAttributePerLine": true,
  "prettier.withNodeModules": true,
  "editor.defaultFormatter": "esbenp.prettier-vscode",

  "[javascript]": {
    "editor.formatOnSave": true,
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },

  "[javascriptreact]": {
    "editor.formatOnSave": true,
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },

  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": "explicit",
    "source.fixAll.tslint": "explicit",
    "source.organizeImports": "explicit"
  },

  "settingsSync.ignoredSettings": [
    "terminal.integrated.macOptionClickForcesSelection"
  ],

  "terminal.integrated.fontFamily": "FiraCode Nerd Font",
  "terminal.integrated.fontWeight": "bold",
  "terminal.integrated.cursorStyle": "block",
  "terminal.integrated.fontSize": 16,
  "terminal.integrated.lineHeight": 1.3,
  "terminal.integrated.defaultProfile.windows": "PowerShell",
  "terminal.integrated.allowMnemonics": true,
  "terminal.integrated.smoothScrolling": true,
  "terminal.integrated.enableMultiLinePasteWarning": "auto",
  "terminal.integrated.cursorBlinking": true,
  "terminal.integrated.fontWeightBold": "bold",
  "terminal.integrated.copyOnSelection": true,
  "terminal.integrated.rightClickBehavior": "paste",
  "terminal.integrated.tabs.defaultIcon": "symbol-event",
  "terminal.integrated.tabs.defaultColor": "terminal.ansiYellow",
  "terminal.integrated.env.windows": {},

  "workbench.colorCustomizations": {
    "terminal.foreground": "#a09ced",
    "terminal.background": "#222335",
    "terminalCursor.background": "#ff0000",
    "terminalCursor.foreground": "#ffffff",
    "terminal.ansiBlack": "#1D2021",
    "terminal.ansiBlue": "#0D6678",
    "terminal.ansiBrightBlack": "#665C54",
    "terminal.ansiBrightBlue": "#0D6678",
    "terminal.ansiBrightCyan": "#8BA59B",
    "terminal.ansiBrightGreen": "#95C085",
    "terminal.ansiBrightMagenta": "#8F4673",
    "terminal.ansiBrightRed": "#FB543F",
    "terminal.ansiBrightWhite": "#FDF4C1",
    "terminal.ansiBrightYellow": "#FAC03B",
    "terminal.ansiCyan": "#8BA59B",
    "terminal.ansiGreen": "#95C085",
    "terminal.ansiMagenta": "#8F4673",
    "terminal.ansiRed": "#FB543F",
    "terminal.ansiWhite": "#A89984",
    "terminal.ansiYellow": "#FAC03B",
    " terminal.border": "#FAC03B",
    //"terminal.foreground": "#ffeee0",
    "terminal.selectionBackground": "#ff0000",
    //"activityBar.background": "#000",
    "activityBar.border": "#FAC03B",
    "activityBar.activeBorder": "#FAC03B",
    "panel.border": "#FAC03B",
    //"activityBar.activeBackground": "#ff0000",
    //"list.hoverBackground": "#a61414",
    //"sidebar.background": "#00ff9d5a",
    "sideBar.border": "#FAC03B",
    "sideBarTitle.foreground": "#FAC03B",
    "titleBar.active Foreground": "#fff",
    "titleBar.inactive Foreground": "#ffffffcc",
    // "titleBar.activeBackground": "#898d3f",
    //"titleBar.inactiveBackground": "#3F758DCC",
    // "editor.background": "#000",
    // "editor.selectionBackground": "#f2ff00",
    // "editor.selectionHighlightBorder": "#fbf300e0",
    "editor.findMatchBackground": "#f352fe8f",
    "editor.findMatchHighlightBackground": "#8e52fe9e",
    "editor.findMatchHighlightBorder": "#fbf300e0",
    "contrastBorder": "#FAC03B"
  },

  "emmet.useInlineCompletions": true,
  "emmet.showSuggestionsAsSnippets": true,
  "emmet.showExpandedAbbreviation": "always",
  "emmet.triggerExpansionOnTab": true,
  "files.associations": {
    "*html": "html",
    "*njk": "html",
    "*.ejs": "html"
  },
  "emmet.includeLanguages": {
    "javascript": "javascriptreact",
    "typescript": "typescriptreact",
    "vue-html": "html",
    "vue": "html",
    "razor": "html",
    "plaintext": "pug",
    "django-html": "html"
  },

  "css.enabledLanguages": ["html", "typescript", "javascript"],
  "css.styleSheets": [
    "https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css",
    "node_modules/bootstrap/dist/css/bootstrap.css",
    "app/${fileBasenameNoExtension}.css",
    "src/base-styles.js",
    "src/**/*.css",
    "src/**/*.scss"
  ],

  "better-comments.multilineComments": true,
  "better-comments.highlightPlainText": false,
  "better-comments.tags": [
    {
      "tag": "!",
      "color": "#FF2D00",
      "strikethrough": false,
      "underline": false,
      "backgroundColor": "transparent",
      "bold": false,
      "italic": false
    },
    {
      "tag": "?",
      "color": "#3498DB",
      "strikethrough": false,
      "underline": false,
      "backgroundColor": "transparent",
      "bold": false,
      "italic": false
    },
    {
      "tag": "//",
      "color": "#474747",
      "strikethrough": true,
      "underline": false,
      "backgroundColor": "transparent",
      "bold": false,
      "italic": false
    },
    {
      "tag": "todo",
      "color": "#FF8C00",
      "strikethrough": false,
      "underline": false,
      "backgroundColor": "transparent",
      "bold": false,
      "italic": false
    },
    {
      "tag": "*",
      "color": "#98C379",
      "strikethrough": false,
      "underline": false,
      "backgroundColor": "transparent",
      "bold": false,
      "italic": false
    }
  ],
  "code-runner.defaultLanguage": "javascript",
  "code-runner.executorMap": {
    "javascript": "node",
    "php": "C:\\php\\php.exe",
    "python": "python",
    "perl": "perl",
    "ruby": "C:\\Ruby23-x64\\bin\\ruby.exe",
    "go": "go run",
    "html": "\"C:\\Program Files (x86)\\Google\\Chrome\\Application\\chrome.exe\"",
    "java": "cd $dir && javac $fileName && java $fileNameWithoutExt",
    "c": "cd $dir && gcc $fileName -o $fileNameWithoutExt && $dir$fileNameWithoutExt"
  },

  "autoimport.doubleQuotes": true,
  "autoimport.absolute": true,

  "code-runner.runInTerminal": true,
  "code-runner.showExecutionMessage": false,

  "npm-intellisense.scanDevDependencies": true,
  "security.workspace.trust.untrustedFiles": "open",
  "explorer.confirmDelete": false,
  "auto-rename-tag.activationOnLanguage": ["*"],
  "reactSnippets.settings.prettierEnabled": true,
  "lifeline.swap": true,

  "editor.dragAndDrop": true,
  "explorer.confirmDragAndDrop": false,
  "powermode.enabled": true,
  "powermode.presets": "clippy",
  "powermode.shake.enabled": false,
  "quokka.automaticRestart": true,
  "quokka.colors": {
    "covered": "#62b455",
    "errorPath": "#ffa0a0",
    "errorSource": "#fe536a",
    "notCovered": "#cccccc",
    "partiallyCovered": "#d2a032"
  },
  "workbench.list.smoothScrolling": true,
  "powermode.combo.location": "statusbar"
}
```
