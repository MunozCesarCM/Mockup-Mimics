# WYSIWYG Editor

This is a What-You-See-Is-What-You-Get (WYSIWYG) editor built using HTML, CSS, and JavaScript. The purpose of this editor is to provide a simple interface for formatting text using basic HTML tags.

# Table of Contents

- [Features](#features)
- [Usage](#usage)
  - [Button Options](#button-options)
  - [Limitations](#limitations)
  - [Dependencies](#dependencies)
- [Code Documentation](#code-documentation)
  - [Initializer](#initializer)
  - [`modifyText()`](#modifytext)
  - [Button Event Listeners](#button-event-listeners)
  - [`highlighter()`](#highlighter)
  - [`highlighterRemover()`](#highlighterremover)
  - [`initializer()`](#initializer)

## Features

- Bold, italic, underline
- Font family and size
- Text alignment
- Text formatting (superscript, subscript, strikethrough)
- Text highlighting
- Link creation
- Undo and redo

## Usage

To use the editor, simply open the HTML file in a web browser. Click on the various buttons to modify the text as desired.

### Button Options

- Bold, italic, underline
- Font family and size
- Text alignment
- Text formatting (superscript, subscript, strikethrough)
- Text highlighting
- Link creation
- Undo and redo

### Limitations

- The editor cannot save text, so all changes will be lost upon closing the window.

### Dependencies

None.

## Code Documentation

### Initializer

- `optionsButtons`: selects all buttons that do not require input
- `advancedOptionButton`: selects all buttons that require input
- `fontName`: selects the font name select element
- `fontSizeRef`: selects the font size select element
- `writingArea`: selects the writing area element
- `linkButton`: selects the create link button element
- `alignButtons`: selects all text alignment buttons
- `spacingButtons`: selects all spacing buttons
- `formatButtons`: selects all text formatting buttons
- `scriptButtons`: selects all superscript and subscript buttons
- `fontList`: an array of all available fonts
- `initializer()`: initializes the editor by setting button highlights, creating font options, and setting font size.

### `modifyText()`

- `command`: the command to execute on the selected text
- `defaultUi`: whether or not to display the default user interface
- `value`: the value to use for the command
- `modifyText()`: executes the given command on the selected text.

### Button Event Listeners

- `optionsButtons`: add event listeners to all buttons that do not require input
- `advancedOptionButton`: add event listeners to all buttons that require input
- `linkButton`: add event listener to the create link button

### `highlighter()`

- `className`: the class name of the buttons to highlight
- `needsRemoval`: whether or not to remove highlighting from other buttons
- `highlighter()`: highlights the clicked button

### `highlighterRemover()`

- `className`: the class name of the buttons to remove highlighting from
- `highlighterRemover()`: removes highlighting from all buttons with the given class name.

### `initializer()`

- `initializer()`: initializes the editor by setting button highlights, creating font options, and setting font size.

