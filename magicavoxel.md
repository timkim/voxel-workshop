---
title: "Using MagicaVoxel"
layout: post
---
# What is MagicaVoxel?
MagicaVoxel is a free 3D modeling software that is designed for ease of use and fun! Everything in MagicaVoxel is built out of cubes or voxels. Think pixel art but in 3D! No worrying about polygons, faces, vertices and textures. Stack your voxels upon another, change their colours, and make something cool!

_**tldr: building stuff in MagicaVoxel is like building stuff with lego**_

#### Some cool stuff I've personally made:
![Cool stuff I've made in MagicaVoxel](img/cool_stuff.png "Cool stuff I've made in MagicaVoxel")

As far as I can tell, it is made by one person named [@ephtracy](https://twitter.com/ephtracy) and is hosted at [https://ephtracy.github.io/](https://ephtracy.github.io/). If you haven't done so already, please download and install MagicaVoxel to continue with this workshop: [https://ephtracy.github.io/](https://ephtracy.github.io/).

## Camera Controls
To navigate around your model, you'll primarily be using the `right click` button, the `space` key, and the `scroll wheel`. There are also keyboard commands, but I find that using a mouse is more intuitive. 

* **Rotate:** Hold down `right-click` to rotate the camera around. Or use `a` & `d` to rotate left and right and `q` & `e` to rotate up and down. 
* **Zoom:** Use the `scroll wheel` to zoom in or out. Or use `w` & `s`. 
* **Pan:** Hold down `space` and `right-click` to move your camera around the scene. Or you can hold down and use `scroll-click` to achieve the same effect. 

#### Change Camera Modes
![Camera modes](img/camera_mode.png "Camera modes")

For the purpose of this tutorial, we shall keep our camera in `Pers` or **Perspective** mode. However, you can change to `Free` in order to move the camera around like you would in a FPS (WASD controls). Switching to `Orth` or `Iso` switches the camera's projection to be _orthgraphic_ which means parallel lines never visually meet. Use this mode to simulate isometric graphics. 

To note: exporting your model in `Pers`, `Orth` or `Iso` will not preserve the camera's setting when viewing it in WebVR! To emulate those camera modes, you will need to set that up on the A-Frame/WebVR side!


