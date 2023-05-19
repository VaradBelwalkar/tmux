# tmux
Configuration file for tmux user sessions
TO COPY CONTENT, JUST DO CTRL + B then [ then using arrow keys get to the content and enter SPACE to start selecting, then once done, press ENTER

ALTERNATIVELY, simply scroll using mouse and select the text and once you remove your finger from mouse click you will return to original last prompt where you left,

with the text copied.

Then to paste the content, just press CTRL + B then press ] to paste the copied test

This is the tmux buffer which you are using, to copy this content to your system's clipboard, just enter following command while in tmux session: 
    
    tmux show-buffer | xclip -selection clipboard 
 
 This will copy to system's clipboard and you are ready to go :)
    
TO PASTE THE SYSTEM CLIPBOARD CONTENT, JUST HOLD SHIFT, THEN DO CTRL+V

Simple and easy to learn key bindings for tmux


Create new window: &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`alt+f`

Go to previous window:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`alt+j`

Go to next window:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`alt+l`

Detach current session:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`alt+d`

Rename current window:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`alt+r`

Rename current session:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`alt+s`

Go to next session:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`alt+k`

Go to previous session:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`alt+i`

Create horizontal pane:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`alt+h`

Create vertical pane:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`alt+v`

Go to left pane:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`alt+,`

Go to right pane:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`alt+.`

Go to upper pane:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`alt+g`

Go to below pane:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`alt+n`

