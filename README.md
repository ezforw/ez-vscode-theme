# EZ Light Theme

A beautiful light theme for VS Code.

## Installation

1. Open VS Code
2. Go to the Extensions view (`Ctrl+Shift+X` / `Cmd+Shift+X`)
3. Search for "EZ Light"
4. Click Install

Or install from the command line:

```bash
code --install-extension ez-light-theme
```

## Activation

Once installed, activate the theme:

1. Open the Command Palette (`Ctrl+Shift+P` / `Cmd+Shift+P`)
2. Type "Color Theme"
3. Select "EZ Light" from the list

## Features

- Clean, light color scheme
- Easy on the eyes
- Great syntax highlighting
- Optimized for all programming languages

## Development

To develop this theme:

1. Clone the repository
2. Press `F5` to open the Extension Development Host
3. Make changes to `themes/ez-light-theme-color-theme.json`
4. Changes will be reflected in the Extension Development Host automatically

## Packaging

To package this theme as a VSIX file:

1. Install `vsce` (if not already installed):

```bash
npm install -g @vscode/vsce
```

2. Run the package command:

```bash
vsce package
```

This will create a `.vsix` file that you can share or install locally:

```bash
code --install-extension ez-light-theme-0.0.1.vsix
```

## License

MIT
