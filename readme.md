This Repo has code snippets I frequently use. Not everything can be automated. Correction: Some things are wrong to automate, it creates more complexity overhead then it could possible ever ease.

### `.gitignore`

```ignore
# Logged messages, from various tools
*.log
# The compiled distributable
dist/

# fucking macOS users
.DS_Store
```

### `.prettierrc`

Prettier settings I use **everywhere**, on clients, servers and dev env. [Here](https://invita.link/prettier-playground) is the Prettier Playground with these settings.

```json
{
  "semi": false,
  "trailingComma": "none",
  "arrowParens": "avoid"
}
```
