# References

Third-party data and research sources used to produce the animations in this repository,
with their citation and how each is used.

## Seismic Cycle (`Seismic-Cycle/`)

### Plate interface geometry — Slab2
- **Hayes, G. P., Moore, G. L., Portner, D. E., Hearne, M., Flamme, H., Furtney, M., &
  Smoczyk, G. M. (2018).** Slab2, a comprehensive subduction zone geometry model.
  *Science*, 362(6410), 58–61. https://doi.org/10.1126/science.aat4723
- Data release: U.S. Geological Survey, https://doi.org/10.5066/F7PV6JNV
- **Used for:** the South America (`sam`) Slab2 depth grid and trench trace along the 33°S
  cross-section profile.

### Crustal structure — GFZ Potsdam
- **Rodriguez Piceda, C., Scheck-Wenderoth, M., Gomez Dacal, M., Bott, J., Prezzi, C., &
  Strecker, M. (2020).** Lithospheric-scale 3D model of the Southern Central Andes.
  GFZ Data Services. https://doi.org/10.5880/GFZ.4.5.2020.001
- **Used for:** the Moho boundary shown in the cross-section profile.

### Earth and star imagery — NASA
- **Globe texture and regional satellite crop:** NASA Earth Observatory, "Blue Marble: Next
  Generation", https://eoimages.gsfc.nasa.gov/images/imagerecords/73000/73751/world.topo.bathy.200407.3x21600x10800.jpg
- **Starfield background:** NASA/Goddard Space Flight Center Scientific Visualization
  Studio, "Deep Star Maps", https://svs.gsfc.nasa.gov/3895/
- **Used for:** the opening globe shot and the star background behind it.

### Deformation solver — Okada (1992)
- **Okada, Y. (1992).** Internal deformation due to shear and tensile faults in a
  half-space. *Bulletin of the Seismological Society of America*, 82(2), 1018–1040.
  https://doi.org/10.1785/BSSA0820021018
- This repository's animations use an in-house implementation built on top of Okada's
  original DC3D Fortran routine, as distributed by Japan's National Research Institute for
  Earth Science and Disaster Resilience (NIED), rather than any third-party wrapper.
- **Used for:** computing the internal crustal deformation shown during the coseismic and
  postseismic stages.

## Notes

- The GFZ dataset above is licensed CC BY 4.0, which requires attribution for any use or
  adaptation of that data, including in the rendered animations. If you reuse these
  animations, that requirement applies to you as well — see the [LICENSE.txt](../LICENSE.txt) file for the full terms.
