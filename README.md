# Crystallography Simulators

Interactive 3D simulators that show how lattice planes become reciprocal-space points, and how the Ewald sphere decides which ones diffract.

- **Ewald Sphere 3D**: rotate the crystal, change λ and d, and watch reciprocal points hit the sphere and trigger diffraction beams.
- **Real to Reciprocal Space**: choose (hkl) and see the lattice planes, their spacing d, and the matching reciprocal-lattice vector.

Open the [simulator website](https://jliu-science.github.io/crystallography-simulators/) and choose a simulator.

The simulators load Three.js, OrbitControls, and Tailwind CSS from public CDNs, so internet access is required. Desktop or tablet use is recommended; phone users can try landscape orientation.

## Hosting

GitHub Pages serves these static HTML files from the `main` branch, repository root. No build step is required.
