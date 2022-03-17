Not everything can be automated. Correction: Some things _should not_ be automated. It creates more complexity overhead, then it could possibly ever reduce. So I maintain a couple **code snippets**, to solve these kinds of problems, the ol' reliable `CTRL+V`(on the Web) or `SHIFT+INSERT`(on the system) way.

- [`./javascript.md`](./javascript.md)
  - HTML
  - CSS

## General

### VS Code `settings.json`

General, always-on, settings, for my IDE of choice.

```jsonc
{
  "git.autofetch": true, // fetch != pull
  "editor.formatOnSave": true,
  "editor.tabSize": 2,
  "files.insertFinalNewline": true,

  // Look and feel
  "editor.unicodeHighlight.invisibleCharacters": true,
  "editor.wordWrap": "on",
  "workbench.startupEditor": "readme",
  "window.menuBarVisibility": "hidden",

  // Confirmed prompts/popups
  "git.confirmSync": false,
  "git.enableSmartCommit": true,
  "explorer.confirmDragAndDrop": false,
  "security.workspace.trust.untrustedFiles": "open",

  // Extension settings
  "liveshare.anonymousGuestApproval": "accept",
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "workbench.iconTheme": "material-icon-theme",
  "github.copilot.enable": { "*": true }
}
```

### `.gitignore`

```ignore
*.log
dist/
desktop.ini
.DS_Store
```
