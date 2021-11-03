### `.gitignore`

```ignore
*.log
dist/
desktop.ini
.DS_Store

# javascript dependencies
/node_modules/
/package-lock.json
```

### `.prettierrc`

Prettier [settings](https://invita.link/prettier-playground) I use everywhere.

```json
{
  "semi": false,
  "trailingComma": "none"
}
```

### published `package.json`

If nowhere published I only set `"private": true`.

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

### production grade `.html` `<head>`

Remember to include `<!DOCTYPE html>` on the first line.

```html
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />

  <title>DOCUMENT TITLE</title>
  <link rel="icon" href="/favicon.ico" />
  <meta name="description" content="DOCUMENT DESCRIPTION" />
</head>
```
