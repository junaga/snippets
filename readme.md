Not everything can be automated. Correction: Some things **should not** be automated. It creates more complexity overhead, then it could possible ever reduce.

### `.gitignore`

```ignore
# Logged messages, from various tools
*.log
# A compiled distributable
dist/

# fucking macOS users
.DS_Store
```

### `.prettierrc`

Prettier [settings](https://invita.link/prettier-playground) I use everywhere.

```json
{
  "semi": false,
  "trailingComma": "none"
}
```

### production grade `.html` `<head>`

Always including the initial `<!DOCTYPE html>` to **force** HTML5.

```html
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>DOCUMENT TITLE</title>
  <meta name="description" content="DOCUMENT DESCRIPTION" />
  <link rel="icon" href="/favicon.ico" />
</head>
```
