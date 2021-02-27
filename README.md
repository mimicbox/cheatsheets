# cheatsheets TODO: Organize this thing

All of my cheatsheets for pentest/ctf

Sourced from around the web, or compiled by myself


## Payloads
https://github.com/swisskyrepo/PayloadsAllTheThings
Hugely helpful repo of pretty much everything payload

## Reverse Shells
https://highon.coffee/blog/reverse-shell-cheat-sheet/

## Upgrading a Shell to tty (including ctrl+c and tab complete)
```bash
python3 -c 'import pty; pty.spawn("/bin/bash")'
```
```
ctrl + z
stty -a <--- take note of rows and columns
stty raw -echo; fg
stty rows <x> columns <y>
```
Further info:
https://blog.ropnop.com/upgrading-simple-shells-to-fully-interactive-ttys/

## Session Hijacking
https://resources.infosecinstitute.com/topic/session-hijacking-cheat-sheet/

## GTFOBINS(exploiting UNIX binaries)
https://gtfobins.github.io/

## OWASP Cheatsheet series
https://github.com/OWASP/CheatSheetSeries

## Active Directory Exploitation
https://github.com/S1ckB0y1337/Active-Directory-Exploitation-Cheat-Sheet

## REGEX (Because who remembers regex)
https://cheatography.com/davechild/cheat-sheets/regular-expressions/

https://pythex.org <--- great tool to test REGEX for python

## Python
https://www.pythoncheatsheet.org/

## CTF Resources (Including links to CTFs themselves)
https://github.com/apsdehal/awesome-ctf

## Linux Priv Escalation
https://blog.g0tmi1k.com/2011/08/basic-linux-privilege-escalation/

## Windows Priv Escalation
https://infosecwriteups.com/privilege-escalation-in-windows-380bee3a2842

## HTTP Headers
https://kapeli.com/cheat_sheets/HTTP_Header_Fields.docset/Contents/Resources/Documents/index

## OSINT Framework
https://osintframework.com/


