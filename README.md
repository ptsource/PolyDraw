# Introduction to Polygonal modeling 

Polygonal modeling is an approach for modeling objects by representing or approximating their surfaces using polygons. Polygonal modeling is well suited to scanline rendering and is therefore the method of choice for real-time computer graphics. Alternate methods of representing 3D objects include NURBS surfaces, subdivision surfaces, and equation-based representations used in ray tracers.

# PolyDraw

[![Maintenance](/images/2017.svg)]() [![Travis](/images/rust.svg)]()  [![You can download here.](/images/version-5.0-red.svg)](https://dl.orangedox.com/YYR2ih46hcVPtlG8lq?dl=1) [![You can download here.](/images/download-here-green.svg)](https://dl.orangedox.com/YYR2ih46hcVPtlG8lq?dl=1) [![Docs](/images/docs-here-blue.svg)](/docs/)

## Screenshots
![PolyDraw](https://raw.githubusercontent.com/ptsource/PolyDraw/master/images/20.png)![PolyDraw](https://raw.githubusercontent.com/ptsource/PolyDraw/master/images/21.png)![PolyDraw](https://raw.githubusercontent.com/ptsource/PolyDraw/master/images/22.png)
![PolyDraw](https://raw.githubusercontent.com/ptsource/PolyDraw/master/images/23.png)![PolyDraw](https://raw.githubusercontent.com/ptsource/PolyDraw/master/images/26.png)![PolyDraw](https://raw.githubusercontent.com/ptsource/PolyDraw/master/images/27.png)

### Current version 5.0 released 08/12/2017

PolyDraw is a 3D polygonal modeller, for creating or modifying 3D objects using a mesh of 3D points and parametric NURBS Curves .Exports to WebVR A-Frame with template and over 30 formats.

## Features 

* Fast rendering (ASM 3d engine)
* WebVR A-Frame template generation.
* Exports to WebVR A-Frame OBJ with template (ready for interactive web viewing), STL for 3D printing, JSON for ThreeJS and more, see supported formats bellow.
* Allows you to create objects from Sweeps & Extrusions, basic shapes (cubes, cylinders, etc), meshes (vertices & triangles) and parametric NURBS Curves.
* Pre-made example models inside the program folder under Objects. 
* Has lists to allow you to view & edit all the data by keyboard.

## Formats import export table current version

|Format  | Import | Export | 
| ------------- | ------------- | ------------- | 
| 3D Studio Binary  (.3DS) | :+1: | :+1: |  
| 3D Studio Ascii (.ASC)  |  :+1:  |  :+1: | 
| 3D Studio Scene (.ASE)  |  :no_entry:  |  :no_entry: | 
| Spreadsheet Text File (.CSV) |  :+1: |  :+1: | 
| Wavefront (.OBJ) + WebVR A-Frame (.HTML)  |  :+1:  |  :+1: | 
| Wavefront Object (.OBJ)  |  :+1:  |  :+1: | 
| Collada Object (.DAE)  |  :+1:  | :+1: | 
| Stereolithography Binary (.STL)  |  :+1:  |  :+1: | 
| Stereolithography Ascii (.STL)  |  :+1:  |  :+1: | 
| Hood Triangle Binary (.TRI)  |  :+1:  |  :+1: | 
| Hood Triangle Ascii (.TRI)  |  :+1:  |  :+1: |
| Open Inventor (.IV)  |  :+1:  |  :+1: |
| Stanford Polygon Library (.PLY)  |  :+1:  |  :+1: | 
| LightWave (.LWO)  |  :+1:  | :no_entry: | 
| LightWave Scene (.LWS)  |  :+1:  | :no_entry: | 
| TrueSpace (.COB)  |  :+1:  | :no_entry: | 
| TrueSpace Scene (.SCN)  |  :+1:  | :no_entry: | 
| XGL (.XGL)  |  :+1:  | :no_entry: | 
| ZGL (.ZGL)  |  :+1:  | :no_entry: |
| Modo (.LXO)  |  :+1:  | :no_entry: | 
| Autodesk  ( .FBX )  |  :+1:  | :no_entry:  | 
| VRML 1.0 (.WRL)  |  :+1:  |  :+1: | 
| VRML 2.0 (.WRL)  |  :+1:  |  :+1: | 
| ThreeJS (.JSON)  | :no_entry:  |  :+1: | 
| Stanford Polygon Library (.PLY) | :+1:  |  :+1: | 
| AutoCAD DXF (.DXF) |  :+1:  |  :+1: | 
| POV-Ray (.POV) | :no_entry: |  :+1: | 
| TECPLOT files (.TEC) | :no_entry:  | :no_entry: | 
| Neutral File Format (.NFF) | :no_entry:  | :no_entry: | 
| Sense8 WorldToolkit (.NFF) | :no_entry:  | :no_entry: |
| RtCW (.MDC) | :no_entry:  | :no_entry: |
| GEOMVIEW files (.OFF) | :no_entry:  | :no_entry: | 
| Movie.BYU geometry (.BYU) | :no_entry:  | :no_entry: | 
| Blender 3D ( .BLEND ) | :no_entry:  | :no_entry: | 
| glTF  ( .GLT ) | :no_entry:  | :no_entry: | 
| Digistar II VLA  ( .VLA )  | :no_entry:  | :no_entry: | 
| Biovision  ( .BVH )  | :+1:  | :no_entry: | 
| Ogre XML ( .XML )  | :+1:  | :no_entry: | 

[![You can download here.](/images/download-here-green.svg)](https://dl.orangedox.com/YYR2ih46hcVPtlG8lq?dl=1)

## Support

[![Visit homepage.](/images/homepage-here-yellowgreen.svg)](https://www.facebook.com/www.ptsource.eu/)
