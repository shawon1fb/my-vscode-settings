{
  // "tabnine.experimentalAutoImports": true,
  // config related to code formatting
  // "editor.defaultFormatter": "esbenp.prettier-vscode",
  "editor.formatOnSave": true,
  "editor.fontFamily": "  'Maven Pro', 'Kiwi Maru Medium'  ,'Courgette' , 'Merienda' ",
  "editor.fontLigatures": true,
  "[javascript]": {
    "editor.formatOnSave": true,
    // "editor.defaultFormatter": null
  },
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": true,
    "source.organizeImports": true
  },
  "eslint.alwaysShowStatus": true,
  "eslint.validate": [
    "javascript"
  ],
  "eslint.format.enable": true,
  "workbench.iconTheme": "vscode-icons",
  "editor.fontSize": 18,
  "code-runner.runInTerminal": true,
  ///go lang 
  //"editor.codeActionsOnSave": null,
  "go.testOnSave": true,
  "go.lintOnSave": "package",
  "go.formatTool": "goimports",
  "go.testFlags": [
    "-v"
  ],
  "go.autocompleteUnimportedPackages": true,
  "[go]": {
    "editor.defaultFormatter": "golang.go",
    "editor.insertSpaces": false,
    "editor.formatOnSave": false,
    "editor.codeActionsOnSave": {
      "source.organizeImports": true
    },
    //   "editor.suggest.snippetsPreventQuickSuggestions": true
  },
  "gopls": {
    "formatting.gofumpt": true
  },
  "terminal.integrated.automationShell.windows": "C:\\Program Files\\Git\\bin",
  "[jsonc]": {
    "editor.defaultFormatter": "vscode.json-language-features"
  },
  "workbench.editor.enablePreview": false,
  ///terminal
  "terminal.integrated.fontFamily": "Fira Code",
  "workbench.colorCustomizations": {
    "terminal.background": "#1D2021",
    "terminal.foreground": "#A89984",
    "terminalCursor.background": "#A89984",
    "terminalCursor.foreground": "#A89984",
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
    "terminal.border": "#ff0000",
    "textLink.activeForeground": "#14012e"
  },
  "mssql.connections": [
    {
      "server": "{{put-server-name-here}}",
      "database": "{{put-database-name-here}}",
      "user": "{{put-username-here}}",
      "password": "{{put-password-here}}"
    }
  ]
}