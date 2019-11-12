# Expand Selection to Quotes for Sublime Text

Expands selections to the closest containing pairs of single or double quotes.

## Installation

### Setup Package Control Repository

1. Follow the instructions from https://sublime.fnando.com.
2. Open the command pallete, run “Package Control: Install Package“, then search for “Expand Selection to Quotes“.

### Git Clone

Clone this repository into the Sublime Text “Packages” directory, which is located where ever the “Preferences” -> “Browse Packages” option in sublime takes you.

## Usage

The default binding is `ctrl + shift + i`.

You can change it by defining a new shortcut binding like the following:

```json
{ "keys": ["ctrl+'"], "command": "expand_selection_to_quotes" }
```
