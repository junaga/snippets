This repo has code snippets I frequently use. Not everything can be automated. Correction: Some things **should not** be automated. It creates more complexity overhead, then it could possible ever ease.

### `.gitignore`

```ignore
# Logged messages, from various tools
*.log
# A compiled distributable
dist/

# fucking macOS users
.DS_Store
```

### `.prettierrc.json`

Prettier settings I use **everywhere**, on clients, servers and the dev env. [Here](https://invita.link/prettier-playground) is the Prettier Playground with these settings.

```json
{
  "semi": false,
  "trailingComma": "none"
}
```

### HTML `<head>`

What a HTML `<head>` might look like. Don't forget the `<!DOCTYPE html>`, at the very top of the document, to force HTML5.

```html
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>DOCUMENT TITLE</title>
  <meta name="description" content="DOCUMENT DESCRIPTION" />
  <link rel="icon" href="/favicon.ico" />
</head>
```
