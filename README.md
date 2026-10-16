# Wee Woo - Ozzie's Ambulances

a no-fail emergency-vehicle feed for a 1.5-year-old, built to the same pattern as Rocco's Garage. FOUR fleets - ambulances, fire trucks, police cars, garbage trucks - picked from a 2x2 grid on the title card or the corner buttons during play.

- every touch does the thing: tap the vehicle = its sound + bounce; any swipe, drag or palm slap = next vehicle. no fail states, no words to read
- each fleet has its own types, lights and sounds: ambulances (6 types, red/blue, 7 siren patterns incl. slow two-tone and wail-into-yelp); fire trucks (5 types, red/WHITE strobes, 7 sounds incl. mechanical Q spool-up, air horn, ringing bell, Q coast-down); police cars (4 types, red/blue at a faster tempo with white flashes, rumbler wail, priority yelp, whoop-whoop chirps); garbage trucks (4 types incl. a blue recycling variant, AMBER beacons only, and work sounds instead of sirens - compactor crunch, lift-and-dump, backup beeper + air-brake hiss, diesel rumble + horn)
- 12 scenes shared by all fleets: city day/night, desert, snow, farm, beach, rain, mountains, forest, autumn town, spring meadow, harbor
- ambulances are procedurally mixed so it does not repeat: 4 body types (box, van, euro, chunky mini) x 7 color schemes x 7 scenes (city day, city night, desert, snow, farm, beach, rain) x 4 sirens = 784 combos
- sirens are synthesized in code with WebAudio (slow wail, fast yelp, european hi-lo - the true wee-woo, phaser) - no audio files. each blast runs about 3 seconds and quiets on its own while the lights keep flashing
- parent corner: long-press (1.5s) the top-right corner for siren volume and mute
- single self-contained `index.html`, just open it or serve it statically. on an iphone, lock him in with Guided Access so palm mashing cannot leave the page

Live: https://wee-woo-gamma.vercel.app (Vercel project wee-woo, git-linked to this repo - pushes to main auto-deploy; wee-woo.vercel.app was already taken, so Vercel assigned the -gamma name). Sibling game: Rocco's Garage (https://github.com/roccozzie/roccos-garage).
