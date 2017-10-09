---
title: "Exporting to WebVR Using Mozilla A-Frame"
layout: post
---

# What is A-Frame?
From the [A-Frame website](https://aframe.io/docs/0.7.0/introduction/):

A-Frame is based on top of HTML, making it simple to get started. But A-Frame is not just a 3D scene graph or a markup language; the core is a powerful entity-component framework that provides a declarative, extensible, and composable structure to three.js.


## Features:

* VR Made Simple: Just drop in a <script> tag and <a-scene>. A-Frame will handle 3D boilerplate, VR setup, and default controls. Nothing to install, no build steps.

* Declarative HTML: HTML is easy to read, understand, and copy-and-paste. Being based on top of HTML, A-Frame is accessible to everyone: web developers, VR enthusiasts, artists, designers, educators, makers, kids.

* Cross-Platform VR: Build VR applications for Vive, Rift, Daydream, GearVR, and Cardboard with support for all respective controllers. Don’t have a headset or controllers? No problem! A-Frame still works on standard desktop and smartphones.

* Entity-Component Architecture: A-Frame is a powerful three.js framework, providing a declarative, composable, reusable entity-component structure. HTML is just the tip of the iceberg; developers have unlimited access to JavaScript, DOM APIs, three.js, WebVR, and WebGL.

* Performance: A-Frame is optimized from the ground up for WebVR. While A-Frame uses the DOM, its elements don’t touch the browser layout engine. 3D object updates are all done in memory with little overhead under a single requestAnimationFrame call. For reference, see A-Painter, a Tilt Brush clone built in A-Frame that runs like native (90+ FPS).

* Tool Agnostic: Since the Web was built on the notion of HTML, A-Frame is compatible with most libraries, frameworks, and tools including React, Preact, Vue.js, d3.js, Ember.js, jQuery.

* Visual Inspector: A-Frame provides a handy built-in visual 3D inspector. Open up any A-Frame scene, hit <ctrl> + <alt> + i, and fly around to peek under the hood!


What I personally like about A-Frame is that it really simplifies the process of making WebVR sites. Without A-Frame, you would have to venture into the WebVR land and code scenes using [three.js](https://threejs.org/)or perhaps even just straight up [WebGL](https://developer.mozilla.org/en-US/docs/Web/API/WebGL_API). This might be fine for those who are more well versed in 