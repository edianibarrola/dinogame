# Fern Hollow — browser playtest

Play at **https://www.edianibarrola.com/dinogame/**.

This repository contains the published Unity WebGL player. Editable Unity and Blender source belongs in the private `dinogamesource` repository.

Choose Rex, Raptor, Triceratops or Ankylosaurus. Resume your saved life, hatch or try an adult. Each species retains its own local bloodline and eggs. Growth takes 12 healthy active minutes; Test tools offer stage selection and 5x growth/incubation. Healthy adults can meet a same-species mate, lay two eggs and hatch a ready offspring. Eggs carry distinct, saved genetic bonuses. Living parents stay on the island, and Family lets you return to living relatives. Customize fresh hatches with separate body/accent/pattern colors, pattern type and pattern size; collected looks are saved per species.

PC: WASD/arrows, Shift sprint, Ctrl sneak, hold Space/mouse for a forward bite, Q/right click for Roar/Pounce/Charge/rear Tail sweep, hold E to eat, hold F to drink, R for scent. Tab/Esc opens bloodlines, T opens Test tools, N lays an eligible nest. Phone: landscape, floating joystick anywhere outside the action buttons; toggle Sprint/Sneak, hold Bite and contextual Eat/Graze/Drink and tap the separate species ability button.

Explore a bounded island with beach, plains, forest and twenty-five freshwater sources. Ocean water is undrinkable. Small crabs are hatchling prey; carcasses provide different finite food amounts. Raptors are threats; herbivores defend when provoked. Crabs and mammals protect territory against hatchlings and flee grown dinosaurs. Connected tree crowns, reliable mate lookup and persistent AI resource routes improve the island playtest. Orbiting gold stars show stuns, and small icons replace AI behavior labels. Compact survival meters and action docks keep the play view clearer; Test tools are accessed through bloodlines or T. This is an early single-player playtest. Saves belong to this browser/device; real phone performance, caves and multiplayer remain future work.

Serve `index.html` over HTTP/HTTPS. Unity gzip fallback files use `.unityweb`, allowing GitHub Pages hosting without custom compression headers. `.nojekyll` keeps player files intact. No private source or credentials are included.


The October 11 habitat pass reshapes the coast with bays, spreads 62 initial AI animals through feeding areas and shore habitats, and adds gradual population renewal. Blocking scenery uses the rendered rock/trunk mesh, with a recorded collision audit. Predators remember fleeing players, rex roar leaves a usable follow-up attack window, and corpse food stocks are reduced by body size.

Touch interaction adapts to Eat/Graze/Drink and stays locked until release; a small alternate appears beside overlapping food and water. Scent (R or the touch button) gives short approximate bearings for nearby animals, food and freshwater. Hatching hides the normal HUD, and both 960x540 and 812x375 touch layouts are checked. Existing bloodlines and eggs are preserved; the old NPC population refreshes once for the new habitats. Quests remain deferred; the latest family/genetics/appearance milestone is described below.

The group and escape update adds predator fatigue, cautious herbivores and local protection for youngsters. Spend time with healthy adults of your species to earn acceptance; parents respond from farther away. Groups assess threats, limit interceptors and retreat when outmatched, so protection depends on the situation.

Connected tall grass and fern beds now support hiding: crouch quietly inside for a moment, then stay quiet. Sprinting or attacking reveals you, and big adults cannot disappear in low grass. Predators search your last sighting. An eye indicator shows whether you are concealed, spotted or too tall for the cover.

Scent now forms a compass around your dinosaur, using shared illustrated icons. Mouse wheel, HUD +/- and two-finger background pinch control zoom. Movement plus an action touch still works normally. Hatching opens the shell before revealing the baby. The population refreshes once for these habitats and groups; player bloodlines and eggs are retained.


## Family and appearance milestone

Each species supports up to eight living owned dinosaurs, separate from wild AI. Hatching preserves the parent as a vulnerable resident; family control restores the chosen individual, genes and appearance. Switching is blocked by active threats and recent combat. An individual lives for 45 active minutes; offline time does not age the island. Wild adult pairs can produce bounded inherited offspring, with growth, population limits and saved recovery timers.

Nine genetic stats have modest species-independent limits and a 36-point total cap. Each generation gains one point in adult potential beyond the stronger parent until the limit, with an occasional extra point mutation. Shared traits persist, and clutch siblings remain the same generation. Compare both eggs before choosing.

Appearance Studio offers twelve colors and Plain, Spots, Stripes, Side stripe, Patches, Rings, Diamonds and Freckles. Body color, belly color, secondary color, pattern color, pattern type and pattern size are independent. Looks belong to one dinosaur species and can be collected and reused for fresh hatches or chosen offspring. New offspring may inherit appearance components and an occasional color variation separately from genes. Preview skins on the actual model; further visual tuning remains welcome.

Hunting commitments now survive repeated bites, and actual movement determines stamina use. AI feeding reservations are local. The lower Rex back stripe deforms less in the corrected drinking pose. Ten springs, distinct dinosaur home groups and twenty-two cover areas support the island.

Validation: 265 native gameplay checks, including a 2,000-generation genetic simulation, plus desktop and two emulated phone browser layouts. Physical phone performance remains unverified. Quests, caves, multiplayer, paid cosmetics and fully modeled carcass stages remain future work.


## Skin and ecology rework

Explicit belly/secondary/marking regions, eight patterns, a named editable thumbnail collection and per-species progress unlocks replace the initial skin controls. Replacement hatches preserve genes without rerolling. Fifty-two target wild animals travel among eighteen feeding grounds and freshwater sources, avoid observed danger and return toward shelter; resource stocks persist and recover gradually. Smaller dinosaur bodies provide less food.

Validated with 265 native checks, a ten-minute autonomous ecology simulation, five editor browser layouts (including portrait and high-DPI touch) and three survival browser layouts. Physical phone performance still needs playtesting.

Final follow-up seats the Triceratops horn roots into the head. Thirty-four additional gameplay scenarios verify starter resource routes, actual hatchling interactions, finite feeding and an active predator escape. The private source includes an engagement rubric separating mechanical release checks from human judgments of long-term enjoyment.

Navigation now caches conservative clearance for each creature size range, preventing an adult from reusing hatchling-sized gaps. Adult freshwater routes are checked after smaller animals have used the navigation cache.


## October 14 survival pass

The expanded island has about 87% more land area, ten freshwater sources and eighteen feeding grounds. Critter renewal continues after sustained hunting; vegetation recovers gradually. Predators finish brief inspection pauses and commit to appropriate hunts. Temporary food thought bubbles show meat/plant searches; combat alerts take priority.

Each two-egg clutch offers visibly different appearances when both would otherwise match, including original-parent clutches. Egg choices name the appearance before hatching. Existing unlocks, families and saved looks are preserved; retrying death cannot reroll offspring.

Guided survival playthroughs exercise normal movement, feeding, drinking, growth, nesting, incubation and offspring selection with live AI, in addition to native regression and browser touch checks. Controllers have map knowledge and accelerated time; human enjoyment and real-phone performance still require playtesting.

Herbivore parents prioritize local youngster protection before general avoidance. NPC needs and family aging pause on the death screen while you choose a next life. New-process checks restore offspring identity, inherited stats, rendered appearance and the living parent.

## Territorial island update

The larger, irregular island supports three wild families of each dinosaur species, with 78 wild animals as its population target. Local home ranges, nearby food and freshwater, off-camera replenishment and saved raised-family homes reduce crowding and long-distance targeting. Actual family members are excluded from attacks; other raised species remain vulnerable. Bites and pounces retain their chosen target, and unrelated wild Rexes can be stunned by roar. Raised animals have a small family marker and rate-limited attack warnings. This build passes 341 native checks, fresh and full-family ecology runs, survival-to-offspring journeys and browser touch checks. Physical-phone performance still needs playtesting.


## AI timing stability

Group defenders commit to a stable retreat and require clearer recovery before fighting again. Herbivore alerts use separate enter/leave distances. AI strikes keep their windup target and cannot transfer or repeat damage. Verified with 351 full native regression checks, 25 timing checks including actual 15/30/60/120 FPS hunts and alert-boundary tests, and desktop plus two emulated touch-browser layouts. Earlier ecology and journey reports refer to the preceding territory release. Physical-phone performance remains unverified.
