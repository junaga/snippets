Not everything can be automated. Correction: Some things _should not_ be automated. It creates more complexity overhead, then it could possibly ever reduce. So I maintain a couple **code snippets**, to solve these kinds of problems, the ol' reliable `CTRL+V`(on the Web) or `SHIFT+INSERT`(on the system) way.

- [`./javascript.md`](./javascript.md)
  - HTML
  - CSS

## General

### VS Code `settings.json`

General, always-on, settings, for my IDE of choice.

```jsonc
{
  "terminal.integrated.shellIntegration.enabled": false, // bad bad bad
  "git.autofetch": true, // fetch != pull
  "editor.formatOnSave": true,
  "files.insertFinalNewline": true,

  // Confirmed prompts/popups
  "git.confirmSync": false,
  "git.enableSmartCommit": true,
  "explorer.confirmDragAndDrop": false,
  "security.workspace.trust.untrustedFiles": "open",

  // Look and feel
  "editor.wordWrap": "on",
  "diffEditor.ignoreTrimWhitespace": false,
  "terminal.integrated.defaultLocation": "editor",
  "terminal.integrated.rightClickBehavior": "default",
  "terminal.integrated.scrollback": 1000000,
  "terminal.integrated.fontFamily": "Cascadia Mono",
  "workbench.startupEditor": "readme",
  "window.menuBarVisibility": "compact",

  // Extension settings
  "github.copilot.enable": { "*": true },
  "liveshare.anonymousGuestApproval": "accept",
  "workbench.iconTheme": "material-icon-theme",
  "errorLens.onSave": true,
  "vscodeGoogleTranslate.preferredLanguage": "English",
  // Prettier
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "prettier.semi": false,
  "prettier.trailingComma": "none",
  // python
  "[python]": {
    "editor.defaultFormatter": "ms-python.python"
  },
  "python.formatting.provider": "black",
  "python.analysis.typeCheckingMode": "strict",
  // svelte
  "svelte.ask-to-enable-ts-plugin": false
}
```

### `.gitignore`

```ignore
*.log
dist/
desktop.ini
.DS_Store
```
