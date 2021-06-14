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

### `.prettierrc`

Prettier settings I use **everywhere**, on clients, servers and the dev env. [Here](https://invita.link/prettier-playground) is the Prettier Playground with these settings.

```json
{
  "semi": false,
  "trailingComma": "none"
}
```

### HTML `<head>`

From [MDN docs](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/head):

> The `<head>` HTML element contains **machine-readable** information (metadata) about the document.

```html
<head>
  <title>Webpage<title>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
</head>
```
