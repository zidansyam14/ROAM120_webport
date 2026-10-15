ROAM0120 - web port (WebAssembly)

HOW TO RUN
1. Extract BOTH zips into the same place, so you end up with two folders side by side:
     ROAM0120-web/          (this folder: the game + images)
     ROAM0120-web-sounds/   (the audio)
2. Open ROAM0120-web/index.html in Chrome, Edge or Firefox (double-click works, no server needed).
3. Click "CLICK TO START".

SINGLE-FILE VERSION
On the start screen, "SAVE AS A SINGLE .HTML FILE" builds one self-contained
ROAM0120.html (about 56 MB) and downloads it. That file needs nothing else,
like an Eaglercraft offline build. It needs both folders present to build.

CONTROLS
Mouse: look around / click hotspots. Arrow keys: change camera angle where shown.
Esc closes the close-up views and mini-games, as in the original.
F4: toggle fullscreen.

NOTES
- The engine is a from-scratch reimplementation of the GameMaker Studio 1.4 runner,
  running the game's original bytecode in WebAssembly.
- Photo texture pages are stored as high-quality WebP (q92); UI, text and cursor
  textures are lossless.
- Dying ends the game, exactly like the original (it closed the window). Use
  "PLAY AGAIN" to restart.
- The original has no save system, so neither does this port.
- Safari is not supported for sound (no Ogg Vorbis decoding).
