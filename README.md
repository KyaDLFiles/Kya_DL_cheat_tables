# Kya_DL_cheat_tables
These cheat tables are for PCSX2 1.7
Guide (from PCSX2 Discord):
1. Download latest emurpm.lua and emurpm.frm from CE's GitHub (https://github.com/cheat-engine/cheat-engine/tree/master/Cheat%20Engine/bin/autorun) 
1. Put them into autorun folder (%programfiles%\Cheat engine x.y\autorun\)
1. (Re)Boot CE and open PCSX2 from process list
1. Click "Emulator Memory" > "Set Base Address"
1. Type [eemem] to first text box and type 0x02000000 to "Size of Memory", then click "(Re)Set address"
1. Execute following script on "Cheat Table Lua script" (shortcut: Ctrl+Alt+L)
```
setPointerSize(4)
setAssemblerMode(0)
```
