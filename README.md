<div align="center">

# Core Lua API for VS Code

A [Visual Studio Code](https://code.visualstudio.com/) [extension](https://marketplace.visualstudio.com/VSCode) that adds support for the [Core Games](https://www.coregames.com) Lua API to the Lua Language Server.

[![Open in VSCode](https://img.shields.io/static/v1?logo=visualstudiocode&label=&message=Open%20in%20Visual%20Studio%20Code&labelColor=2c2c32&color=007acc&logoColor=007acc)](https://open.vscode.dev/ManticoreGames/vscode-core) [![Build Status](https://github.com/ManticoreGamesInc/vscode-core/workflows/CI/badge.svg)](https://github.com/ManticoreGamesInc/vscode-core/actions?workflow=CI) [![Marketplace Version](https://img.shields.io/visual-studio-marketplace/v/manticoregames.vscode-core?label=Visual%20Studio%20Marketplace&logo=visual-studio-code "Current Version")](https://marketplace.visualstudio.com/items?itemName=ManticoreGames.vscode-core)

![Logo](https://i.imgur.com/4WSkkYF.jpg)
</div>

As of version 1.0.0, this extension uses [Sumneko's](https://marketplace.visualstudio.com/items?itemName=sumneko.lua) Lua [Language Server](https://microsoft.github.io/language-server-protocol/) with [auto-generated](https://github.com/kerwanp/core-types-generator) [EmmyLua](https://github.com/sumneko/lua-language-server/wiki/EmmyLua-Annotations) annotations.

The extension itself does not come with any options. If you want to alter its behavior you have to change it in the [Lua Language Server](https://github.com/sumneko/lua-language-server) extension that gets installed automatically.

If you have previously been using `vscode-core` together with the `Lua Coder Assist` extension, make sure to uninstall that for the best results.

Sumneko's Lua extension also comes with it's own "**Diagnostics**" feature, so if you have been using other extensions that use Luacheck and a `.luacheckrc` file, you might want to either disable those extensions or the "Diagnostics" feature in Sumneko's.

## Known Issues

- There is currently no support for Core API operators.

## Installation

- Go to the Visual Studio Code Marketplace and click the "**Install**" button, that's it!

## Related Repositories

- [platform-documentation](https://docs.coregames.com) - The Core Lua API documentation website.
- [core-types-generator](https://github.com/kerwanp/core-types-generator) - Generates the `core-games-api.def.lua` file that contains the Core API EmmyLua annotations.

## Contributing

This project welcomes contributions and suggestions.

### Community Contributors

- @agincel
- @SargntSprinkles

## License

Licensed under the [MIT](LICENSE) license.
