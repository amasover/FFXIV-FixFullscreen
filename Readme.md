Note: as of Auguest 3, 2020, Windows Defender is detecting the executable as [Behavior:Win32/Atosev.A1sms](https://www.microsoft.com/en-us/wdsi/threats/malware-encyclopedia-description?Name=Behavior:Win32/Atosev.A!sms&threatId=-2147237347). Basically a generic "something looks fishy". I think Windows Defender doesn't like the hooking/injection method. Please review the source code if you have any concerns.

About
=====

This program fixes FFXIV refreshing the screen resolution when switching into the game window in a multi-monitor environment.

Usage
=====

1. Extract both the exe and the dll to the same folder somewhere on your computer.
2. Launch FFXIV client (the game must be fully launched and the game executable must be called ffxiv_dx11.exe).
3. Run ffxiv-fixfullscreen.exe. Note that you'll most likely need to run as administrator for it to work.

Note: This only works with FFXIV DX11. The DX9 version of the game client doesn't seem to have this problem

Disclaimer
=====
Use of this program is at your own risk. Square Enix does not permit the use of any third party tools, even those which do not modify the game.
