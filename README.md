# praatKateSyntax

#### Praat syntax highlighting for Kate

## Features
* Accurate highlighting of most of Praat's commands,
  directives and functions, as well as predefined
  variables
* Code folding for all types of blocks
* Highlighting of character escapes and Praat's 'special symbol' syntax

## Installation

* Download `praat.xml`
* Save to the kate syntax folder. This is either at  
  `/usr/share/kde4/apps/katepart/syntax`
  or  
  `~/.kde/share/apps/katepart/syntax`
* Restart Kate

The highlighting definition should be automatically selected for most
common Praat script file extensions. If not, it can be manually
selected from `Tools/Highlighting/Scripts/Praat`.

## Known Issues

* Character escapes are detected for all double-quoted strings, even
  though for Praat they are meaningless unless sent to the Picture
  Window or written to a TextGrid file.
