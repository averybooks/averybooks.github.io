---
layout: page
title: "Fusor"
permalink: /research/fusor/
header: no
---

### Abstract / Update
This is the research into the Farnswirth-Hirsch fusor. The current objective is the optimization of the high voltage grid within the vacuum chamber. This is an active project, so a full report is being produced. The simulation code is finished and the current stage is tesing different geometries and analyzing different confinement scores and ion trajectories to understand the magnetohydrodynamics. 

The following image is an output from the code for a 6 ring spherical grid geometry. This, as of right now, is the optimal geometry for plasma confinement in the spherical style. Note that an in depth analysis of why and the exact differences between geometry types and ring amount is still being conducted. Additionally, analysis of the ion density correlation with the simulated ion trajectories is being conducted as well. The following graph has large amounts of "stray" ion density, however there is significantly less "stray" ion trajectories in the MHD simulation.

Code can be found at: https://github.com/averybooks/Farnswirth-Hirsch-Fusor

<div style="text-align: center; margin: 20px 0;">
  <img src="{{ '/assets/images/6ringspherical.png' | relative_url }}" 
       alt="6 Ring spherical geometry grid" 
       style="max-width: 150%; height: auto; border: 1px solid #ddd; border-radius: 4px; display: inline-block;">
  <p style="font-style: italic; color: #666; margin-top: 5px;">Figure 1: Notice the boundary conditions on the electric potential and electric field graphs correlating strongly with the ion trajectories. However, note how in both the XZ and XY planes the ion density shows high amounts of jets outside of the +- 5 cm radial distance from the center. </p>
</div>