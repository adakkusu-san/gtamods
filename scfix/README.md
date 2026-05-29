# scfix

Decided to make them separately instead

I used the minimum-necessary mainscm to test these, I don't guarantee it's 
gonna work in a save-game but I'll try

Please let me know if there's a way to easily see the amount of bytes the 
opcodes would take, so I don't have to compile/decompile them or make it up 
in my mind every time; it's to do with offsets because a save-game needs 
the same exact offsets for the MAIN script and such, else it'll goto in the 
middle of an opcode and most likely crash

note to me: tried to change in a way that won't break saves and make sure 
compiler is happy and game won't crash