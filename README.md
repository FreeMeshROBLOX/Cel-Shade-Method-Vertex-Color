# Documentation Method Cel-Shade: Method Vertex Color

This is an example repo that can be copied into the `/docs` folder of your codebase. It follows [the Diátaxis method](https://diataxis.fr/) of technical documentation management. Here are some useful sections to keep in the README of your project.

## Introduction

An introduction to the area of the organization that this project lives in and the context around why this project was designed.

## Getting Started

How to get this repo up and running.

### I'm a developer working on this project, where do I start?

Instructions for a developer that may be making changes to this repository.

### I'm a consumer of this project, where do I start?

Instructions for someone that may be using the production version of this project.


---

## Cel-Shade-Method-Vertex-Color (Roblox)

This is one of my personal methods for achieving a cel-shaded look in Roblox.

The method is named after the core technique used to create this shading style. Technically, this is not a full or complex rendering system. It is a simple and practical trick that allows you to fake a cel-shaded appearance using standard tools.

### Core idea

**Cel-Shade-Method-Vertex-Color** is based on:

* Cloning the original object
* Manually modifying the mesh and vertex colors in Blender
* Adjusting Roblox lighting settings, especially using very high Sun values

The shading effect is achieved by combining modified vertex colors with lighting behavior rather than using custom shaders.

### Features and limitations

* Works on all devices, since it relies only on standard Roblox rendering techniques
* Semi-universal, can be applied to almost any object if you know how to work in Blender
* Not compatible with all player character mesh combinations
* Does not require custom shaders or engine modifications

### Blender version

At the time this method was discovered, Blender **3.6** was used.
This version is now outdated, but newer Blender versions can also be used.
You only need to find compatible addon versions for your Blender release.

### Addons used

The following Blender addons were used during development:

* **Vertex Color Plus**
  [https://github.com/oRazeD/VertexColorPlus](https://github.com/oRazeD/VertexColorPlus)

* **Vertex Color Master**
  [https://github.com/andyp123/blender_vertex_color_master](https://github.com/andyp123/blender_vertex_color_master)

* **Bake to Vertex Color**
  [https://3dbystedt.gumroad.com/l/zdgxg](https://3dbystedt.gumroad.com/l/zdgxg)

---
