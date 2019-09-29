DuplicateSelections
===================

I wrote and use this plugin as an alternative to copy and pasting.

First, you can use this command to duplicate the current line (or lines).

Another common use case is when you need to copy some small bit of text, like a variable or method name.

Select the text to copy, then `cmd+click` to place an empty cursor, then run this command to insert the selected text at the cursor position.

This can be extended to multiple selections: if you have an equal number of selections and cursors, this command will place each selection at the corresponding cursor location.

Or, you can select some text and place *multiple* empty cursors, and the selection will be inserted at all the cursor locations.


## Installation

### By Package Control

1. Download & Install `Sublime Text 3` (https://www.sublimetext.com/3)
1. Go to the menu `Tools -> Install Package Control`, then,
   wait few seconds until the `Package Control` installation finishes
1. Go to the menu `Preferences -> Package Control`
1. Type `Package Control Add Channel` on the opened quick panel and press <kbd>Enter</kbd>
1. Then, input the following address and press <kbd>Enter</kbd>
   ```
   https://raw.githubusercontent.com/evandrocoan/StudioChannel/master/channel.json
   ```
1. Now, go again to the menu `Preferences -> Package Control`
1. This time type `Package Control Install Package` on the opened quick panel and press <kbd>Enter</kbd>
1. Then, search for `DuplicateSelections` and press <kbd>Enter</kbd>

See also:
1. [ITE - Integrated Toolset Environment](https://github.com/evandrocoan/ITE)
1. [Package control docs](https://packagecontrol.io/docs/usage) for details.


###### Example:
<video src="https://github.com/colinta/SublimeDuplicateSelections/raw/master/example.mp4">[Example.mp4](https://github.com/colinta/SublimeDuplicateSelections/raw/master/example.mp4)</video>

Installation
------------

1. Using Package Control, install "DuplicateSelections"

Or:

1. Open the Sublime Text Packages folder
    - OS X: ~/Library/Application Support/Sublime Text 3/Packages/
    - Windows: %APPDATA%/Sublime Text 3/Packages/
    - Linux: ~/.Sublime Text 3/Packages/ or ~/.config/sublime-text-3/Packages

2. clone this repo
3. Install keymaps for the commands (see Example.sublime-keymap for my preferred keys)

Commands
--------

`duplicate_selections`: See description above
