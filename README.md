## Typescript-Node.js Template

[![Build Badge](https://github.com/EddieWongED/nodejs-typescript-template/actions/workflows/build.yaml/badge.svg)](https://github.com/EddieWongED/nodejs-typescript-template/actions/workflows/build.yaml)
[![Eslint Badge](https://github.com/EddieWongED/nodejs-typescript-template/actions/workflows/eslint.yaml/badge.svg)](https://github.com/EddieWongED/nodejs-typescript-template/actions/workflows/eslint.yaml)

-   In VSCode settings, append the following to use eslint by default:

```json
{
	...
	"[typescript]": {
		"editor.defaultFormatter": "esbenp.prettier-vscode"
	},
	"[json]": {
		"editor.defaultFormatter": "esbenp.prettier-vscode"
	},
	"editor.codeActionsOnSave": {
		"source.fixAll.eslint": true
	},
	"eslint.validate": ["typescript"],
	"eslint.format.enable": true
}
```
