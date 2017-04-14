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

-The 4 first lines of "Clip launch": launch respective clips in current set

-The 5th line of "Clip launch" trigger mute groups with patterns from 01 up to 07 on the respective 7 first buttons (mute groups from keys shift + 1 to 7)

-The 4 first buttons of "Scene launch" column launch full-line mute groups (from keys shift + 8 i k ;)

-The 5th "Scene launch" button activates the Snapshot mode. The button on its left restores the snapshot (the bottom-right button of "Clip launch").

-The "Clip stop" buttons stop the respective columns

-"Bank Select" up for next set, down for previous set

-"Stop all clips" activates the Replace mode

-"Shift" activates the Keep-Queue mode. (Note: There's a bug when using "off" control on queue mode, which makes mute-group shortcuts broken, so people should use Ctrl_right on keyboard to disable keep queue.)

-"Nudge-" reduces bpm, "Nudge+" increases it

Side notes:

-You can combine Snapshot and Replace (first press snapshot, then replace, then the new patterns, then restore)

-Replace doesn't work with queue

