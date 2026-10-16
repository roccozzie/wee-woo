# Wee Woo - Ozzie's Ambulances

a no-fail ambulance feed for a 1.5-year-old, built to the same pattern as Rocco's Garage.

- every touch does the thing: tap the ambulance = siren blast + bounce; any swipe, drag or palm slap = next ambulance. no buttons, no menus, no fail states, no words to read
- ambulances are procedurally mixed so it does not repeat: 4 body types (box, van, euro, chunky mini) x 7 color schemes x 7 scenes (city day, city night, desert, snow, farm, beach, rain) x 4 sirens = 784 combos
- sirens are synthesized in code with WebAudio (slow wail, fast yelp, european hi-lo - the true wee-woo, phaser) - no audio files. each blast runs about 3 seconds and quiets on its own while the lights keep flashing
- parent corner: long-press (1.5s) the top-right corner for siren volume and mute
- single self-contained `index.html`, just open it or serve it statically. on an iphone, lock him in with Guided Access so palm mashing cannot leave the page

Live: https://wee-woo-gamma.vercel.app (Vercel project wee-woo, git-linked to this repo - pushes to main auto-deploy; wee-woo.vercel.app was already taken, so Vercel assigned the -gamma name). Sibling game: Rocco's Garage (https://github.com/roccozzie/roccos-garage).
