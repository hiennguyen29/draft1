Review recording project 13 for flex the menu bar 
old code:
```
// Style the header
header {
  background-color: v.$background-colour;
  padding: 30px;
  text-align: center;
  margin-bottom: 30px;

  // style the logo
  .menu-logo {
    text-decoration: none;
    color: v.$white;
    font-size: 1.5em;
  }
}
```


**My JSON setttings - maybe something wrong**
```
{
  "window.zoomLevel": 1,
  "editor.fontSize": 13,
  "workbench.iconTheme": "vscode-icons",
  "editor.wordWrap": "on",
  "prettier.bracketSameLine": true,
  "prettier.singleAttributePerLine": false,
  "liveServer.settings.donotShowInfoMsg": true,
  "liveServer.settings.donotVerifyTags": true,
  "errorLens.enabledDiagnosticLevels": ["error", "warning"],
  "[html]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "emmet.syntaxProfiles": {
    "html": {
      "inline_break": 2
    }
  },
  "[jsonc]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[css]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "html.format.indentInnerHtml": true,
  "editor.hover.enabled": false,
  "[scss]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "editor.stickyScroll.enabled": false,
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "files.autoSave": "afterDelay",
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "emojisense.languages": {
    "html": true,
    "css": true,
    "markdown": true,
    "plaintext": {
      "markupCompletionsEnabled": false,
      "emojiDecoratorsEnabled": false
    },
    "scminput": true,
    "git-commit": true
  },
  "liveSassCompile.settings.formats": [
    {
      "format": "expanded",
      "extensionName": ".css",
      "savePath": "/assets/css"
    },
    {
      "format": "compressed",
      "extensionName": ".min.css",
      "savePath": "/assets/css"
    }
  ]
}
```