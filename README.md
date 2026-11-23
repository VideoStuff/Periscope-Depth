# 🧦 Sock Quest: Laundromat of Doom

A turn-based roguelike. You're a lone sock lost in a haunted laundromat. Descend six floors of procedurally generated dungeon, fight dust bunnies, rogue quarters and angry irons, and defeat **The Great Dryer** to find your matching pair. Permadeath.

## Play
Open `index.html` in any browser (desktop or mobile — touch d-pad included).

| Key | Action |
|---|---|
| Arrows / WASD / hjkl / yubn | Move / attack (bump) |
| `.` or Space | Wait |
| `Q` | Fabric Softener (+10 HP) |
| `E` | Bleach (damages foes within 3 tiles) |
| `R` | Restart after death |

Step on 🕳️ to go down the drain. 🧦 pickups grant max HP and attack; 📄 dryer sheets absorb damage.

---

# 🔭 Periscope Depth

A WW2 submarine stealth game, played through the periscope. North Atlantic, 1942: you command an Allied submarine and must sink German warships (cruisers, a fleet tanker) before their escorts (destroyers, torpedo boats, patrol boats) find you.

## Play
Open `periscope/index.html` in any browser (desktop or phone; on-screen buttons included).

## How it works
- **Find them**: the plotting table (bottom right) shows ships you can *hear* as orange bearing lines, and ships you've *seen* as markers.
- **Plot a solution**: keep a ship in the periscope view and the crew works out a firing solution. A **◆ AIM** marker appears ahead of the ship.
- **Fire**: torpedoes run straight along the periscope bearing. Put the crosshair on ◆ AIM and fire. Cruisers take 2–3 hits.

## Stealth
The **Detection** meter shows how close the enemy is to finding you.
- A raised periscope is spotted faster the longer it stays up and the closer the enemy is.
- Speed makes noise; Ahead Slow is nearly silent.
- Firing is loud, and lookouts may spot the torpedo wake and dodge.
- Once detected, escorts charge in, ping with sonar, drop depth charges and shell your periscope.
- To escape: lower the periscope, slow down and dive to 70 m, then move away from where you fired.
- Finish a patrol without ever being detected for a **+50% ghost bonus**.

| Key | Action |
|---|---|
| ← → (Shift = faster), or drag | Turn periscope |
| Z / mouse wheel | Zoom 1.5× / 6× |
| Q | Raise / lower periscope |
| Space | Fire torpedo |
| A / D | Steer the boat |
| W / S | Speed up / slow down |
| C | Dive deep / return to periscope depth |
| T | Time compression (1× 2× 4× 8×) |
| M | Enlarge plotting table |
| P / Esc | Pause |
