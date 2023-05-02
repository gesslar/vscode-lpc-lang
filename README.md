# Visual Studio Code LPC Language Extension

LPmud C Language syntax highlighting for the FLUFFOS branch of LPmud drivers.

## Features

Basic syntax highlighting for LPC

## Release Notes
### v 1.0.1
* Removed triangular brackets that were causing issues. `<` and `>` are not
  used in FluffOS as brackets. If needed for other drivers, can re-evaluate
  in the future.
* Modified standard colour tag support to be arrays instead of objects, since
  they are basic and don't require additional syntaxes such as "notIn".
* Removed `activationEvents` from package.json since VS Code advises that this
  is inferred information.

### v 1.0.0
* Strings are now handled by the language server.
* The language server should fix the @text/text block issues.

### v 0.4.0
* Fixed issue with snippets (thanks to gesslar)
* Added .lpc as a filetype

### v 0.3.0
* Added standard color tag support
* Fixed issue with extra paren appearing when defining mappings and arrays.

### v 0.2.1
* Added icon and some metadata changes.

### v 0.2.0
* Added more efun references.

### v 0.1.0
* Initial Setup

## Contribute

If you'd like to contribute please check out our project page: [GwennKoi/vscode-lpc-lang](http://github.com/GwennKoi/vscode-lpc-lang)
