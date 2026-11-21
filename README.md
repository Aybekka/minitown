# MiniTown

A cozy, retro-flavoured city sim that plays more like a god game than a management game. Zone a few lots, watch roads appear around them, builders put up houses, shops and workplaces, and a little town comes alive. Then mostly just watch.

**Play it:** open `index.html` in a browser, or visit the GitHub Pages site for this repo.

## What you can do

- **Zone** Homes, Shops, Work and Parks by clicking or dragging through up to three connected lots (a straight row or an L). Everything in one drag becomes one shared block; streets form along its outer edges on the same 20×20 grid as the buildings.
- **Watch construction**: surveyed lot → foundation → timber frame → scaffolding → finished, then buildings fill up and grow to three floors over time.
- **Observe residents**: every person has a home, an age, a job or school, a daily schedule, and sometimes a dog, a bike or a car. They commute, have lunch, shop, visit friends, play in parks, and take weekends off.
- **Inspect anything**: hover a building, person or vehicle to see who's there and what they're doing; click to pin it, follow a resident, or jump to their home or workplace.
- **Day and night**: a full day cycle with a clickable 24-hour bar to skip ahead. At night the town turns cool and soft while windows, streetlights, shop signs and park lamps glow warm.
- **Explore**: free camera, minimap, a slow Tour mode, and "Follow someone".
- **Clear** blocks with the bulldozer; unused streets disappear with them.
- Your town **autosaves** in your browser.

## Controls

| Action | Input |
| --- | --- |
| Explore / Homes / Shops / Work / Parks / Clear | `1`–`6` |
| Pan | Drag, or `WASD` / arrow keys |
| Turn | Right-drag, or `Q` / `E` |
| Zoom | Mouse wheel or pinch |
| Frame the town | `F` |
| Tour / Follow someone | `T` / `G` |
| Pause | `Space` |
| Pixel rendering on/off | `P` |

## Tech

A single self-contained HTML file using [three.js r128](https://threejs.org/) from a CDN. All models are simple stylized geometry built in code; textures are tiny generated canvases. A small post-processing pass adds the soft night glow.
