# Bermuda Syndrome


## About

This program is a re-implementation of the engine used in the game Bermuda
Syndrome made by Century Interactive (now [Reakktor Studios](http://www.reakktor.com))
and published by BMG in 1995. The original data files for either the full
or demo version of the game are required.

This rewrite is based on reverse engineering of the original Windows executable.
More information about the game can be found on
[Mobygames](http://www.mobygames.com/game/bermuda-syndrome).


## Running

By default, the engine will try to load the game data files from the `DATA`
directory. The savestates are saved in the current directory. If you have the
CD game soundtrack, you can rip the tracks to 22 Khz stereo Vorbis `.ogg` files.

For the Korean version of the game, you will also need the `BT16.TBM` file from
a Windows 3.x installation. The file is 330328 bytes long and should be copied
in the same directory as the `bs` executable.


### Command-line arguments

```
	Usage: bs [OPTIONS]...
  	--datapath=PATH    Path to data files (default 'DATA')
  	--savepath=PATH    Path to save files (default '.')
	--musicpath=MUSIC  Path to music files (default 'MUSIC')
	--fullscreen       Fullscreen display
	--widescreen=MODE  Widescreen mode ('default', '4:3' or '16:9')
```

### Game controls

```
	Arrow Keys      move Jack
	Tab             display bag
	Ctrl            display status bar
	Shift/Space     use weapon
	Enter           skip dialogue speech
```

### Other hotkeys

```
	C		capture screenshot as .tga
	S               save game state
	L               load game state
	+               increase game state slot
	-               decrease game state slot
	F               enable fast mode
	W               toggle fullscreen/windowed display
```
