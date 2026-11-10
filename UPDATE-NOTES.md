# Update notes

## Crystallography Simulators (Ewald sphere 3D + Real to Reciprocal space)

### Display and interaction
- Lattice planes are now drawn as parallel sheets, so the stacking and spacing of (hkl) planes is easy to see.
- Orthographic camera, so parallel lines stay parallel (no perspective distortion).
- Dragging no longer has inertia: the view stops when you release the mouse.
- Labels are larger and easier to read, with depth cues so near and far objects are distinguishable.
- Detector label is now a vertical label placed where it stays visible when zoomed in.
- G label moved so it no longer covers the yellow G vector.
- The guide now says: left button rotates, right button (hold) pans / moves the view.

### Miller indices and lattice
- h, k, l sliders now go up to ±4 (previously smaller), so higher-order planes can be explored.
- The reciprocal grid only grows as far as the chosen indices need, so the screen is not flooded with points.
- Real to Reciprocal: lattice constant `a` now defaults to 4 Å, with range 3–7 Å.

### Ewald sphere defaults
- Opens with Mo Kα (0.7107 Å) and d = 1.90 Å.
- New opening view (zoom and angle) tuned so it looks good on first load.

### Site and text
- New site title and intro on the index page and README; the intro is shown on two lines.
- Star link reworded everywhere to "☆ Found this useful? Star it on GitHub", with the hover tip "Leave your star if you found it helpful". Applied to the simulators, PXRD Optics (8 pages) and Crystallisation Explorer.
- Removed redundant old copies of the pages so only one version exists.

## Crystallisation Explorer (ROY lab) — typography restyle (not yet pushed)
- Font weights lowered: headings 600, buttons 500, body text 400 (previously very heavy, up to 900+).
- Inter font added (Google Fonts) with a system-font fallback.
- Title letter-spacing loosened.
- Functionality unchanged. New build files: `assets/dev-Bm1KlNbk.js`, `assets/dev-DqZ0TJ5g.css`.
