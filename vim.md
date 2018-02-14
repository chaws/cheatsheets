# Basics
k navigate upwards<br>
j navigate downwards<br>
l navigate right side<br>
h navigate left side<br>
0 go to the starting of the current line<br>
^ go to the first non blank character of the line<br>
$ go to the end of the current line<br>
g_ go to the last non blank character of the line<br>
H – Go to the first line of current screen<br>
M – Go to the middle line of current screen<br>
L – Go to the last line of current screen<br>
ctrl+f – Jump forward one full screen<br>
ctrl+b – Jump backwards one full screen<br>
ctrl+d – Jump forward (down) a half screen<br>
ctrl+u – Jump back (up) one half screen<br>

# Folding
From: https://stackoverflow.com/questions/2362914/fold-function-in-vim<br>
zf#j creates a fold from the cursor down # lines<br>
zf/ string creates a fold from the cursor to string<br>
zj moves the cursor to the next fold<br>
zk moves the cursor to the previous fold<br>
za toggle a fold at the cursor<br>
zo opens a fold at the cursor<br>
zc closes fold under cursor<br>
zO opens all folds at the cursor<br>
zc closes a fold under cursor<br>
zm increases the foldlevel by one<br>
zM closes all open folds<br>
zr decreases the foldlevel by one<br>
zR decreases the foldlevel to zero -- all folds will be open<br>
zd deletes the fold at the cursor<br>
zE deletes all folds<br>
[z move to start of open fold<br>
]z move to end of open fold<br>
You can also select multiple lines in Visual Line Mode (Shift+v) and fold them with zf<br>
