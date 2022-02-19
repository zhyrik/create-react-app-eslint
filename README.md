# Stararteer with eslint & prettier

npx eslint --init

npm i -D eslint eslint-config-airbnb eslint-config-prettier eslint-plugin-import eslint-plugin-jsx-a11y eslint-plugin-prettier eslint-plugin-react eslint-plugin-react-hooks husky lint-staged prettier pretty-quick


ctrl+shift+p => settings

{
    "prettier.semi": false,
    "prettier.jsxBracketSameLine": true,
    "diffEditor.wordWrap": "on",
    "editor.wordWrap": "on",
    "window.zoomLevel": 1,
    "editor.formatOnSave": true,
    "reactSnippets.settings.prettierEnabled": true,
    "prettier.jsxSingleQuote": true,
    "editor.tabSize": 2,
    "javascript.format.insertSpaceAfterOpeningAndBeforeClosingJsxExpressionBraces": true,
    "[javascript]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode",
        "editor.formatOnSave": true
    },
    "[vue]": {
        "editor.formatOnSave": true,
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "[javascriptreact]": {
        "editor.formatOnSave": true,
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "prettier.singleQuote": true,
    "eslint.alwaysShowStatus": true,
    "files.eol": "\n"
}