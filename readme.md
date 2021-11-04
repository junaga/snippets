Not everything can be automated. Correction: Some things _should not_ be automated. It creates more complexity overhead, then it could possibly ever reduce. So I maintain a couple **code snippets**, to solve these kinds of problems, the ol' reliable `CTRL+V`(on the Web) or `SHIFT+INSERT`(on the system) way.

- [`./javascript.md`](./javascript.md)
  - HTML
  - CSS

## General

### VS Code `settings.json`

General, always-on, settings, for my IDE of choice.

```jsonc
{
  "git.autofetch": true,
  "workbench.startupEditor": "readme",

  "editor.formatOnSave": true,
  "editor.tabSize": 2,
  "editor.wordWrap": "on",
  "files.insertFinalNewline": true,

  // Confirmed prompts/popups
  "git.confirmSync": false,
  "git.enableSmartCommit": true,
  "explorer.confirmDragAndDrop": false,
  "liveshare.anonymousGuestApproval": "accept"
}
```

### `.gitignore`

```ignore
*.log
dist/
desktop.ini
.DS_Store
```
