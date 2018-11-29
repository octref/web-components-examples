# Web Component Examples

This is a fork of https://github.com/mdn/web-components-examples to demonstrate VS Code's improved HTML support for custom tags / attributes.

Please send feedback and feature requests to https://github.com/Microsoft/vscode/issues/62976 or open new issues at https://github.com/Microsoft/vscode.

## Demo

![demo](demo.gif)

## Files of interest

- [.vscode/settings.json](.vscode/settings.json): The `html.experimental.custom.tags` and `html.experimental.custom.attributes` settings inform VS Code's HTML language server of custom tags / attributes.
- [web-components.json](web-components.json) and [web-components-attributes.json](web-components-attributes.json): The JSON files that define custom tags / attributes. **The JSON format is subject to change.**