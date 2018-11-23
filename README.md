Keylogger
=========

Simple FTP Python Keylogger for Windows only. -Alex Avlonitis- http://alex.avlonitis.me


Required:<br/>
Python 2.7 32bit: http://www.activestate.com/activepython/downloads<br/>
Pyhook: http://sourceforge.net/projects/pyhook/

How it works:<br/>
First it checks if there is a keys.txt file under %appdata% folder.<br/>
If there isn't, it creates one and starts recording keystrokes immediately.<br/>
It uploads the keys.txt file on the ftp server every time you run the script.<br/>
To exit press escape
