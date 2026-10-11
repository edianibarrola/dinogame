# Fern Hollow — browser playtest

Play at **https://www.edianibarrola.com/dinogame/**.

This repository contains the published Unity WebGL player. Editable Unity and Blender source belongs in the private `dinogamesource` repository.

Choose Rex, Raptor, Triceratops or Ankylosaurus. Resume your saved life, hatch or try an adult. Each species retains its own local bloodline and eggs. Growth takes 12 healthy active minutes; Test tools offer stage selection and 5x growth/incubation. Healthy adults can meet a same-species mate, lay two eggs and hatch a ready offspring. Functional inheritance and cosmetics remain deferred.

PC: WASD/arrows, Shift sprint, Ctrl sneak, hold Space/mouse for a forward bite, Q/right click for Roar/Pounce/Charge/rear Tail sweep, hold E to eat, hold F to drink, R for scent. Tab/Esc opens bloodlines, T opens Test tools, N lays an eligible nest. Phone: landscape, floating joystick anywhere outside the action buttons; toggle Sprint/Sneak, hold Bite and contextual Eat/Graze/Drink and tap the separate species ability button.

Explore a bounded island with beach, plains, forest and five freshwater sources. Ocean water is undrinkable. Small crabs are hatchling prey; carcasses provide different finite food amounts. Raptors are threats; herbivores defend when provoked. Crabs and mammals protect territory against hatchlings and flee grown dinosaurs. Connected tree crowns, reliable mate lookup and persistent AI resource routes improve the island playtest. Orbiting gold stars show stuns, and small icons replace AI behavior labels. Compact survival meters and action docks keep the play view clearer; Test tools are accessed through bloodlines or T. This is an early single-player playtest. Saves belong to this browser/device; real phone performance, caves and multiplayer remain future work.

Serve `index.html` over HTTP/HTTPS. Unity gzip fallback files use `.unityweb`, allowing GitHub Pages hosting without custom compression headers. `.nojekyll` keeps player files intact. No private source or credentials are included.


The October 11 habitat pass reshapes the coast with bays, spreads 62 initial AI animals through feeding areas and shore habitats, and adds gradual population renewal. Blocking scenery uses the rendered rock/trunk mesh, with a recorded collision audit. Predators remember fleeing players, rex roar leaves a usable follow-up attack window, and corpse food stocks are reduced by body size.

Touch interaction adapts to Eat/Graze/Drink and stays locked until release; a small alternate appears beside overlapping food and water. Scent (R or the touch button) gives short approximate bearings for nearby animals, food and freshwater. Hatching hides the normal HUD, and both 960x540 and 812x375 touch layouts are checked. Existing bloodlines and eggs are preserved; the old NPC population refreshes once for the new habitats. Quests and skin work remain deferred.

The group and escape update adds predator fatigue, cautious herbivores and local protection for youngsters. Spend time with healthy adults of your species to earn acceptance; parents respond from farther away. Groups assess threats, limit interceptors and retreat when outmatched, so protection depends on the situation.

Connected tall grass and fern beds now support hiding: crouch quietly inside for a moment, then stay quiet. Sprinting or attacking reveals you, and big adults cannot disappear in low grass. Predators search your last sighting. An eye indicator shows whether you are concealed, spotted or too tall for the cover.

Scent now forms a compass around your dinosaur, using shared illustrated icons. Mouse wheel, HUD +/- and two-finger background pinch control zoom. Movement plus an action touch still works normally. Hatching opens the shell before revealing the baby. The population refreshes once for these habitats and groups; player bloodlines and eggs are retained.
