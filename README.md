# Files to use for configuring VS Code for STM32 ARM development

Supporting tutorials:
- [Using Visual Studio Code with STM32CubeMX for ARM Development](https://hbfsrobotics.com/blog/configuring-vs-code-arm-development-stm32cubemx) - Windows 
- [VS Code Setup for STM32 ARM Development](https://medium.com/@cristian.dbr/vs-code-setup-for-stm32-arm-development-on-apple-silicon-mac-e244b789bde1) - macOS

## Usage

There is a branch created for every OS. Run the appropariate quickstart scripts to download the configuration files to your project folder.

### win-x86_64

```sh
mkdir .vscode
cd .vscode
curl -LO https://raw.githubusercontent.com/cristidbr/vscode-stm32-setup/win-x86_64/c_cpp_properties.json
curl -LO https://raw.githubusercontent.com/cristidbr/vscode-stm32-setup/win-x86_64/tasks.json
curl -LO https://raw.githubusercontent.com/cristidbr/vscode-stm32-setup/win-x86_64/settings.json
curl -LO https://raw.githubusercontent.com/cristidbr/vscode-stm32-setup/win-x86_64/launch.json
cd ..
```

### macos-arm64

```sh
mkdir .vscode
cd .vscode
curl -LO https://raw.githubusercontent.com/cristidbr/vscode-stm32-setup/macos-arm64/c_cpp_properties.json
curl -LO https://raw.githubusercontent.com/cristidbr/vscode-stm32-setup/macos-arm64/tasks.json
curl -LO https://raw.githubusercontent.com/cristidbr/vscode-stm32-setup/macos-arm64/settings.json
cd ..
```

## License

MIT 