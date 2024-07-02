# Vim Advanced Cheat Sheet

## Basic
```
gg // go to first line of the file
G // go to last line of the file
o // new line bellow and insert
O // new line above and insert
_ // go to first char of the line
0 // start of line
$ // end of line
I // insert in start line
A // insert in end line
```

## Vertical move
```
* // go to next same word
zz // center your view or set the line you are at on the middle of the screen
Ctrl + d // half pagedown
Ctrl + u // half pageup
{ // top of paragraph whiteline on top of line 1
( // top of paragraph in line 1
) // bottom of paragraph
```

## Advance
```
ci( // remove whats inside the next () and insert
dt) // cut until )
vt) // select until )
vi( // select whats inside to next ()
vi{ // select whats inside to next {}
viW // selects all between whitespaces
ya{ // yank everything in between {} including {}
yiW // yank all between whitespaces
F) // go back to nearest ) closing bracket
F( // go back to nearest ( opener bracket
f) // go forward to nearest ) closing bracket
f( // go forward to nearest ( opener bracket
t( // jump 1 char before (
t) // jump 1 char before )
, // repeat the last command backwards
; // repeat the last command forward
```
