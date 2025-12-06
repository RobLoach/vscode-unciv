# vscode-unciv

[![VSCode Marketplace](https://img.shields.io/badge/VSCode-robloach.unciv-blue)](https://marketplace.visualstudio.com/items?itemName=robloach.unciv)
[![Open VSX](https://img.shields.io/badge/OpenVSX-robloach.unciv-pink)](https://open-vsx.org/extension/robloach/unciv)

[Visual Studio Code](https://code.visualstudio.com/) extension for [Unciv](https://github.com/yairm210/Unciv) mod validation, type-hinting, autocomplete, error highlighting, and intellisense.

## Features

- JSONC file association for Unciv files
- Validation and Type Hinting
- Unique autocompletes

## Installation

In Visual Studio Code open the command palette using Ctrl + P, paste the following command, and press Enter.

```sh
ext install robloach.unciv
```

## Development

To install from source, use...
```sh
npm run build
```

## References

- [Official Unciv Schemas](https://github.com/yairm210/Unciv/tree/master/docs/Modders/schemas)
- [VSCode `jsonValidation` Contribution Points](https://code.visualstudio.com/api/references/contribution-points#contributes.jsonValidation)
- [Uniques.md](https://github.com/yairm210/Unciv/blob/master/docs/Modders/uniques.md)

## License

[MIT](LICENSE)
