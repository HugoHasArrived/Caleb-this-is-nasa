# Apollo 11 — The Journey

An independent, browser-based Apollo 11 story adventure and junior astronaut mission trainer built with **Vite + Three.js**. The experience uses a 3D scene with a cinematic, mission-control-style 2D interface.

> This is an educational game, not an official NASA product, a NASA-certified training course, or a physically validated spacecraft simulator. Flight dynamics, resource indicators, and checklists are simplified gameplay systems.

## Features

- **Story homepage and briefing:** mission summary, crew roles, controls, learning goals, and pre-mission checklist.
- **Neil Armstrong story:** childhood in Wapakoneta, early interest in aviation, flying lessons, aeronautical engineering, Navy aviation, NACA/NASA research-pilot work, astronaut selection in 1962, and Gemini 8.
- **NASA application chapter:** an educational story scene about joining the astronaut corps.
- **Astronaut learning center:** interactive questions about checklists, lunar geology, teamwork, and spacecraft orientation. These are inspired by historical training themes, not actual NASA qualification exercises.
- **Controllable Saturn V:** ignition, throttle, pitch, yaw, staging milestones, Earth-orbit milestone, and translunar injection.
- **Multiple rocket cameras:** chase, side, and wide views.
- **Apollo 11 lunar chapter:** Eagle landing, first steps, science and samples, lunar ascent, and rendezvous story events.
- **Earth return:** Pacific splashdown, USS Hornet recovery, and quarantine story.
- **Mission Systems panel:** educational oxygen, electrical, coolant, communications indicators, crew roles, and a checklist tracker. Values are illustrative and are not historical Apollo telemetry.
- **Lunar outpost resource exercise:** allocate a limited pool of planning points across life support, electrical power, and radiation shielding, then evaluate the trade-offs.
- **Desktop and touch controls**, responsive layouts, mission log, and source links.

## Run locally

Install Node.js (LTS), then run:

```bash
npm install
npm run dev
```

Open the local URL printed by Vite.

## Production build

```bash
npm run build
npm run preview
```

Vite writes the production site to `dist/`.

## Deploy with GitHub and Vercel

1. Extract this ZIP.
2. Create a new GitHub repository.
3. Upload the **contents** of this folder to the repository root (so `package.json`, `index.html`, `main.js`, `style.css`, and `vercel.json` are at the top level).
4. In Vercel, choose **Add New → Project** and import that GitHub repository.
5. Use these settings:
   - Framework Preset: **Vite**
   - Install Command: `npm install`
   - Build Command: `npm run build`
   - Output Directory: `dist`
6. Deploy. Future pushes to the connected GitHub branch will trigger new deployments.

No environment variables or API keys are required.

## Controls

### Walking chapters

| Action | Keyboard |
|---|---|
| Move | W / A / S / D |
| Look | Mouse |
| Interact | E |
| Move faster | Shift |

On touch screens, use the on-screen directional pad, drag-look area, and Use button.

### Saturn V flight chapter

| Action | Control |
|---|---|
| Start engines / liftoff | Ignition button |
| Throttle | Throttle slider or W / S |
| Pitch | Up / Down arrows or pitch slider |
| Yaw | Left / Right arrows or yaw slider |
| Confirm S-IC / S-II staging | Stage button when enabled |
| Change camera | Chase / Side / Wide buttons |
| Continue toward the Moon | Trans-Lunar Injection when enabled |

The flight model is intentionally simplified for play and learning. It does not reproduce Saturn V engine performance, Apollo guidance equations, real trajectories, or operational flight rules. Real Apollo 11 flight control involved onboard guidance systems and a large Mission Control team; the game gives the player simplified attitude and throttle controls for interactive learning.

## Historical reference points

- Launch: July 16, 1969, 13:32 UTC, Launch Complex 39A.
- Crew: Neil Armstrong, Buzz Aldrin, and Michael Collins.
- Lunar landing: July 20, 1969, Sea of Tranquility.
- Splashdown: July 24, 1969, Pacific Ocean.
- Total mission duration: 8 days, 3 hours, 18 minutes, 35 seconds.

Historical scenes are condensed for gameplay. The apartment interior and the player's role are fictionalized; the game does not claim that the player is Neil Armstrong or that the apartment is an exact reconstruction of his home.

## Official NASA sources

- [Apollo 11 Mission Overview](https://www.nasa.gov/missions/apollo/apollo-11/apollo-11-mission-overview/)
- [Neil A. Armstrong — NASA biography](https://www.nasa.gov/humans-in-space/astronauts/former-astronauts/former-astronaut-neil-a-armstrong/)
- [Apollo 11 Lunar Surface Journal — Mission Overview](https://www.nasa.gov/wp-content/uploads/static/history/alsj/a11/a11ov.html)
- [NASA Apollo 11 historical mission data](https://nssdc.gsfc.nasa.gov/planetary/lunar/apollo11info.html)

## Junior Astronaut Mission Trainer connection

The learning activities introduce mission planning concepts such as crew communication, checklists, power, life support, and mission priorities. Resource indicators are sample gameplay values, not live data from NASA. No live NASA API is required for the project to run.
