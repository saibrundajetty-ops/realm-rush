# Realm Rush — Zero-Cost Vertical Slice

Offline, dependency-free browser prototype built entirely from HTML/CSS/JavaScript and procedural primitives.

## Included
- One connected 360m × 260m conceptual world with three contiguous regions.
- Third-person adventure presentation with mouse-look and movement.
- Greenfield Village → Whispering Woods → Central City Edge progression.
- M01–M06 mission state flow and rewards.
- Realm Dash and Wall Run progression flags.
- Ability gates LG1–LG4.
- Collectibles and XP/coin tracking.
- Crystal Run AI rival using fixed race waypoints.
- Mission/HUD/map UI.
- Local/offline execution; no network calls or external assets.

## Run
Open `index.html` in a modern desktop browser. No server, package manager, plugin, or internet connection is required.

## Controls
WASD move · Mouse drag turn · Space jump · Shift dash · E interact · R wall-run · M map · P pause.

## Deliberate prototype limitations
This is a functional zero-cost prototype, not the final Form-stage 3D build. Visuals use a lightweight canvas software renderer and procedural/placeholder geometry. Collision, traversal and camera are intentionally simplified for offline prototyping. The approved specifications remain the authority for a later Form-stage implementation.

## Cost
₹0. No paid service, Meshy, paid API, purchased asset, plugin, texture, music, backend, or external asset download was used.

## Runtime-debug packaging note

This diagnostic package embeds the existing `src/game.js` code directly into `index.html` so iPad local-file viewers do not need to resolve an external JavaScript subpath. The renderer and gameplay remain unchanged. The bottom-left diagnostic indicator reports initialization progress and runtime errors.
