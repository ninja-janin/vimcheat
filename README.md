# Vimcheat by Ninja-Janin

## ACCIDENTALLY PRESSED

if ctrl z pressed, press fg Enter to go back to vim.

## NAVIGATION:
* `h      - left`
* `j      - down`
* `k      - right`
* `l      - left`
* `b      - move backward to the beginning of the word`
* `$      - end`
* `0      - home`
* `^      - move to the first non-blank character of the line`
* `)      - jump forward one sentence`
* `(      - jump backward one paragraph`
* `{      - jump forward one paragraph`
* `}      - jump backward one paragraph`
* `H      - jump to the top of the screen`
* `1G     - jump to the beginning of the file (same as gg)`
* `50G    - jump to line 50`
* `'m     - jump to the the beginning of the line of mark m`
* `\`m    - jump to the cursor position of mark m`
* `""     - return to the line where the cursor was before the latest jump(two single qoutes)`
* `\`\`   - return to the cursor position before the latest jump (undo the jump)(two back ticks. this is above the Tab key on some keyboards)`
* `%      - jump to the corresponding item, e.g. from an open brace to its matching closing brace.`
* `arrows - moving lines`
* `o      - inserting newlines below`
* `O      - inserting newlines above`
* `ctrly  - scroll up`
* `ctrle  - scroll down`
* `gg     - back to top`
* `G      - jump to the end of the file`
* `a      - type appended text`
* `g+t    - change active tab`
* `tabnew - new tab`
* `esc    - place to normal mode`
* `:vsp   - vertical split`
* `:sp    - split`
* `:A     - insert at the end of the line`
* `:I     - insert at the beginning of the line`


## SAVING:

* `w					- save`
* `wq					- quit and save`
* `wq!					- quit and disregard changes`
* `:saveas filename		- saving as`
 	`note: wrap filename with "" if it contain space/s`
	`or`
  `:saveas % then press tab to get the present file directory`

## DELETING

* `d          -delete`
* `dd         -deleting the entire row`
* `d$         -deleting from cursor at the end of the line`
* `dw         -deleting upto the end of the word including spaces`
* `de         -deleting upto the end of the current word`
* `x          -deleting character`

## FORMATTING

* `set spell   - checking all uncorrect words.`
* `z=          - go to word to correct then type z= to view the all uncorrect words.`
* `set nospell - setting to no spell.`
* `ga character                                                                     - highlight the word first before pressing ga`
* `gaip + character                                                                 - aligning with specific character //disregard + sign`
* `ga ctrl x + character                                                            - custom aligning // disregard + sign`
* `v                                                                                - highlight`
* `i                                                                                - insert text`
* `shift >                                                                          - tab`
* `u                                                                                - undo`
* `ctrl r                                                                           - redo`
* `higlight the word then press control n until all words are selected then press s - edit same word in one time`
* `:Tab /word                                                                       - tabularize(after typing :Tab /word press enter`
* `ctrl v                                                                           - highlighting by line downwards (use the navigation key to navigate)`
* `r                                                                            	- replace existing character`

## SEARCHING

* `\p                                                   - searching files`
* `m                                                    - Add, edit, Delete,Copy files`
* `:sort                                                - sorting`
* `highlight the word then ctrl n  then press s to edit - multiple editing.`
* `highlight the word then shift+S+" or '               - wrap text with single/double quote`
* `c+s then press double/sing quote                     - changing wrapper`
* `:grep "word to search" -r ./sourceDirectoryToBeSearch     - searching file`
* `:cw                                                  - (view the results)sorting the searched files`
* `di input character                                   - deleting inside`

## COPY & PASTING

* `v   - highlight`
* `"+y - copy to system clipboard`
* `"+p - paste from system clipboard`
* `yyp - copy current line in cursor`

## BASIC COPY PASTING

* `y           - copy`
* `p           - paste`
* `:e filename - search the .file`
* `|p          - search file`
* `yyp         - instant copy the line`

## MULTIPLE COPY AND PASTING

* `"register(anyLetter) y   - copy to register`
* `"register(choosenLetter) - paste from register`

## EDITING & DELETING

* `ci" or ()    - copy inside closing characters like ", () , [], {}`
* `vi" or ()    - visual inside closing characters like ", () , [], {}`
* `di" or ()    - delete inside closing characters like ", () , [], {}`
* `ctrlv 		- multiple inputs vertically`

## NERD

* `\n                                          - open & close sidebar`
* `I                                           - show hidden file in nerdtree`
* `\p                                          - search file`
* `/nameOfFile                                 - search word`
* `ctrl h or l                                 - move from edit field to dir`
* `s                                           - open file in new tab`
* `/wordToSearch                               - to search a word`
* `n                                           - move cursor to searched word/s downward`
* `N                                           - move cursor to searched word/s upward`
* `noh                                         - exit from search mode`
* `T                                           - open in new tab`
* `gt                                          - next tab`
* `gT                                          - previous tab`
* `s                                           - open file horizontally`
* `i                                           - open file vertically`
* `ctrl+w then no. of spaces then shift < or > - widening nerd`
* `i                                           - open file in split window horizontally`
* `s                                           - open file in split window vertically`
* `R                                           - refreshing nerd directory`

## WINDOW ADJUSTMENT

* `ctrlw numberOfSpaces then < or > - adjusting nerd`
* `ctrlw|                           - set to full screen selected window`
* `ctrlw=                           - set the screen of the selected window to equal size`
* `:vsp                             - open file in split window horizontally`
* `:sp                              - open file in split window vertically`

## TAGS

* `type html tags then press ctrlY,`

# ex:

* `<html>sample tag</html>`
* `tag.className*5 ctrly,                   - multiple tags`
* `highlight then gc                        - to comment`
* `tag.nameOfTheClass then press ctrlYcomma - creating html element with class name`
* `:set tw=999                              - removing vertical limitation`
* `vat                                      - highlighting divs`

## MANIPULATING FILES

* `:new filename.txt`
* `m   - adding,deleting,copying`

## GIT COMMANDS:

* `diff         - viewing changes.`
* `-- .         - remove all changes`

## FEATURES

* `hi Normal ctermbg=none - set background to transparent`
* `git rebase             - i root branchname`

