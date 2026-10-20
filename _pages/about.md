---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a 3rd year PhD student in Applied Mathematics at the University of Colorado Boulder working with [Dr. Adrianna Gillman](https://sites.google.com/colorado.edu/gillmana). I recieved an MS in Applied Mathematics from CU Boulder in 2026 and a BA in Mathematics and Astronomy in 2024. 

My research interests include scientific computing, numerical methods for partial differential equations, numerical linear algebra, and fast algorithms. I am currently developing numerical methods for free-space Helmholtz scattering problems with spatially varying wavenumbers. I have some visualizations below!

## News
_September 2026 --_ Presented at the CU Boulder SIAM Graduate Chapter monthly lunch.

_October 2026 --_ Attended and presented results at the Numerical and Scientific Computing Research Training Group workshop at Rice University. 

## Research Visuals

### Scattering by a Graded Lens

Free-space scattering governed by the variable-coefficient Helmholtz equation, with a graded-lens scattering potential.

<div style="display: grid; grid-template-columns: repeat(2, minmax(0, 1fr)); gap: 10px; align-items: start; width: 100%;">

  <figure style="margin: 0; min-width: 0;">
    <video autoplay loop muted playsinline controls
           style="width: 100%; height: auto; display: block;">
      <source src="{{ '/files/GLk160.mp4' | relative_url }}"
              type="video/mp4">
    </video>
    <figcaption style="text-align: center; margin-top: 8px;">
      Real part of the scattered field for varying incident directions. \(\kappa\) = 160.
    </figcaption>
  </figure>

  <figure style="margin: 0; min-width: 0;">
    <img src="{{ '/files/b_GL.png' | relative_url }}"
         alt="Graded-lens scattering potential"
         style="width: 100%; height: auto; display: block;">
    <figcaption style="text-align: center; margin-top: 8px;">
      Graded-lens scattering potential.
    </figcaption>
  </figure>

</div>

### Near-Resonant Waveguide Scattering

Free-space Helmholtz scattering involving a near-resonant waveguide configuration.

<div style="display: grid; grid-template-columns: repeat(2, minmax(0, 1fr)); gap: 10px; align-items: start; width: 100%;">

  <figure style="margin: 0; min-width: 0;">
    <img src="{{ '/files/Waveguide.png' | relative_url }}"
         alt="Real component of scattered wave field"
         style="width: 100%; height: auto; display: block;">
    <figcaption style="text-align: center; margin-top: 8px;">
      Real part of the scattered wave field. \(\kappa\) = 77.1.
    </figcaption>
  </figure>

  <figure style="margin: 0; min-width: 0;">
    <img src="{{ '/files/b_waveguide.png' | relative_url }}"
         alt="Waveguide scattering potential"
         style="width: 100%; height: auto; display: block;">
    <figcaption style="text-align: center; margin-top: 8px;">
      Waveguide scattering potential.
    </figcaption>
  </figure>

</div>