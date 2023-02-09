Not everything can be automated. Correction: Some things _should not_ be automated. It creates more complexity overhead, then it could possibly ever reduce. So I maintain a couple **code snippets**, to solve these kinds of problems, the ol' reliable `CTRL+V`(on the Web) or `SHIFT+INSERT`(on the system) way.

## `.gitignore`

```
*.log
dist/
desktop.ini
.DS_Store
```

### JavaScript `.gitignore`

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
<html>
	<head>
		<meta charset="UTF-8" />
		<meta name="viewport" content="width=device-width, initial-scale=1" />

		<title>DOCUMENT TITLE</title>
		<link rel="icon" href="/favicon.png" />
		<meta name="description" content="DOCUMENT DESCRIPTION" />
	</head>
	<body />
</html>
```
