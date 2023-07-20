# vscode_setting

This repository contains the configuration for Visual Studio Code settings. The `settings.json` file customizes various aspects of the VS Code editor to enhance the development experience.

## Settings

The following are some of the key settings in the `settings.json` file:

### Editor

- `"editor.tabSize": 3`: Sets the tab size to 3 spaces.
- `"editor.fontFamily": "Menlo"`: Sets the font family to Menlo.

### Terminal

- `"terminal.integrated.fontSize": 13`: Sets the terminal font size to 13.

### Theme and Color Customizations

- `"workbench.colorTheme": "One Dark Pro Darker"`: Applies the One Dark Pro Darker theme to the editor.
- `"workbench.colorCustomizations": { ... }`: Customizes various colors in the editor, including the terminal background and selection colors.

### Notebook and Cell Toolbar

- `"workbench.editorAssociations": { ... }`: Specifies the editor associations for specific file types.
- `"notebook.cellToolbarLocation": { ... }`: Sets the location of the cell toolbar for notebooks.

### Auto Save

- `"files.autoSave": "afterDelay"`: Enables auto-saving files after a delay.

### Code Runner

- `"code-runner.executorMap": { ... }`: Configures the commands for different programming languages when using the Code Runner extension.

### To-Do Highlight

- `"todohighlight.keywords": [ ... ]`: Specifies custom keywords to highlight in code comments.
- `"todohighlight.defaultStyle": { ... }`: Customizes the style for highlighted to-do items.

### Live Server

- `"liveServer.settings.donotShowInfoMsg": true`: Prevents Live Server from showing info messages.

### Other Customizations

- `"gocodeo.authToken": "..."`: Specifies the authentication token for the Gocodeo extension.
- `"gocodeo.pythonTestFramework": "unittest"`: Sets the Python test framework for Gocodeo.
- `"gocodeo.jsTestFramework": "unittest"`: Sets the JavaScript test framework for Gocodeo.
- `"tabnine.experimentalAutoImports": true`: Enables experimental auto-imports in TabNine.

## Usage

To use these settings, copy the content of the `settings.json` file to your Visual Studio Code settings.

Please make sure to properly format the JSON content to avoid syntax errors in your `.vscode/settings.json` file.

Happy coding!
