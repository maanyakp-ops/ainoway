# 🐀 Portal Rat: Takeshi's Cat Maze

An interactive 2D top-down arcade adventure inspired by the classic **Takeshi's Castle "Knock-Knock" Door Maze** (TBS Game Show).

Play as a brave **Rat equipped with a handheld Aperture Science Portal Gun**. Navigate a 3x4 grid of cubicles separated by Japanese sliding/hinged screen doors marked with the iconic wooden 'X' cross-bracing.

## ⚠️ Hazard: The 2D Pixelated Cat
Behind some of the doors lurks the ultimate maze predator: a **giant 2D Pixelated Cat**.
- Opening a **Wrong Door** triggers a sudden cinematic jump-scare sequence!
- The door violently shatters open.
- The 2D pixelated cat lunges forward with glowing yellow/red eyes, extending sharp claws.
- The cat's jaws unhinge and snap shut with a giant comic **CHOMP!**, swallowing the rat whole.
- Followed by an authentic retro 80s arcade **GAME OVER** screen!

---

## 🎮 Controls
| Action | Key / Input |
|---|---|
| **Move Rat** | `W` `A` `S` `D` or `Arrow Keys` |
| **Push / Open Door** | Walk directly into the door panel |
| **Shoot Blue Portal** | `Left Click` or `Q` / `1` |
| **Shoot Orange Portal** | `Right Click` or `E` / `2` |
| **Teleport** | Step into any active Blue or Orange portal |
| **Quick Restart** | `R` key or on-screen Restart button |
| **Toggle Audio** | `SFX` button in top HUD |

---

## 🔬 Core Features & Mechanics
1. **Takeshi's Castle Set Architecture**:
   - 3 rows × 4 columns grid of cubicle chambers.
   - Overhead wooden beams with drop shadows and joint plates matching the broadcast aesthetic.
   - Scuffed concrete floors with footprints and debris.
   - Cream-colored wooden doors featuring Japanese diagonal 'X' cross braces that swing inward upon collision.
2. **Portal Physics**:
   - Aim your Portal Gun in 360° toward walls.
   - Place Blue and Orange portals dynamically.
   - Stepping through one instantly translates momentum and position to the other, allowing you to bypass dangerous chambers or scout ahead!
3. **Procedural Synthesizer (Web Audio API)**:
   - 100% self-contained audio—no external sound files required!
   - Rat footsteps, portal laser sweeps, spatial teleport whooshes, door creaks, cat screech & chomp crunch, and victory fanfare.
4. **Cheese Radar HUD**:
   - Real-time Manhattan distance tracker showing how many rooms away the Golden Cheese is.
