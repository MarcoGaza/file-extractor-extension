# File Content Extractor

This is the README for the "file-content-extractor" extension. This extension provides a context menu option to extract the contents of files along with their file paths and compile them into a single file. It provides options to extract content to JSON or TXT files.

## Features

- Extract the content of files and directories.
- Compile file contents into a single JSON or TXT file.
- Easy-to-use context menu options for extraction.


> Tip: Many popular extensions utilize animations. This is an excellent way to show off your extension! We recommend short, focused animations that are easy to follow.

## Requirements

There are no special requirements or dependencies for this extension.

## Extension Settings

This extension contributes the following settings:

* `fileContentExtractor.enable`: Enable/disable this extension.
* `fileContentExtractor.format`: Set the default format for extraction (`json` or `txt`).

## Known Issues

There are no known issues at this time. If you encounter any issues, please open an issue on GitHub.

## Release Notes

### 0.0.1

- Initial release of the File Content Extractor extension.
- Added file and directory content extraction features.
- Supported formats: JSON and TXT.

---

## Following Extension Guidelines

Ensure that you've read through the extension guidelines and follow the best practices for creating your extension.

* [Extension Guidelines](https://code.visualstudio.com/api/references/extension-guidelines)

## Working with Markdown

You can author your README using Visual Studio Code. Here are some useful editor keyboard shortcuts:

* Split the editor (`Cmd+\` on macOS or `Ctrl+\` on Windows and Linux).
* Toggle preview (`Shift+Cmd+V` on macOS or `Shift+Ctrl+V` on Windows and Linux).
* Press `Ctrl+Space` (Windows, Linux, macOS) to see a list of Markdown snippets.

## For More Information

* [Visual Studio Code's Markdown Support](http://code.visualstudio.com/docs/languages/markdown)
* [Markdown Syntax Reference](https://help.github.com/articles/markdown-basics/)

## Packaging the Extension with VSCE

To package the extension, follow these steps:

1. **Install VSCE**:
   If you haven't installed VSCE, you can install it globally using npm:
   ```sh
   npm install -g vsce
