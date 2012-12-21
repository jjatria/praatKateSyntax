# praatKateSyntax

#### Praat syntax highlighting for Kate

## Features
* Accurate highlighting of most of Praat's commands,
  directives and functions, as well as predefined
  variables
* Code folding for all types of blocks
* Highlighting of character escapes and Praat's 'special symbol' syntax
* Highlight of some (not all) unquoted string contexts (eg. `printline`)

## Installation

* Download `praat.xml`
* Save to the kate syntax folder. This is either at  
  `/usr/share/kde4/apps/katepart/syntax`  
  or  
  `~/.kde/share/apps/katepart/syntax`
* Restart Kate

The highlighting definition should be automatically selected for most
common Praat script file extensions. If not, it can be manually
selected from `Tools -> Highlighting -> Scripts -> Praat`.

## Known Issues

* Character escapes are detected for all double-quoted strings, even
  though for Praat they are only used in certain contexts (eg. the Picture window).
* Lines broken into many with triple dots (...) are not properly regarded as a single line.
