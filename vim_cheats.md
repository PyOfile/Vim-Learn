# Vim Text Editor Cheats

## Spell check:
```
:set spell
```
## Numbers:
```
:set number
```
#
## Quitting:
#
#### Exit as long as there have been no changes:
```
:q
```
#### Exit and save changes if any changes have been made:
```
:wq
```
#### Exit and ignore any changes:
```
:q!
```
#
## Inserting Text:
#
#### Insert before cursor:
```
i 
```
#### Insert before line:
```
I
```
#### Append after cursor:
```
a 
```
#### Append after line:
```
A 
```
#### Open a new line after current line:
```
o 
```
#### Open a new line before current line:
```
O 
```
#### Replace one character:
```
r
```
#### Replace many characters:
```
R 
```
#
## Deleting Text:
#
#### Delete character to the right of cursor:
```
x
```
#### Delete character to the left of cursor:
```
X 
```
#### Delete to the end of the line:
```
D
```
#### Delete current line:
```
dd 
```
#
## Yanking Text:
#
#### Yank the current line:
```
y 
```
#
## Changing Text:
#
#### Change to the end of the line:
```
C
```
#### Change the whole line:
```
cc
```
#
## Putting Text:
#
#### Put after the position or after the line:
```
p
```
#### Put before the position or before the line:
```
P 
```
#
## Search for strings:
#
#### Search forward for string:
```
/string
```
#### Search back for string:
```
?string
```
#### Search for next instance of string:
```
n 
```
#### Search for previous instance of string:
```
N
```
#
## Replace:
#
#### Replace pattern with string according to flags:
```
:s/pattern/string/flags
```
#### Flag - Replace all occurrences of pattern:
```
g 
```
#### Flag - Confirm replaces:
```
c
```
#### Repeat last :s command:
```
&
```
#
## Motion:
#
#### Move left:
```
h
```
#### Move down:
```
j
```
#### Move up:
```
k
```
#### Move right:
```
l
```
#### Move to next word:
```
w
```
#### Move to next blank delimited word:
```
W
```
#### Move to the beginning of the word:
```
b
```
#### Move to the beginning of blank delimited word:
```
B
```
#### Move to the end of the word:
```
e
```
#### Move to the end of Blank delimited word:
```
E
```
#### Move a sentence back:
```
(
```
#### Move a sentence forward:
```
)
```
#### Move a paragraph back:
```
{
```
#### Move a paragraph forward:
```
}
```
#### Move to the beginning of the line:
```
0
```
#### Move to the end of the line:
```
$
```
#### Move to the first line of the file:
```
1G
```
#### Move to the last line of the file:
```
G
```
#### Move to nth line of the file:
```
nG
```
#### Move to nth line of the file:
```
:n
```
#### Move to top of screen:
```
H
```
#### Move to middle of screen:
```
M
```
#### Move to bottom of screen:
```
L
```
#### Move to associated ( ), { }, [ ]:
```
%
```
#### Move forward to the next occurrence of the letter c in the current line:
```
fc
```
#### Move backward to the next occurrence of the letter c in the current line:
```
Fc 
```
#
## Other:
#
#### Toggle upper and lower case:
```
~ 
```
#### Join lines:
```
J 
```
#### Repeat last text-changing command:
```
. 
```
#### Undo last change:
```
u 
```
#### Undo all changes to line:
```
U
```
#
