Not everything can be automated. Correction: Some things _should not_ be automated. It creates more complexity overhead, then it could possibly ever reduce. So I maintain a couple **code snippets**, to solve these kinds of problems, the ol' reliable `CTRL+V`(on the Web) or `SHIFT+INSERT`(on the system) way.

## `.gitignore`

```
*.log
dist/
desktop.ini
.DS_Store
```

### JavaScript

```
# dependencies
node_modules/
# dotenv config files
.env
```

## `package.json`

```json
{
	"private": true,
	"type": "module",
	"browserslist": [
		"defaults and supports es6-module",
		"maintained node versions"
	],
	"prettier": {
		"useTabs": true,
		"semi": false,
		"trailingComma": "none"
	}
}
```

## `index.html`

```html
<!DOCTYPE html>
<html dir="ltr" lang="$LANG">
	<head>
		<meta charset="UTF-8" />
		<meta name="viewport" content="width=device-width, initial-scale=1" />

		<title>$TITLE</title>
		<meta name="description" content="$DESCRIPTION" />
		<link rel="icon" type="image/png" sizes="48x48" href="/favicon.png" />
	</head>
	<body>
		<main />
	</body>
</html>
```
