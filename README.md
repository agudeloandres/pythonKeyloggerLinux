# pythonKeyloggerLinux

pyxhook requires python-xlib. Install it if you don't have it already. 

sudo apt-get install python-xlib

OnKeyPress - is the function which executes every time a key is pressed.
here, the log file is opened in append mode and the keystrokes are appended to the log file. a new line character is written to the file to get the keys on new lines.

if the grave key (it's the key below esc key) is pressed the log file is closed and session is terminated.


you can get more events information like time of the event, event window name  and Mouse events can also be tracked, you can refer to the documentation in link below.

pyxhook doesn't have any official documentation but the pyhook documentation works fine for most of the stuff.

Resources:
pyHook API documentation [http://pyhook.sourceforge.net/doc_1.5.0/]

