Target 30fps

1. Go to terminal
2. add https://terra.fyralabs.com/ repo
	1. if on ultramarine you already have this
	2. `doas dnf group install stardust-xr`
3. `stardust-xr-server -f` to test
4. `telescope -f` to test
	2. shift+WASDQE movement
	3. shift+right click look
	4. Mouse button 5 for grab
	5. click hexagon launcher
	6. grab app out (blender)
	7. show interacting with it and exiting it
5. run monado/wivrn
	1. If struggling, ask in LVRA
6. `telescope` for overlay
	1. Record readback
	2. Explain `--disable-hands`
	3. `hexagon_launcher`
		1. tap the center to open/close
			1. green means captured which means it registered input
		2. grab the app out, drop where you wanna launch
	4. `flatland`
		1. grab corner handles with grip or pinch to move
		2. left click is trigger
		3. stick click is middle mouse
		4. right click is b button
		5. explain that the grab ball is for panel shells that are currently broken
		6. show close button
	5. `black-hole`
		1. found on left controller or back of wrist
		2. tap with index finger to toggle minimize
	6. `non-spatial-input`
		1. what if we want to get desktop keyboards in?
		2. `manifold` is to get keyboard/mouse from 2D desktop
		3. `simular` beams keyboard to whatever you're looking at
		4. `manifold | simular`
		5. click into the window
		6. show using this in blender
	7. `comet`
		1. launch from terminal inside stardust
		2. grab with controller grip or curl middle, ring, pinky near it
		3. to draw use trigger or pinch with index+thumb
7. `stardust-xr-server`
	1. `~/.config/stardust/startup`
	2. put flatland, hexagon_launcher, etc. in there
	3. launch server
	4. `atmosphere`
		1. `atmosphere install the_grid` from https://github.com/StardustXR/atmosphere/tree/dev/default_envs/the_grid
		2. `atmosphere list`
		3. `atmosphere set-default the_grid`
		4. `atmosphere show`
		5. grab the world
8. Support
	1. Stardust support in LVRA stardust channel or stardust xr server support channel