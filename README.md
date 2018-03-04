# McSpaces

At this moment, essentially a ready to use-ish tool to get the current fkn mission control space in use on macOS.

Platform: macOS
Tested on: 10.13.3
Result: PASS

Maybe I'll improve it... Or maybe you will.. this is GitHub after all :)


Please note:
The output is a UUID on all spaces except the first one. Actually that's a UUID too, but the value is simply an empty string. It is unique in that none of the other spaces have an empty string as their UUID.


Example usage:
```Bash
Pandora:ObjC jero$ gcc -o spaceID spaceID.m -framework Foundation -framework Carbon
Pandora:ObjC jero$ ./spaceID
67240BCE-9A57-43FD-AFA5-8640A87F41D5
Pandora:ObjC jero$ ./spaceID

Pandora:ObjC jero$ ./spaceID
3A3A75BE-723F-4C70-977D-F22749BE2363
Pandora:ObjC jero$ ./spaceID
67240BCE-9A57-43FD-AFA5-8640A87F41D5
```
(Note that I moved the terminal window between desktops inbetween running the commands...)
