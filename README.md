# singularity-portfolio

A single-file 3D portfolio. 140,000 GPU-shader particles morph between 8 scenes as you scroll:
singularity, Lorenz attractor, torus knot, galaxy, nebula, pulsar, DNA helix, wormhole.

- **Stack:** three.js r128 (cdnjs), custom GLSL vertex/fragment shaders, vanilla JS, zero build step
- **Interactions:** scroll-driven scene morphing, pointer repulsion, click shockwave, scene picker (keys `1`-`8`), interactive terminal (`help`)
- **Resilience:** WebGL fallback, automatic particle downgrade on low FPS, reduced-motion support, responsive layout

## Run

Open `index.html` in a browser, or serve it: `python3 -m http.server`.

## Customize

Edit `CFG` (contact links) and the `PROJ` array (projects) near the bottom of `index.html`.
