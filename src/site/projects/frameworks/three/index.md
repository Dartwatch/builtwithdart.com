---
layout: project
title: "Three.dart"
added: 07/Dec/2012
updated: 
description: 'Port of three.js'
download_url: https://github.com/threedart/three.dart
source: https://github.com/threedart/three.dart
homepage: http://threedart.github.com/three.dart/
author_name: Robert Silverton
author: https://plus.google.com/u/0/106977194431607185215/
author_image: https://profiles.google.com/s2/photos/profile/106977194431607185215
mainimage: three.png
---

### Author's Notes

It took 5 days to port everything that was needed to get the most simple example in three.js working in Dart. Once that spinning cube was visible, everything else fell into place much more easily. The experience was much easier than it might have been due to the similarities between JS and Dart and the way that the three.js code is organised into (what can be considered) the JS equivalent of classes. Porting the code to Dart felt much more like a formalisation that a rewrite, as it allowed me to specify public and private members, return types, etc. Structurally the two libs are practically identical, the Dart language simply provides the project with a bit more explicit information on how it is expected to be used.

### Demos

[Web GL Cat demo](http://threedart.github.com/three.dart/example/webgl_nyan_cat/nyan_cat.html)
[Web GL 3d shape demo](http://threedart.github.com/three.dart/example/webgl_geometries/WebGL_Geometries.html)
[CSS Periodic table demo](http://threedart.github.com/three.dart/example/css3d_periodictable/CSS3D_Periodic_Table.html)
[HTML5 Canvas demo](http://threedart.github.com/three.dart/example/canvas_geometry_hierarchy/Canvas_Geometry_Hierarchy.html)

And many more demo's on the project's [homepage](http://threedart.github.com/three.dart/)