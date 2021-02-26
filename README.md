# cheatsheets

All of my cheatsheets for pentest/ctf

Sourced from around the web, or compiled by myself


# Payloads
https://github.com/swisskyrepo/PayloadsAllTheThings
Hugely helpful repo of pretty much everything payload

# Reverse Shells
https://highon.coffee/blog/reverse-shell-cheat-sheet/

# Upgrading a Shell

python3 -c 'import pty; pty.spawn("/bin/bash")'

then ctrl + z
stty -a <--- take note of rows and columns
stty raw -echo; fg
stty rows <x> columns <y>
