# vscode_tips

eslint prettier vscode autosave fix

```cmd
    npm install -g eslint
    eslint --init
    npm i -D eslint-config-prettier eslint-plugin-prettier

```

```json
    "editor.formatOnSave": true,
    "[javascript]": {
        "editor.formatOnSave": false,
    },
    "editor.codeActionsOnSave": {
        "source.fixAll": true
  }
```

```javascript
    // eslintrc
    extends: ["prettier"],
    plugins: ["prettier"],
    rules: {
        "prettier/prettier": ["error"],
    },
```
