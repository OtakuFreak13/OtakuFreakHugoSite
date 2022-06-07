---
title: WebGL 
date: 2022-06-07
type: post
tags: ["3d", "programming", "webgl", "metaballs", "raymarching"]
---

## Metaballs in WebGL
This is the colmination of the WebGL course I took.  
Basicaly the only thing that is sent to the shaders is a rectrectangle, in my case a point that is very large, that covers the whole canvas.
It is in this rectangle where all the raymarching takes place in the fragment shader.

{{< metaballsshortcode >}}


