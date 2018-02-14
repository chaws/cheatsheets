# Basics
From: https://www.skorks.com/2009/09/bash-shortcuts-for-maximum-productivity/
## Navigation
Ctrl + a  go to the start of the command line<br>
Ctrl + e  go to the end of the command line<br>
Ctrl + k  delete from cursor to the end of the command line<br>
Ctrl + u  delete from cursor to the start of the command line<br>
Ctrl + w  delete from cursor to start of word (i.e. delete backwards one word)<br>
Ctrl + y  paste word or text that was cut using one of the deletion shortcuts (such as the one above) after the cursor<br>
Ctrl + xx  move between start of command line and current cursor position (and back again)<br>
Alt + b  move backward one word (or go to start of word the cursor is currently on)<br>
Alt + f  move forward one word (or go to end of word the cursor is currently on)<br>
Alt + d  delete to end of word starting at cursor (whole word if cursor is at the beginning of word)<br>
Alt + c  capitalize to end of word starting at cursor (whole word if cursor is at the beginning of word)<br>
Alt + u  make uppercase from cursor to end of word<br>
Alt + l  make lowercase from cursor to end of word<br>
Alt + t  swap current word with previous<br>
Ctrl + f  move forward one character<br>
Ctrl + b  move backward one character<br>
Ctrl + d  delete character under the cursor<br>
Ctrl + h  delete character before the cursor<br>
Ctrl + t  swap character under cursor with the previous one<br>

## Command Recall Shortcuts
Ctrl + r – search the history backwards<br>
Ctrl + g – escape from history searching mode<br>
Ctrl + p – previous command in history (i.e. walk back through the command history)<br>
Ctrl + n – next command in history (i.e. walk forward through the command history)<br>
Alt + . – use the last word of the previous command<br>

## Command Control Shortcuts
Ctrl + l – clear the screen<br>
Ctrl + s – stops the output to the screen (for long running verbose command)<br>
Ctrl + q – allow output to the screen (if previously stopped using command above)<br>
Ctrl + c – terminate the command<br>
Ctrl + z – suspend/stop the command<br>

## Bash Bang (!) Commands
!! – run last command<br>
!blah – run the most recent command that starts with ‘blah’ (e.g. !ls)<br>
!blah:p – print out the command that !blah would run (also adds it as the latest command in the command history)<br>
!$ – the last word of the previous command (same as Alt + .)<br>
!$:p – print out the word that !$ would substitute<br>
!* – the previous command except for the last word (e.g. if you type ‘find some_file.txt /‘, then !* would give you ‘find some_file.txt‘)<br>
!*:p – print out what !* would substitute<br>
