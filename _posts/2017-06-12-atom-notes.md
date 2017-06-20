---
title: Atom Notes
layout: default
---

# Atom Notes

1. Getting Started
	* Atom Basics
	 * Search for command
		- Ctrl+Shift+P
2. Using Atom
	* Atom Packages
		- Search for them in the install tab in settings
	* Moving in Atom
		- Ctrl+Left 	- Move to the beginning of word
		- Ctrl+Right 	- Move to the end of word
		- Home 			- Move to the first character of the current line
		- End 			- Move to the end of the line
		- Ctrl+Home 	- Move to the top of the file
		- Ctrl+End 		- Move to the bottom of the file
		- Ctrl+G 			- Move to specific line (row:column)
		- Ctrl+R			- Jump to a symbol
		- Ctrl+T			- Does same thing as preview command but needs a tags file (Don't know if fully neccessary)
		- Alt+Ctrl+F2	- Toggle bookmark on current line
		- F2					- Jump to next bookmark
		- Shift+F2		- Cycle backwards through them
		- Ctrl+F2			- List of bookmarks
	* Atom Selections
		- Shift+Up 			- Select up
		- Shift+Down 		- Select down
		- Shift+Left 		- Select previous character
		- Shift+Right 		- Select next character
		- Ctrl+Shift+Left 	- Select to beginning of word
		- Ctrl+Shift+Right 	- Select to end of word
		- Shift+End 		- Select to end of line
		- Shift+Home 		- Select to first character of line
		- Ctrl+Shift+Home 	- Select to top of file
		- Ctrl+Shift+End 	- Select to bottom of file
		- Ctrl+A 			- Select the entire contents of the file
		- Ctrl+L 			- Select the entire line
	* Editing and Deleting Text
		- Basic Manipulation
			- Ctrl+J 			- Join the next line to the end of the current line
			-Ctrl+Up/Down 		- Move the current line up or down
			- Ctrl+Shift+D 		- Duplicate the current line
			- Ctrl+K Ctrl+U 	- Upper case the current word
			- Ctrl+K Ctrl+L 	- Lower case the current word
			- Alt+Ctrl+Q		- Current selection has no longer than 80 characters
		- Deleting and Cutting
			- Ctrl+Shift+K 		- Delete current line
			- Ctrl+Backspace 	- Delete to beginning of word
			- Ctrl+Delete 		- Delete to end of word
		- Multiple Cursors and Selections
			- Ctrl+Click 			- Add a new cursor at the clicked location
			- Alt+Ctrl+Up/Down 		- Add another cursor above/below the current cursor
			- Ctrl+D 				- Select the next word in the document that is the same as the currently selected word
			- Alt+F3 				- Select all words in the document that are the same as the currently selected word
			- Ctrl+Mouse			- Select multiple regions simultaneously
		- Whitespace
			- atom/whitespace
		- Brackets
			- Ctrl+M 			- Jump to the bracket matching the one adjacent to the cursor. It jumps to the nearest enclosing bracket when there's no adjacent bracket.
			- Alt+Ctrl+M 	- Select all the text inside the current brackets
			- Alt+Ctrl+. 	- Close the current XML/HTML tag
		- Encoding
			- Ctrl+Shift+U 		- Toggle menu to change file encoding
	* Find and Replace
		- Ctrl+F 					- Search within a buffer
		- Ctrl+Shift+F 		- Search the entire project (and replace)
	* Snippets
		- Tab			- Expand code snippets
	* Folding
		- Alt+Ctrl+[/]						- Fold and unfold blocks of code
			~ Add shift to fold/unfold everything
		- Ctrl+K and Ctrl+0-9			- Folds at specific indention level
		-Alt+Ctrl+F								- Fold arbitrary sections of your code with selection
	* Panes
		- Ctrl+K with up/down/left/right		- Split pane
			~ Add Ctrl with directional buttons to navigate between panes
		- Ctrl+W		- Close pane
	* Grammar
		- Ctrl+Shift+L		- Language selector
	* Version Control
		- Checkout HEAD revision
			- Alt+Ctrl+Z		- Discards staged and saved changes that aren't from latest commit
		- Git Status List
			- Ctrl+T					- Open files in a project
			- Ctrl+B					- Jump to any open editor
			- Ctrl+Shift+B		- Shows untracked and modified files
		- Open on GitHub
			- Alt+G O 	- Open file on GitHub
			- Alt+G B 	- Open Blame view of file on GitHub
			- Alt+G H 	- Open History view of file on GitHub
			- Alt+G C 	- Copy the URL of the current file on GitHub to the clipboard
			- Alt+G R 	- Branch compare on GitHub
	* Writing in Atom
		- Spell Checking
		 - Ctrl+Shift+;		- Possible corrections list
		- MarkDown Preview
			- Ctrl+Shift+M
