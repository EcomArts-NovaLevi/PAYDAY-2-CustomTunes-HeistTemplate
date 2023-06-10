# PAYDAY-2-CustomTunes-HeistTemplate

Hello!  Making PAYDAY 2 custom heist music is really simple!  I will do my best to explain it here, in regards to the files found within.

"loc" folder
This is the localization folder, put any localization files in all languages you'd like your music to appear in.  Default for english is features in this repository (en).

"sounds" folder
This contains the music itself in .ogg files:
setup - the stealth track
control_start - what plays when the control phase first initiates in game
control_loop - what plays immediately following the control intro, and loops until anticipation phase starts
buildup - anticipation phase
assault_start - what plays when the assault phase first begins
assault_loop - the assault phase music that plays following the intro, and until the assault phase is over

main.xml
.xml file that organizes how the sounds are read, and when they are played.  You can remove any part of the song's segments in game (which will cause nothing to play when that specific phase is initiated, of course!); the only two that you can remove when not needed/used are control_start and assault_start.

track.txt
This file designates the volume (read from 0 to 1, using decimal values between) as well as how the .xml file reads from the file to the game engine.
