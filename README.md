# Polygonal modeling 

Polygonal modeling is an approach for modeling objects by representing or approximating their surfaces using polygons. Polygonal modeling is well suited to scanline rendering and is therefore the method of choice for real-time computer graphics. Alternate methods of representing 3D objects include NURBS surfaces, subdivision surfaces, and equation-based representations used in ray tracers.

# PolyDraw
### Current version 11 released 23/07/2018 compiled and tested under Windows 10


PolyDraw is a free 3D polygonal modeller, for creating or modifying 3D objects using a mesh of 3D points and parametric NURBS Curves .Exports and imports to over 40 formats including WebVR and 3D Printing.

[![Maintenance](/images/2017.svg)]() [![Travis](/images/rust.svg)]()  [![You can download here.](/images/version-11-red.svg)](https://dl.orangedox.com/YYR2ih46hcVPtlG8lq?dl=1) [![You can download here.](/images/download-here-green.svg)](https://dl.orangedox.com/YYR2ih46hcVPtlG8lq?dl=1) [![Help here.](/images/docs-here-blue.svg)](https://wiki.ptsource.eu/) [![Donate here.](/images/donate.svg)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=D3EH7N735BVVW)

## Screenshots
![PolyDraw](https://raw.githubusercontent.com/ptsource/PolyDraw/master/images/01.PNG)![PolyDraw](https://raw.githubusercontent.com/ptsource/PolyDraw/master/images/02.PNG)![PolyDraw](https://raw.githubusercontent.com/ptsource/PolyDraw/master/images/03.PNG)
![PolyDraw](https://raw.githubusercontent.com/ptsource/PolyDraw/master/images/04.PNG)![PolyDraw](https://raw.githubusercontent.com/ptsource/PolyDraw/master/images/05.PNG)![PolyDraw](https://raw.githubusercontent.com/ptsource/PolyDraw/master/images/06.PNG)

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
| 3D Studio Scene (.ASE)  |  :white_check_mark:  |  :white_check_mark: | 
| Spreadsheet Text File (.CSV) |  :white_check_mark: |  :white_check_mark: | 
| Wavefront (.OBJ) + WebVR A-Frame (.HTML)  |  :white_check_mark:  |  :white_check_mark: | 
| Wavefront Object (.OBJ)  |  :white_check_mark:  |  :white_check_mark: | 
| Collada Object (.DAE)  |  :white_check_mark:  | :white_check_mark: | 
| GLTF Binary (.GLB)  |  :x:  | :white_check_mark: | 
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
| Quick3D Object (.Q3O)  |  :white_check_mark:  | :x: | 
| Quick3D Scene (.Q3S)  |  :white_check_mark:  | :x: | 
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
| Neutral File Format (.NFF) | :white_check_mark:  | :x: | 
| Sense8 WorldToolkit (.NFF) | :white_check_mark:  | :x: |
| RtCW (.MDC) | :white_check_mark:  | :x: |
| Quake I (.MDL) | :white_check_mark:  | :white_check_mark: |
| Quake II (.MD2) | :white_check_mark:  | :x: |
| Quake III (.MD3) | :white_check_mark:  | :x: |
| Quake III Map (.PK3) | :white_check_mark:  | :x: |
| Raw Triangles (.RAW) | :white_check_mark:  | :white_check_mark: |
| Object File Format (.OFF) | :white_check_mark:  | :x: | 
| SoftImage (.HRC) | :white_check_mark:  | :white_check_mark: | 
| Movie.BYU geometry (.BYU) | :white_check_mark:  | :white_check_mark: | 
| Digistar II VLA  ( .VLA )  | :white_check_mark:  | :white_check_mark: | 
| Biovision  ( .BVH )  | :white_check_mark:  | :x: | 
| Ogre XML ( .XML )  | :white_check_mark:  | :x: | 
| UnreaL ( .3D )  | :white_check_mark:  | :x: | 
| Izware Nendo ( .NDO )  | :white_check_mark:  | :x: | 
| 3D GameStudio Terrain ( .HMP )  | :white_check_mark:  | :x: | 
| Terragen Terrain ( .TER )  | :white_check_mark:  | :x: | 
| BlitzBasic 3D ( .B3D )  | :white_check_mark:  | :x: |
| Extensible 3D ( .X3D )  | :x:  | :white_check_mark: |
| IFC/Step ( .IFC )  | :white_check_mark:  | :x: |
| Renderware ( .RWX )  | :x:  | :white_check_mark: |

[![You can download here.](/images/download-here-green.svg)](https://dl.orangedox.com/YYR2ih46hcVPtlG8lq?dl=1)

## Support

[![Visit homepage.](/images/homepage-here-yellowgreen.svg)](https://www.ptsource.eu/)

[![Visit homepage.](https://webstats.ptsource.eu/github-polydraw.gif)](https://www.ptsource.eu/)
