# apc40-linux
midi bindings to connect an APC40 controller to ardour and sequencer64

***Midi bindings for APC40 on ardour5***

-Copy the folder midi_maps to ~/.config/ardour5/

-The 8 faders control volume fader of bank tracks, master controls master fader.
-The 3 buttons above each fader controls mute, solo and rec for each bank track
-The 8 Track Control pots control pan direction on respective bank tracks
-Bank select left and right select previous and next track bank
-Play, Stop and Rec for respective global controls


***Midi bindings for APC40 on seq64***

-Copy sequencer64.rc to ~/.config/sequencer64/

-The 4 first lines of clip launch: launch respective clips in current set

-The 5th line of clip launch trigger mute groups with patterns from 01 up to 07 on the respective 7 first buttons

-4 first buttons of scene launch columns launch full-line mute groups (keys * I K < , left vertical raw)

-The stop buttons stop the respective columns

-Bank Select up for next set, down for previous set

-"Stop all clips" to activate Replace mode

-"Shift" to activate Keep Queue mode. (Note: There's a bug when using "off" control on queue mode, which makes mute-group shortcuts broken, so people should use Ctrl_right on keyboard to disable keep queue.)

-Nudge- to reduce bpm, Nudge+ to increase it

Side note:
-Replace doesn't work with queue

