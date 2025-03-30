# Kya DL Cheat Engine tables
These cheat tables are for PCSX2 ≥2.0
## Guide (from PCSX2 Discord):  
1. Download latest emurpm.lua and emurpm.frm from CE's GitHub (https://github.com/cheat-engine/cheat-engine/tree/master/Cheat%20Engine/bin/autorun) 
1. Put them into autorun folder (%programfiles%\Cheat engine x.y\autorun\)
1. (Re)Boot CE and open PCSX2 from process list
1. Click "Emulator Memory" > "Set Base Address"
1. Type [eemem] to first text box and type 0x02000000 to "Size of Memory", then click "(Re)Set address"
1. If you want to open an already existing cheat table, do so now
1. Execute following script on "Cheat Table Lua script" (shortcut: Ctrl+Alt+L) (in case of the table in this repo, you can just confirm the popup that shows when you open it)
```
setPointerSize(4)
setAssemblerMode(0)
```
With this procedure, the addresses and offsets stored in the cheat table will match the values they'd have on the actual hardware, so they also be directly used to write cheat codes

  

    
Legacy note: PCSX2 1.6 instead always maps EEmem to 0x20000000, but please try to migrate to 2.0 as it's more accurate, seems to be faster, has useful features (like frame advance), and will shortly replace 1.6 as the stable release anyway
