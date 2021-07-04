---
layout: post
title: RollEngine
date: 2021-07-04 23:16:00 +0300
description: Graphic Engine developed at ESAT.
img: RollEngine.PNG # Add image post (optional)
tags: [Graphic, Development, C++, OpenGL]
---

After 9 months of work with a classmate, we were able to create a Graphic Engine from zero using C++ and OpenGL. Using some libraries like GLFW and TinyOBJLoader, we were able to accomplish an engine that runs with two threads and the user is able to interact with it thanks to the ImGui interface or directly trough scripts made on Lua. The possibilities of the engine includes:

* Create cubes, quads or load geometries trough .obj files.
* Use three types of materials with any of the entities: All painted with the same color, all painted depending on their normals, or all painted with a texture.
* Asign any transform to any of the entities, including a parenthood option.
* Three type of lights included: directional, spotlight and pointlight. Directional lights include shadow mapping.
* Includes Deferred Shading to render the scene.
* Includes Render to Texture to include any post-processing. Includes HDR with Bloom and inverting colors.
