# Project Lock & Code Containment Protocol

## STRICT AGENT INSTRUCTIONS — DO NOT MODIFY WITHOUT EXPLICIT PERMISSION
This codebase (`index.html`, `frames/`, `images/`) has been fully engineered, optimized, and stabilized for production.

### Core Immutable Rules for AI Agents:
1. **NO UNPROMPTED CHANGES**: Do not refactor, clean up, alter, or rewrite any part of `index.html`, CSS, JavaScript, canvas frame logic, or visual assets unless the user explicitly requests a specific change in their prompt.
2. **PRESERVE THE CANVAS FRAME SEQUENCER**: The hero scroll scrub is powered by the 240-frame WebP GPU Canvas Frame Sequencer (`#introCanvas`). Under NO circumstances should this be converted back to an HTML5 `<video>` tag or altered without explicit instructions.
3. **PRESERVE VIEWPORT & SAFE AREA POSITIONING**:
   - `height: 100dvh;` / `height: 352dvh;` must remain intact to prevent mobile address-bar resize jumping.
   - Stage text overlays (`#stage1`, `#stage2`, `#stage3`) must remain in their dedicated safe zones to prevent collisions with the bottom telemetry HUD.
4. **VERSION CONTROL INTEGRITY**:
   - The stable production release is tagged at `v1.0.0-stable`.
   - Any manual or requested modifications must be tested on both desktop and mobile viewports before committing.
