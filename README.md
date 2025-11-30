# vscode-unciv

[Visual Studio Code](https://code.visualstudio.com/) extension to provide validation for [Unciv](https://github.com/yairm210/Unciv) mods. It provides type-hinting, autocomplete, and error highlighting for your Unciv mod files.

## Features

- JSONC file association for Unciv files
- Validation and Type Hinting

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
