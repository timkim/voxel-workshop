---
title: "Exporting to WebVR Using Mozilla A-Frame"
layout: post
---

# What is A-Frame?
![A-Frame](img/aframe_inspector.png "A-Frame")

From the [A-Frame website](https://aframe.io/docs/0.7.0/introduction/#what-is-a-frame):

A-Frame is based on top of HTML, making it simple to get started. But A-Frame is not just a 3D scene graph or a markup language; the core is a powerful entity-component framework that provides a declarative, extensible, and composable structure to three.js.

## Features:
* **Simple Installation:** All that is required to start using A-Frame is a `<script>` that points to the A-Frame js file and then use the `<a-scene>` tag in your HTML. 

* **Use Declarative HTML:** Construct your scenes using HTML tags that represent certain objects in the scene. 

* **Cross-Platform:** The power of the web allows us to use A-Frame practically anywhere that supports a browser with WebGL. 

* **Visual Inspector:** A powerful visual 3D inspector that allows you to debug your scenes. Use it on any A-Frame with the key-command: `<ctrl> + <alt> + i`.

More listed features at the [A-Frame website](https://aframe.io/docs/0.7.0/introduction/#features).

What I personally like about A-Frame is that it really simplifies the process of making WebVR sites. Without A-Frame, you would have to venture into the WebVR land and code scenes using [three.js](https://threejs.org/) or perhaps even just straight up [WebGL](https://developer.mozilla.org/en-US/docs/Web/API/WebGL_API). This might be fine for those who are more well versed in coding 3D, but this is quite a daunting task for those looking to wet their feet. 

## Working with PhoneGap
Since A-Frame is all web based, it works pretty well with PhoneGap! Aside from annoying CSP-issues, it should work out of the box fairly well. I haven't personally seen much outside of demos of A-Frame and PhoneGap, but perhaps one of you will change that. Let's see some VR apps made with PhoneGap, eh?

In this workshop, we'll clone down the `phonegap-magicavoxel-aframe-template` that has a small premade A-Frame project ready to go. Once your models are ready to be viewed on your phone, we'll import them into the template and then use `phonegap serve` to connect our phones to the A-Frame project. 

## Let's Start Our PhoneGap Project!
Enough with words, code time now! First things first, let us create our PhoneGap project using a template:
`$ phonegap create myVoxelProject --template phonegap-magicavoxel-aframe-template`

And if all goes successfully, our PhoneGap project directory structure should look something like:
![Directory Screenshot](img/directory_screenshot.png "Directory Screenshot")
