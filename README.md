# JavaScript/Typescript Language Configuration

This reverts the automatic single line indentation introduced in https://github.com/microsoft/vscode/pull/209038 and similar PRs.

The `package.json` settings and language configurations are based on the following files:
- https://github.com/microsoft/vscode/blob/main/extensions/javascript/package.json
- https://github.com/microsoft/vscode/blob/main/extensions/javascript/javascript-language-configuration.json
- https://github.com/microsoft/vscode/blob/main/extensions/typescript-basics/package.json
- https://github.com/microsoft/vscode/blob/main/extensions/typescript-basics/language-configuration.json

The language configurations are meant to be kept in sync besides the `indentNextLinePattern` line.
