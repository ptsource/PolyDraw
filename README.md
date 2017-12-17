# Introduction to Polygonal modeling 

Polygonal modeling is an approach for modeling objects by representing or approximating their surfaces using polygons. Polygonal modeling is well suited to scanline rendering and is therefore the method of choice for real-time computer graphics. Alternate methods of representing 3D objects include NURBS surfaces, subdivision surfaces, and equation-based representations used in ray tracers.

# PolyDraw

[![Maintenance](/images/2017.svg)]() [![Travis](/images/rust.svg)]()  [![You can download here.](/images/version-5.0-red.svg)](https://dl.orangedox.com/YYR2ih46hcVPtlG8lq?dl=1) [![You can download here.](/images/download-here-green.svg)](https://dl.orangedox.com/YYR2ih46hcVPtlG8lq?dl=1) [![Docs](/images/docs-here-blue.svg)](/docs/)

## Screenshots
![PolyDraw](https://raw.githubusercontent.com/ptsource/PolyDraw/master/images/20.png)![PolyDraw](https://raw.githubusercontent.com/ptsource/PolyDraw/master/images/21.png)![PolyDraw](https://raw.githubusercontent.com/ptsource/PolyDraw/master/images/22.png)
![PolyDraw](https://raw.githubusercontent.com/ptsource/PolyDraw/master/images/23.png)![PolyDraw](https://raw.githubusercontent.com/ptsource/PolyDraw/master/images/26.png)![PolyDraw](https://raw.githubusercontent.com/ptsource/PolyDraw/master/images/27.png)

### Current version 6.0 released 17/12/2017

PolyDraw is a 3D polygonal modeller, for creating or modifying 3D objects using a mesh of 3D points and parametric NURBS Curves .Exports to WebVR A-Frame with template and over 30 formats.

## Features 

* Fast rendering (ASM 3d engine)
* WebVR A-Frame template generation.
* Exports to WebVR (ready for interactive web viewing), STL for 3D printing, JSON for ThreeJS and more, see supported formats bellow.
* Allows you to create objects from Sweeps & Extrusions, basic shapes (cubes, cylinders, etc), meshes (vertices & triangles) and parametric NURBS Curves.
* Pre-made example models inside the program folder under Objects. 
* Has lists to allow you to view & edit all the data by keyboard.
* RGB Colour Picker.
* RGB > ACI Colour Converter.

## Formats import export table current version

|Format  | Import | Export | 
| ------------- | ------------- | ------------- | 
| 3D Studio Binary  (.3DS) | :white_check_mark: | :white_check_mark: |  
| 3D Studio Ascii (.ASC)  |  :white_check_mark:  |  :white_check_mark: | 
| 3D Studio Scene (.ASE)  |  :x:  |  :x: | 
| Spreadsheet Text File (.CSV) |  :white_check_mark: |  :white_check_mark: | 
| Wavefront (.OBJ) + WebVR A-Frame (.HTML)  |  :white_check_mark:  |  :white_check_mark: | 
| Wavefront Object (.OBJ)  |  :white_check_mark:  |  :white_check_mark: | 
| Collada Object (.DAE)  |  :white_check_mark:  | :white_check_mark: | 
| Stereolithography Binary (.STL)  |  :white_check_mark:  |  :white_check_mark: | 
| Stereolithography Ascii (.STL)  |  :white_check_mark:  |  :white_check_mark: | 
| Hood Triangle Binary (.TRI)  |  :white_check_mark:  |  :white_check_mark: | 
| Hood Triangle Ascii (.TRI)  |  :white_check_mark:  |  :white_check_mark: |
| Open Inventor (.IV)  |  :white_check_mark:  |  :white_check_mark: |
| Stanford Polygon Library (.PLY)  |  :white_check_mark:  |  :white_check_mark: | 
| LightWave Object (.LWO)  |  :white_check_mark:  | :x: | 
| LightWave Scene (.LWS)  |  :white_check_mark:  | :x: | 
| TrueSpace Object (.COB)  |  :white_check_mark:  | :x: | 
| TrueSpace Scene (.SCN)  |  :white_check_mark:  | :x: | 
| Quick3D Object (.Q3O)  |  :x:  | :x: | 
| Quick3D Scene (.Q3S)  |  :x:  | :x: | 
| XGL (.XGL)  |  :white_check_mark:  |:x: | 
| ZGL (.ZGL)  |  :white_check_mark:  | :x: |
| Modo (.LXO)  |  :white_check_mark:  | :x: | 
| Autodesk  ( .FBX )  |  :white_check_mark:  | :x:  | 
| VRML 1.0 (.WRL)  |  :white_check_mark:  |  :white_check_mark: | 
| VRML 2.0 (.WRL)  |  :white_check_mark:  |  :white_check_mark: | 
| ThreeJS (.JSON)  | :x:  |  :white_check_mark: | 
| Stanford Polygon Library (.PLY) | :white_check_mark:  |  :white_check_mark: | 
| AutoCAD DXF (.DXF) |  :white_check_mark:  |  :white_check_mark: | 
| POV-Ray (.POV) | :x: |  :white_check_mark: | 
| TECPLOT files (.TEC) | :x:  | :white_check_mark: | 
| Neutral File Format (.NFF) | :x:  | :x: | 
| Sense8 WorldToolkit (.NFF) | :x:  | :x: |
| RtCW (.MDC) | :x:  | :x: |
| Quake II (.MD2) | :x:  | :x: |
| Quake III (.MD3) | :x:  | :x: |
| Raw Triangles (.RAW) | :x:  | :x: |
| Object File Format (.OFF) | :x:  | :x: | 
| SoftImage (.HRC) | :x:  | :white_check_mark: | 
| Movie.BYU geometry (.BYU) | :x:  | :white_check_mark: | 
| Blender 3D ( .BLEND ) | :x:  | :x: | 
| glTF  ( .GLT ) | :x:  |:x: | 
| Digistar II VLA  ( .VLA )  | :x:  | :white_check_mark: | 
| Biovision  ( .BVH )  | :white_check_mark:  | :x: | 
| Ogre XML ( .XML )  | :white_check_mark:  | :x: | 

[![You can download here.](/images/download-here-green.svg)](https://dl.orangedox.com/YYR2ih46hcVPtlG8lq?dl=1)

## Support

[![Visit homepage.](/images/homepage-here-yellowgreen.svg)](https://www.facebook.com/www.ptsource.eu/)
