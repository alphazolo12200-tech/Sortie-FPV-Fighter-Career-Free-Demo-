# Sortie FPV: Fighter Career (Free Demo)

A first-person 3D fighter pilot career game that runs in your browser. Take off, land, earn your first rank, then decide if you want the full carrier career.

**Play online:** https://alphazolo12200-tech.github.io/sortie-fpv-demo/
**Full game (16 sorties, carrier ops):** https://alphazolozyro.itch.io/sortie-fpv

Works on desktop and phone (landscape is best). No install, no account, and it runs offline once downloaded.

## What is in this demo

- **2 sorties:** Cold Start Takeoff and Pattern Landing, both in daylight with an instructor on board.
- **2 ranks:** Cadet and Student Pilot. Pass a sortie (50 points or more) to unlock the next one and earn XP.
- Full cockpit view with HUD, ILS guidance, jet engine sound and spoken instructor callouts.

## What the full game adds

- 16 sorties: night training, solo flights, dusk gusts, storm nights and a check ride
- Carrier operations: catapult launches, the landing ball, arrestor hook and wire landings, bolters
- 10 ranks from Cadet to Air Marshal
- Rain and lightning on the hardest sorties

## Controls

| Action | Keyboard | Touch |
| --- | --- | --- |
| Pitch and roll | Arrow keys or WASD (pull back = nose up) | Drag on the right half of the screen |
| Throttle | Shift up, Ctrl down | Slider on the left |
| Rudder | Q and E | - |
| Landing gear | G | GEAR button |
| Flaps | F | FLAPS button |
| Wheel brakes | Space | BRAKE button |
| Voice on or off | V | VOICE button |
| Invert pitch | I | INV button |
| Pause menu | P or Esc | \|\| button |
| Retry the sortie | R | Pause menu |

On final approach the controls are deliberately gentler, and the wings level themselves when you let go, so small corrections are easier.

## How to play

1. Start with Sortie 1. Hold full throttle, roll along the runway, rotate gently at about 140 knots, then raise the gear and climb to 300 m.
2. Sortie 2 starts you on a 3 degree approach. Lower gear and flaps, keep the pink ILS cross centred, ease the throttle back and put the aircraft down smoothly. Then brake to a stop.
3. Your score depends on stalls, touchdown softness, where you touch down, centreline error and bounces. Replay any sortie to beat your best score.

## Run it yourself

- **Locally:** download this folder and open `index.html` in a modern browser. Nothing else is needed.
- **On GitHub Pages:** put `index.html` in the repository root, then go to Settings, Pages, choose the main branch and the root folder. Your demo appears at `https://<your-username>.github.io/<repository-name>/` after a minute or two.

## Good to know

- Needs a browser with WebGL. Recent Chrome, Edge, Firefox and Safari work.
- The flight model is arcade style, built to feel good and teach approach discipline. It is not a certified simulator.
- Spoken callouts use your device's built-in voice, so the voice and accent depend on your device. Press V to turn them off.
- Progress is saved in your browser on that device, so it will not follow you to another browser.
- Sound starts after your first tap or key press, which is a browser rule.

## Credits and licence

- Game design, code and content: alphazolo. All rights reserved. You are welcome to play and share the link to this demo, but please do not redistribute or resell the files.
- Built with [three.js](https://threejs.org/) r128, which is MIT licensed. Its licence notice is kept at the top of the script inside `index.html`.

## More from alphazolo

Other games and tools: https://alphazolozyro.itch.io and https://alphazolo.gumroad.com
