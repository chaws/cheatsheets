Basics
k navigate upwards
j navigate downwards
l navigate right side
h navigate left side
0 go to the starting of the current line
^ go to the first non blank character of the line
$ go to the end of the current line
g_ go to the last non blank character of the line
H – Go to the first line of current screen
M – Go to the middle line of current screen
L – Go to the last line of current screen
ctrl+f – Jump forward one full screen
ctrl+b – Jump backwards one full screen
ctrl+d – Jump forward (down) a half screen
ctrl+u – Jump back (up) one half screen

Folding
https://stackoverflow.com/questions/2362914/fold-function-in-vim
zf#j creates a fold from the cursor down # lines
zf/ string creates a fold from the cursor to string
zj moves the cursor to the next fold
zk moves the cursor to the previous fold
za toggle a fold at the cursor
zo opens a fold at the cursor
zc closes fold under cursor
zO opens all folds at the cursor
zc closes a fold under cursor
zm increases the foldlevel by one
zM closes all open folds
zr decreases the foldlevel by one
zR decreases the foldlevel to zero -- all folds will be open
zd deletes the fold at the cursor
zE deletes all folds
[z move to start of open fold
]z move to end of open fold
