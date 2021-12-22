# DELA-EPROMMER-II 27512 Extension

This is a reproduction of the 27512 extension board from DELA-Elektronik for the DELA-EPROMMER II for the Commodore 64.  
The user instruction calls this add-on "Umbauset für den DELA-EPROMMER II"

This extension makes it possible to program 27512 EPROMS with the DELA-EPROMMER II by removing VPP from pin 1 and replacing it with the switch controlled address pin A15. A special version of the DELA EPROMMER software is needed which connects VPP to pin 22.  
The 27512 has to be programmed in two 32kB passes and there are two switches on the board, one for activation/deactivation of the extension and one for 32kB block selection (A15).

When this extension is active, the EPROMMER should only be used with a special version of the DELA EPROMMER software. If the extension is deactivated by the switch, it can be used with the standard software.

Dirk Wouters has created an excellent reproduction of the complete DELA-EPROMMER II which together with schematics, user manuals and standard software can be found at https://github.com/DL2DW/DELA-EPROMMER-II
