# Periscope Depth

Version 2.4 (shown as **v2.4** next to the title in the game). See the version history at the bottom.

A WW2 submarine stealth game, played through the periscope. North Atlantic, 1942: you command an Allied submarine on a campaign against the German surface fleet. Hunt warships, raid harbours and rescue downed airmen without being found.

## Play
Open `index.html` in any browser, on a computer or a phone (on-screen buttons included). The game is that one file; the crew's recorded voice lines live in `voice/voices.js` next to it.

## New here?
Pick **Training** on the title screen: a short guided attack that teaches aiming, firing, diving, the hydrophones and surfacing.

## Campaign
Nine hand-built missions, then endless generated ones, tracked on a map of the North Atlantic:

| Mission type | Goal |
|---|---|
| Convoy attack | Sink the cruisers and tankers before they steam out of range |
| Capital ship | Sink a battleship that takes five hits, behind a strong destroyer screen |
| Harbour raid | Get through a minefield and sink ships at anchor in a bay |
| Rescue | Reach a life raft and pick up four airmen before German patrol boats do |
| Submarine duel | Hunt a U-boat that is hunting you, and dodge its torpedoes |

Some convoys sail near **neutral merchant ships** flying their colours. Identify every target first: sinking a neutral costs command points.

Each mission has day or night and its own weather (clear, fog, rain or heavy seas).

## How to attack
- **Find them.** Marks around the periscope rim and orange lines on the plotting table point to ships you can *hear*.
- **Plot a solution.** Keep a ship in view and the crew works out a firing solution. A **◆ AIM** marker appears ahead of it (on Veteran the crew calls out the lead angle instead).
- **Fire.** Torpedoes run straight along the periscope bearing. Cruisers take 2–3 hits, a battleship 5.
- **Choose the torpedo.** Steam torpedoes are fast with a long range but leave a bubble trail. Electric ones leave almost no wake but are slower and shorter-ranged.
- **Listen.** The hydrophone station (H) shows a sound trace around a dial and identifies what you hear.
- **Surface.** On the surface the diesels recharge your battery and air, and the deck gun (G) can finish off ships. You are loud and easy to see, so do it at night.

## Stealth
The **Detection** meter shows how close the enemy is to finding you.
- A raised periscope is spotted faster the longer it stays up, the closer the enemy is, and the faster you move.
- Speed makes noise; Ahead Slow is nearly silent.
- Firing is loud, and lookouts may spot the torpedo wake and dodge.
- Destroyers hunt in pairs: one stops its engines to listen and guides the other onto you.
- At night, hunting escorts fire star shells that light you up.
- By day, patrol aircraft hunt for periscopes and surfaced boats, bomb them and call in the escorts.
- Battery and air run down underwater, faster at high speed.
- Depth charges can crack the periscope, damage the motors or start flooding. Your damage-control party repairs them over time.
- To escape: lower the periscope, slow down, dive to 70 m and move away from where you fired.
- Finish a mission without ever being detected for a **+50% ghost bonus**.

## Your crew
Five named crewmen gain experience every mission and get better at their jobs: the First Lieutenant plots solutions faster, the sonar operator hears farther, the torpedo gunner's mate reloads faster, the lookout sees farther and spots aircraft sooner, and the engineer repairs faster and stretches the battery. Depth charges can injure them (someone less skilled covers the station while they recover) or kill them, and a green replacement joins.

## Time and weather
The clock runs during a mission (one second of play is one minute aboard). Afternoon attacks can run into sunset and night; night attacks into dawn. Weather can change mid-mission: fog rolls in, rain squalls pass, seas build.

## After each mission
A captain's patrol report lists everything that happened with times, plus sepia "periscope photographs" of the ships you sank. Eighteen achievements track special feats, from Night Owl to Clean Sweep.

## Views and controls
- **Control room view (R):** the boat's gauges, your crew at their stations, red lighting when you rig for silent running, and water on the deck when flooding.
- **Game controller:** Xbox, PlayStation and other standard controllers work. Left stick turns the periscope, right stick steers, A fires, B raises or lowers the periscope.
- **Phones:** vibration on depth charges and hits (Android), and a sideways layout with the buttons in a column beside the periscope.

## Between missions
Earn command points and spend them on refits: silent motors, a slim periscope, faster torpedo loading, extra torpedoes, a reinforced hull and better batteries. Earn nine decorations and promotion from Lieutenant to Commodore; the service record shows your medals, mission log and campaign map. Your career saves automatically in the browser, so you can close the game and continue later.

## Settings
Three difficulties (Easy, Normal, Veteran), background music and spoken crew callouts. Turn music and voices on or off from the pause menu.

| Key | Action |
|---|---|
| ← → (Shift = faster), or drag | Turn periscope |
| Z / mouse wheel | Zoom 1.5× / 6× |
| Q | Raise / lower periscope |
| Space | Fire torpedo |
| A / D | Steer the boat |
| W / S | Speed up / slow down |
| C | Dive deep / return to periscope depth |
| V | Surface / dive |
| G | Deck gun (when surfaced) |
| X | Switch steam / electric torpedoes |
| H | Hydrophone station |
| R | Control room view |
| T | Time compression (1× 2× 4× 8×) |
| M | Enlarge plotting table |
| P / Esc | Pause and settings |

## Crew voices
The crew's lines are pre-recorded audio clips made with [Piper](https://github.com/rhasspy/piper), an open-source neural voice engine (MIT licence), so they sound the same on every device. They play through a ship's-intercom filter. Bearings are read digit by digit.

| Crewman | Voice | Source and licence |
|---|---|---|
| Officer of the watch | VCTK speaker p226 | [VCTK corpus](https://datashare.ed.ac.uk/handle/10283/3443), CSTR, University of Edinburgh, CC BY 4.0 |
| Sonar operator | Northern English male | [OpenSLR 83](http://www.openslr.org/83/), CC BY-SA 4.0 |
| Lookout | VCTK speaker p279 | VCTK corpus, CC BY 4.0 |

## Version history
- **2.4** — Controls regrouped into the boat's stations (Periscope, Torpedo firing, Helm & engines, Diving, Sonar & nav), each with a brass nameplate, plain-English labels with captions, indicator lamps, an engine-telegraph readout and hover tooltips.
- **2.3** — Named crew with experience and injuries; time of day passes and weather changes during missions; captain's patrol report with periscope photographs; 18 achievements; control room view; game controller support; phone vibration; sideways phone layout.
- **2.2** — Recorded crew voices: every line is a pre-generated audio clip played over the intercom, with three distinct crewmen. "Test crew voices" button in the sound settings.
- **2.1** — More natural male crew voices with a voice picker; realistic shellfire (whistle, splash, delayed gun report); explosions as ships sink, bigger for bigger ships; on phones, pop-up messages show one at a time in a small strip at the top.
- **2** — Torpedo types, battery and air, aircraft, hydrophone station, deck gun, U-boat duel, system damage, neutral ships, training mission, campaign map, medals and ranks.
- **1** — Campaign, refits, weather, smarter destroyers, music and crew callouts, realistic effects, sinking close-up.
