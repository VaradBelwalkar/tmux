# tmux
Configuration file for tmux user sessions  
To copy content, just do control + b  then [ then using arrow keys get to the content and enter SPACE to start selecting, then once done, press ENTER

Alternatively, simply scroll using mouse and select the text and once you remove your finger from mouse click you will return to original last prompt where you left,

with the text copied.

Then to paste the content, just press CTRL + B then press ] to paste the copied test

This is the tmux buffer which you are using, to copy this content to your system's clipboard, just enter following command while in tmux session: 
```    
tmux show-buffer | xclip -selection clipboard 
```
This will copy to system's clipboard and you are ready to go :)

To paste teh system clipboard content, just hold shift, then do ctrl+v

Simple and easy to learn key bindings for tmux

| Description | Command |
|-----------|--------|
Create new window | `alt+f` |
Go to previous window |`alt+j` |
Go to next window | `alt+l` |
Detach current session | `alt+d` |
Rename current window | `alt+r` |
Rename current session | `alt+s` |
Go to next session | `alt+k` |
Go to previous session | `alt+i` |
Create horizontal pane | `alt+h` |
Create vertical pane | `alt+v` |
Go to left pane | `alt+,` |
Go to right pane | `alt+.` |
Go to upper pane | `alt+g` |
Go to below pane | `alt+n` |





## Using Tmux in Windows

To use tmux in windows, first install any distro of your choice on WSL, once installed, install tmux according to the distribution's docs,  
and after that, simply start it.

You may ask i want the tmux to be working in windows environment right?

Well it is pretty simple, simply run `powershell.exe` in the terminal and woh!  
Powershell with windows info just got up right,

now simply do `cd C:` and yup, you got into windows file system!

Now you can use tmux in windows as if you are running it in windows itself.





