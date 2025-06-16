# Simulating Translucence in Human Skin

<p align="center"><img src="https://github.com/Noctiluce/skin-texture/blob/master/images/skin.gif" alt="Animated gif" width="100%" /></p>

This project demonstrates a custom **real-time rendering pipeline** designed to simulate the **translucence of human skin**.  
Using **OpenGL shaders** and **C++**, it performs **subsurface light transport calculations** to approximate how light diffuses through skin layers, yielding a soft, realistic appearance.

## 🔹Features
- **Translucence Model:** Approximates **subsurface scattering** to capture softness and depth in skin.
- **Custom Shaders:** Implemented in **GLSL**, integrated into a custom pipeline.
- **C++ Core:** Built from scratch to handle geometry, materials, and lighting efficiently.
- **Procedural Texturing:** Combines base texture with scattering effects in real time.

## 🔹Tech Stack
- **C++**, **OpenGL**, **GLSL**
- Custom rendering pipeline (forward rendering)

## 🔹About
This renderer highlights my ability to:
- Develop low-level rendering techniques.
- Integrate custom shaders and C++ code efficiently.
- Handle GPU-side computations and data structures.

## 🔹See more
➥ [Portfolio](https://noctiluce.github.io)  
➥ [LinkedIn](https://www.linkedin.com/in/felix-rollet/)  


## Building
**Prerequisite**: CMake

To build this program, download the source code using ``git clone https://github.com/Noctiluce/Simulating-Translucence-in-Human-Skin`` or directly the zip archive.
Then run the `` launch.sh`` shell script.

You can do it manually by following these commands:
```shell script
mkdir build
cd build
cmake -DCMAKE_BUILD_TYPE=Release ..
make -j
./program
```



## Gallery
#### YouTube Video

<a href="https://www.youtube.com/watch?v=MlTtGBSUrVE" target="_blank"><img src="https://github.com/Noctiluce/skin-texture/blob/master/images/youtube_skin.PNG" 
alt="Skin Texture" width="100%" height="auto" border="10" /></a>

