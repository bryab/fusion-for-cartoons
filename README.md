# Fusion for Cartoons

This repository contains Scripts, Fuses and Macros for Blackmagic Fusion, with a focus on assisting a compositing pipeline for 2D/3D animation productions.

Please suggest any improvements to these macros, if you find any bugs with them!

## Installation

Clone this repository, and add it to the `UserPaths` path in the Fusion PathMap settings.

## Macros

### CartoonRimLightMask

Create a mask to create a procedural rim light effect, using a generated normal map based on the alpha channel.

### CartoonOffsetMask

Create a simpler 'alpha offset' mask to achieve a rim light with a harder edge.

### CartoonFillMask

This is a simple "color key" node meant for keying out solid fill colors from 2D artwork, but rather than 'keying out' a color, it produces a mask for that color.

### Sprite3D

Create a "Sprite" in 3D space from a bitmap source. This can be used to add 2D objects to a 3D scene, in such a way that they are always facing camera.
