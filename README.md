# vscode-unciv

[Visual Studio Code](https://code.visualstudio.com/) extension to provide validation for [Unciv](https://github.com/yairm210/Unciv) mods. It automatically checks your Unciv JSON syntax errors and common mistakes, helping you catch issues early.

## Features

- JSONC file association for Unciv files
- Unciv JSON Schema Validation

## Installation

In Visual Studio Code open the command palette using Ctrl + P, paste the following command, and press Enter.

```sh
ext install robloach.unciv
```

## Development

To install from source, use...
```
npm run build
```

## References

- [Official Unciv Schemas](https://github.com/yairm210/Unciv/tree/master/docs/Modders/schemas)
- [VSCode `jsonValidation` Contribution Points](https://code.visualstudio.com/api/references/contribution-points#contributes.jsonValidation)

## License

[MIT](LICENSE)
