# VIM

Vim (Vi Improved) is a text editor that is commonly used by programmers and system administrators. It is a command-line based tool that is known for its powerful editing capabilities and efficient workflows. Vim is a modal editor, which means that it has different modes for editing, inserting text, and issuing commands. This can take some time to get used to, but many users find it to be a very efficient way of working with text. Vim is available on most Unix-like systems, including Linux and macOS.

Movement:

| Command	| Description
|---------|------------
| h	| move left
| j	| move down
| k	| move up
| l	| move right
| w	| move to the start of the next word
| e	| move to the end of the next word
| b	| move to the start of the previous word
| 0	| move to the start of the line
| $	| move to the end of the line
| gg | move to the first line of the file
| G |	move to the last line of the file

Editing:

| Command	| Description
|---------|------------
| i	| enter insert mode at the cursor
| I	| enter insert mode at the start of the line
| a	| enter insert mode after the cursor
| A	| enter insert mode at the end of the line
| o	| open a new line below the cursor and enter insert mode
| O	| open a new line above the cursor and enter insert mode
| s	| delete the character under the cursor and enter insert mode
| S |	delete the current line and enter insert mode

Cut, copy, and paste:

| Command	| Description
|---------|------------
| yy | copy the current line
| dd | cut the current line
| p	| paste after the cursor
| P |	paste before the cursor

Search and replace:

| Command	| Description
|---------|------------
| /pattern | search for pattern
| n	| go to the next search result
| N |	go to the previous search result
| :%s/old/new/g	| replace all occurrences of old with new in the file

Save and quit:

| Command	| Description
|---------|------------
| :w	| save the file
| :q	| quit vim
| :wq	| save and quit
| :q! |	force quit (without saving)
