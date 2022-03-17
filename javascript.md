### `.gitignore`

```ignore
*.log
dist/
desktop.ini
.DS_Store

# dependencies
node_modules/
# dotenv config files
.env
```

### `.prettierrc`

Prettier [settings](https://invita.link/prettier-playground) I use everywhere.

```json
{
  "semi": false,
  "trailingComma": "none",
  "arrowParens": "avoid",
  "quoteProps": "consistent"
}
```

### Private `package.json`

```json
{
  "private": true,
  "type": "module"
}
```

### Published `package.json`

```json
{
  "name": "PACKAGE NAME",
  "version": "0.0.0",
  "description": "PACKAGE DESCRIPTION",
  "license": "MIT",
  "author": "junaga <hermann-stanew@invita.gmbh>",
  "repository": {
    "type": "git",
    "url": "https://github.com/junaga/REPO-NAME.git"
}
```

### Production grade `.html` `<head>`

Always include `<!DOCTYPE html>` on the first line.

```html
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />

  <title>DOCUMENT TITLE</title>
  <link rel="icon" href="/favicon.png" />
  <meta name="description" content="DOCUMENT DESCRIPTION" />
</head>
```
