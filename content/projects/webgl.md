---
title: Swedish Metaballs 
date: 2022-03-23
type: post
tags: ["3d", "programming", "webgl", "metaballs", "raymarching"]
---

## Metaballs in WebGL
This is the colmination of the WebGL course I took.  
Basicaly the only thing that is sent to the shaders is a rectrectangle, in my case a point that is very large, that covers the whole canvas.
It is in this rectangle where all the raymarching takes place in the fragment shader.
The core parts of the raymarching is from Jamie Wongs tutorial at http://jamie-wong.com/2016/07/15/ray-marching-signed-distance-functions/.

{{< metaballsshortcode >}}


