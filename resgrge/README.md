restore some (unused?) garages

note: needs grgx

some `dff`s are facing the wrong way, and such the camera when going in 
is pointing the wrong direction, possibly the reason these are 'broken'

I tried rotating the `dff`s until the camera is right, but it's optional, 
you don't need to replace them unless you don't mind the camera being 
kinda wrong

you may need to extract binary IPLs and edit some of them but I'm not sure yet, 
and also edit some data files, I'll document my edits anyway

~~I'll extract my binary IPLs and do the changes myself, so all you have to do is 
extract the files and go to the locations~~ done it

please open `changes.txt` to see what to do, or extract `binary.zip` in a folder 
in modloader

then also copy resgrge.cs and loader.txt in there and it should work\
I've not really tested from a savegame

Currently, the following garages are restored or fixed

* wuzi's garage (original changes type in a mission but doesn't do anything more)
* the SF bombshop (original doesn't have a name and can't be used; in the mission 
you're teleported to an interior; dff also faced sideways for some reason)
* the big garage from pier69 (also doesn't have a name; the mission doesn't 
even use it; dff faced the wrong way I think)
* LV pay'n'spray (with bugged entrance collision, but fixed the camera to 
be outside, dff was facing the wrong way)
* the LV bombshop (camera follows player instead of pointing from the back of 
the garage(??), maybe the dff is facing the wrong way but I couldn't get it 
to work)

TODO: maybe I don't need to recreate them in the script, I could just edit 
the IPL files, we'll see. I did it in a script because IPLs were not reliable 
for me when loaded in a savegame, but I don't know

Also for testing purposes, I'll make it so you can also use these mission garages, 
but not currently implemented, these are TODO

* that one in some SF mission where you follow bikes
* some garage in a mission a bit before the final one
* one in the bottom-left part of map, from a SF mission
* the burg garages
* following are not mission garages, but an object is moved; remove the object 
or make it invisible or something idk
* "garage" behind wuzi's place
* "garage" behind four dragons place
* there might be more, that's every I could think of

* note: the doherty garage thing is empty inside when not in the interior world, 
there's better mods out there to restore it and make it functional
