# Interference Rainbow Lab

An interactive demonstration of the interference (supernumerary) rainbow, based on Airy's theory of the primary bow.

**Live site:** https://teyuan-lab.github.io/interference-rainbow/

## What it shows

- **Wavefronts through the drop** — a ray trace of sunlight through a spherical water drop (refraction, one internal reflection, refraction). Wavefronts are drawn one per wavelength and fold into a cusp near the rainbow angle. Arrows mark the rainbow maximum and the supernumerary directions.
- **Far-field intensity** — Airy theory, intensity ∝ Ai²(−z) with z = (2x²/h)^(1/3)·(θ_R − ψ), where x = 2πa/λ and h = −d²θ/d(b/a)² at the Descartes ray. The geometric-optics curve (∝ 1/√(θ_R − ψ)) is shown for comparison, plus a white-light colour strip.
- **Observed bow** — white sunlight (5778 K blackbody, 380–720 nm) summed through CIE colour matching, optionally blurred by the sun's 0.53° disk, drawn in a simulated sky.

Hover (or tap) the far-field chart to see the two rays that leave the drop at that angle and their path difference in wavelengths.

## Parameters

Drop radius, wavelength, refractive index (water dispersion), diagram wavelength exaggeration (a/λ), sun elevation, sky field of view, sun-disk blur.

## Limitations

The far field uses the Airy approximation rather than full Mie theory. It is accurate near the bow; for very small fog drops the outer fringes are only approximate. Only the primary bow is modelled.

## Run locally

It is a single static file. Open `index.html` in a browser, or serve the folder with any static server.
