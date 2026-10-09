# Fern Hollow — browser playtest

Play at **https://www.edianibarrola.com/dinogame/**.

This repository contains the published Unity WebGL player. Editable Unity and Blender source belongs in the private `dinogamesource` repository.

PC: WASD/arrows, Shift sprint, Ctrl sneak, hold Space/mouse to bite, hold E to eat, hold F to drink. Phone: landscape, floating joystick anywhere outside the action buttons; toggle Sprint/Sneak, hold Bite/Eat/Drink. The game is an early single-player survival test. Growth, hatching, nests, saves and playable herbivore are not implemented yet.

Serve `index.html` over HTTP/HTTPS. Unity gzip fallback files use `.unityweb`, allowing GitHub Pages hosting without custom compression headers. `.nojekyll` keeps player files intact. No private source or credentials are included.
