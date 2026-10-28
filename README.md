# Speed Skill Lab · Umamusume

A small interactive page that shows what **target speed**, **acceleration** and **current speed** skills really do in an Umamusume race, depending on when they fire.

Two identical runners (same stats, same running style) race side by side. Only their skills differ. Edit each runner's skills (type, value, trigger point in metres, base duration), pick a race distance from 1200 to 3000 m, and watch the side view, the speedometers and the speed chart.

Live page: https://kevinpoteau.github.io/Umaspeed/

## Model

- Speed 1200, Power 1000, Pace Chaser, A aptitude, good ground, enough stamina for the last spurt.
- Phases: Opening Leg (first sixth), Middle Leg (to two thirds), Final Leg (to five sixths), Last Spurt.
- Base speed = 20 − (distance − 2000) / 1000 m/s; target speed jumps at the Final Leg.
- Real skill duration = base duration × distance / 1000.
- No collisions, slopes or randomness: a visual aid, not a full simulator.

Single static file (`index.html`), served with GitHub Pages from the `main` branch root.
