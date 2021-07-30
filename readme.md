Not everything can be automated. Correction: Some things **should not** be automated. It creates more complexity overhead, then it could possible ever reduce.

### `.gitignore`

```ignore
*.log
dist/

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

### published `package.json`

If nowhere published, I only set `"private": true`.

```json
{
  "name": "PACKAGE NAME",
  "version": "0.0.0",
  "description": "PACKAGE DESCRIPTION",
  "license": "MIT",
  "author": "hermann-stanew@invita.gmbh",
}
```

### production grade `.html` `<head>`

```html
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>DOCUMENT TITLE</title>
  <meta name="description" content="DOCUMENT DESCRIPTION" />
  <link rel="icon" href="/favicon.ico" />
</head>
```
