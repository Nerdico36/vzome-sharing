---
title: Point and Unit Cell Classes of the Laves Graph
description: The 4 classes of integer points W.R.T. the Laves graph and their corresponding unit cells.
image: https://Nerdico36.github.io/vzome-sharing/2026/02/27/20-09-20-Laves-Point-Classes-Scene-Tester/Laves-Point-Classes-Scene-Tester.png
published: true
layout: vzome
---

{% comment %}
 - [***web page generated from this source***](<https://Nerdico36.github.io/vzome-sharing/2026/02/27/Laves-Point-Classes-Scene-Tester-20-09-20.html>)
 - [data assets and more info](<https://github.com/Nerdico36/vzome-sharing/tree/main/2026/02/27/20-09-20-Laves-Point-Classes-Scene-Tester/>)
 
{% endcomment %}

The Laves graph can be fitted to an integer grid, the sparsest of which gives it a cubic unit cell with side length 4. Under the symmetries of the Laves graph, this integer grid is partitioned into 4 point orbits. These are best described by also considering the dual mirror image Laves graph, which lies on the same integer grid.

<figure style="width: 87%; margin: 5%">
  
  <div style='display:flex;'><div style='margin: auto;'><vzome-viewer-previous label='prev step'></vzome-viewer-previous><vzome-viewer-next label='next step'></vzome-viewer-next></div></div>
  <vzome-viewer style="width: 100%; height: 60dvh" indexed='true'
        src="https://Nerdico36.github.io/vzome-sharing/2026/02/27/20-09-20-Laves-Point-Classes-Scene-Tester/Laves-Point-Classes-Scene-Tester.vZome" >
    <img  style="width: 100%"
        src="https://Nerdico36.github.io/vzome-sharing/2026/02/27/20-09-20-Laves-Point-Classes-Scene-Tester/Laves-Point-Classes-Scene-Tester.png" >
  </vzome-viewer>

  <figcaption style="text-align: center; font-style: italic;">
    Unit Cell of Dual Laves Graphs and Neighbors
  </figcaption>
</figure>

Each vertex of the Laves graph has D_3 symmetry (the orientation preserving symmetries of a triangular prism), which means the 6 integer lattice points of distance 1 from each vertex - their "nearest neighbors" - are equivalent under symmetry. These are in turn equivalent to the neighbors of all other vertices of the Laves graph. Taking together the 4 classes of the Laves vertices, their neighbors, the dual graph's vertices, and their respective neighbors, turns out to cover all lattice points in the unit cell, as can be verified in the above model. (The Laves graph is shown in green connecting white vertices, linked to its red neighbors with cyan, with the dual in purple connecting yellow vertices, linked to its blue neighbors with orange). These classes happen to also be equivalent to sorting the integer points by taxicab/Manhattan distance to either the nearest vertex of the Laves graph or that of its dual, with ratios of 16 : 48 : 48 : 16 per unit cell.

Now, the classes of unit cells (up to symmetries of the single Laves graph) aligned to the underlying integer lattice correspond one-to-one with the classes points on this lattice under Laves graph symmetries; simply check the point class of the corner vertices of the unit cell, or its center (which are the same in this case, since the Laves graph's symmetry has a body-centered cubic translation lattice). Thus, the 4 classes of unit cells are shown below (arranged as if they were taken from the same Laves graph, offset by 1 in the integer grid). The corner vertices of the unit cells share their color scheme by point class with the previous model, with pink struts representing 2-fold rotational axes of the unit cell and gold struts representing 3-fold axes of the unit cells.

<vzome-viewer style="width: 100%; height: 65vh;"
       src="https://Nerdico36.github.io/vzome-sharing/2026/02/27/20-09-20-Laves-Point-Classes-Scene-Tester/Laves Unit Cell Classes.vZome" >
  <img src="https://Nerdico36.github.io/vzome-sharing/2026/02/27/20-09-20-Laves-Point-Classes-Scene-Tester/Laves-Point-Classes-Scene-Tester.png" />
</vzome-viewer>

The unit cells corresponding to the vertices of the Laves graph or its dual have a 3-fold axis and three 2-fold axes (D_3 symmetry) while the unit cells corresponding to either's neighbors has only a single 2-fold axis. The Laves vertex/dual vertex type unit cells appear in 4 orientations each in the Laves graph, while the neighbor/duall neighbor typee unit cells appear in 12 orientations each. This covers all unit cells up to equivalence under Laves graph symmetries.
