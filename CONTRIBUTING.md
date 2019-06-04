# Contribution Guide
Thank you for helping us! Below you can find some notes for the development of the Dackboard.

## Project policies
* Try to keep the line length below 120 characters (There's a VSCode setting for displaying a ruler below)
```json
"editor.rulers": [120], // at 120 characters
"workbench.colorCustomizations": {
    "editorRuler.foreground": "#ffffff45" // color of the ruler
}
```
- All classnames and interfaces in `PascalCase`
  - Routes with a leading `R`
  - Interfaces with a leading `I`
- JSON keys in `camelCase`
- Enums names in `PascalCase`, keys in `UPPERCASE`
- Boolean variables should be prefixed with `is`, `can` or `should`
- All `if/else/do/while/for/try/catch` etc. clauses must be wrapped inside brackets, even oneliners.
- Conditional operators should only be used if they are short, split the complex ones in if/else
- Try to keep the code as simple and clear to read as possible
- Document everything as good as you can (see [jsdoc syntax](https://devhints.io/jsdoc))
- Commits should be in logical and small pieces with meaningful commit messages
- Pull requests should be kept as small as possible
