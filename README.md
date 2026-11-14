# guile-vscode README

## Features

This package provides editing support and syntax highlighting for Guile source
code. For indentation, install package Paredit or Strict Paredit.

## Extension Settings

If you don't want the brackets in your source code to be colourized switch off the configuration variable editor.bracketPairColorization.enabled.

If you don't want to use the strict editing mode configure VSCode setting `paredit.defaultKeyMap` to `original` or `none`. 

## Release Notes

### 1.0.4

Updated README.md.

### 1.0.3

Updated release notes in README.md.

### 1.0.2

Fixed matching and highlighting bugs caused by bracket character constants.

Improved parsing character constants.

### 1.0.1

Added publisher to package.json.

### 1.0.0

Initial release of guile-vscode.
