---
layout: project
title: "RGB Cube"
description: 'Graphical Color Picker written in Dart'
download_url: https://github.com/delwarde/RGB_Cube
author: https://plus.google.com/100947828840196897820/
added: 19/Nov/2012
updated: 
description: 'QR Code generator'
source: https://github.com/delwarde/RGB_Cube
homepage: 
author_name: Damien Delwarde
author_image: https://profiles.google.com/s2/photos/profile/100947828840196897820
mainimage: rgbcube.png
---

### Author's Notes

RGB colors define a discrete cube of size 256. Choosing a RGB color is choosing a point in that cube.

This example show you an original version of the RGB cube exploration : We travel along the main diagonal of the cube via the slider element, and see the intersection of the cube with the plane that is perpendicular to this diagonal at the considered point. If we click inside the intersection, we pick a color and see it.

This is not a perfect representation of the cube, because of some approximations : If we choose a point on one edge, we have a plane that is perpendicular to the diagonal and contains this point. But we are not sure that this plane also contains a point on the diagonal (we are in a discrete space !). Anyway, I decided to represent the intersection between the cube and the plane, and fill it with appropriate colors (calculated as a barycenter), without considering if the point really exists. So this is just an approximative representation...

### Demo

[Launch Author's Demo](http://delwarde.github.com/RGB_Cube/)