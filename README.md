# Documentation Method Cel-Shade: Method Vertex Color
Cel-Shade: Vertex Color Method is a simple technique to achieve a stylized cel-shaded look for Roblox places and projects. 
This repository explains how the method works and how to apply it in practice.

## Introduction
This is one of my personal methods for achieving a cel-shaded look in Roblox.

The method is named after the core technique used to create this shading style. 
Technically, this is not a full or complex rendering system. 
It is a simple and practical trick that allows you to fake a cel-shaded appearance using standard tools.

Also i have old video about that method. Some information can be outdate but if you like more video format go on.

### Old Video
[![Cel Shade Demo](https://img.youtube.com/vi/Dcj6fNwTie0/maxresdefault.jpg)](https://youtu.be/Dcj6fNwTie0)

### Core idea

**Cel-Shade-Method-Vertex-Color** is based on:

* Cloning the original object
* Manually modifying the mesh and vertex colors in Blender
* Adjusting Roblox lighting settings, especially using very high Sun values

The shading effect is achieved by combining modified vertex colors with lighting behavior rather than using custom shaders.

### Features and limitations

* + Works on all devices, since it relies only on standard Roblox rendering techniques
* + Semi-universal, can be applied to almost any object if you know how to work in Blender
* - Not compatible with all player character mesh combinations
* - Addition load the twofold increase in resource consumption per model with this effect.

### Sub-Method
For now this method have 3 sub solution some problem you can combine all off this to solve you problem.
Also i give hime name.
* Orign Vertex which requred some tools knowladge in blender and slower need do by hand 
* Simpler simpler automatic method, but it is only suitable for simpler objects in terms of coloring and does not support textures.
* Static approach that allows you to support objects with textures, but it only works for static objects.

## Getting Started
How to do that?
For more fast and simple using i have plugin and project with settings up all script to achive this cel shade

Have some limitation but if you wanna by self do all thigs need required this tools:

### Blender

At the time this method was discovered, Blender **3.6** was used.
This version is now outdated, but newer Blender versions can also be used.
You only need to find compatible addon versions for your [Blender release](https://www.blender.org/download/).

### Addons 

The following Blender addons were used tool for modificated mesh:
* **[Bake to Vertex Color](https://3dbystedt.gumroad.com/l/zdgxg)**

* **[Vertex Color Plus](https://github.com/oRazeD/VertexColorPlus)**

* **[Vertex Color Master](https://github.com/andyp123/blender_vertex_color_master)**





