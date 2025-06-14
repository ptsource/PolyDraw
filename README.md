# Polygonal modeling 

Polygonal modeling is an approach for modeling objects by representing or approximating their surfaces using polygons. Polygonal modeling is well suited to scanline rendering and is therefore the method of choice for real-time computer graphics. Alternate methods of representing 3D objects include NURBS surfaces, subdivision surfaces, and equation-based representations used in ray tracers.

# PTSource PolyDraw
### Current version 18 updated 10/06/2025 for Windows

PTSource PolyDraw is a 3D polygonal modeller for Windows x86 and x64 designed for creating and modifying 3D objects with precision and flexibility. Whether you're working with a mesh of 3D points or parametric NURBS curves, PTSource PolyDraw offers a robust set of tools for both beginners and professionals in 3D design. With support for importing and exporting to over 40 file formats, including WebVR and 3D printing, PTSource PolyDraw ensures seamless integration into your workflow.


|  System requirements  |  
|         :---:         | 
| Windows 8.1, 10 or 11 platforms arch x86 or x64. | 

## Download

 [![Maintenance](/images/maintained.svg)](https://wiki.ptsource.eu/soft/polydraw/start) [![You can download here.](/images/version-18-red.svg)](https://wiki.ptsource.eu/files_windows) [![You can download here.](/images/download-here-green.svg)](https://wiki.ptsource.eu/files_windows) [![Help here.](/images/docs-here-blue.svg)](https://wiki.ptsource.eu/soft/polydraw/start)

## Screenshots
<img src="https://raw.githubusercontent.com/ptsource/PolyDraw/master/images/01B.PNG" width="33%"><img src="https://raw.githubusercontent.com/ptsource/PolyDraw/master/images/02B.PNG" width="33%"><img src="https://raw.githubusercontent.com/ptsource/PolyDraw/master/images/03B.PNG" width="33%">
<img src="https://raw.githubusercontent.com/ptsource/PolyDraw/master/images/04B.PNG" width="33%"><img src="https://raw.githubusercontent.com/ptsource/PolyDraw/master/images/05B.PNG" width="33%"><img src="https://raw.githubusercontent.com/ptsource/PolyDraw/master/images/06B.PNG" width="33%">

## Features 

* Fast rendering (ASM 3d engine)
* WebVR A-Frame template generation.
* Exports to WebVR (ready for interactive web viewing), STL for 3D printing, JSON for ThreeJS and more, see supported formats bellow.
* Allows you to create objects from Sweeps & Extrusions, basic shapes (cubes, cylinders, etc), meshes (vertices & triangles) and parametric NURBS Curves.
* Pre-made example models inside the program folder under Objects. 
* Has lists to allow you to view & edit all the data by keyboard.


## Import and export table for latest version

|Format  | Import | Export | 
| ------------- | ------------- | ------------- | 
| PTSource PolyDraw (.D3D) | :white_check_mark: | :white_check_mark: |
| PTSource VRGrid (.VROBJ) | :x: | :white_check_mark: |
| 3DStudio Binary  (.3DS) | :white_check_mark: | :white_check_mark: |  
| 3DStudio Ascii (.ASC)  |  :white_check_mark:  |  :white_check_mark: | 
| 3DStudio Scene (.ASE)  |  :white_check_mark:  |  :white_check_mark: | 
| Spreadsheet Text (.CSV) |  :white_check_mark: |  :white_check_mark: | 
| A-Frame (.HTML + .OBJ)  |  :white_check_mark:  |  :white_check_mark: | 
| Wavefront (.OBJ)  |  :white_check_mark:  |  :white_check_mark: | 
| Collada Object (.DAE)  |  :white_check_mark:  | :white_check_mark: | 
| GLTF Binary (.GLB)  |  :x:  | :white_check_mark: | 
| Stereolit Binary (.STL)  |  :white_check_mark:  |  :white_check_mark: | 
| Stereolit Ascii (.STL)  |  :white_check_mark:  |  :white_check_mark: | 
| Hood Binary (.TRI)  |  :white_check_mark:  |  :white_check_mark: | 
| Hood Ascii (.TRI)  |  :white_check_mark:  |  :white_check_mark: |
| Open Inventor (.IV)  |  :white_check_mark:  |  :white_check_mark: |
| Polygon (.PLY)  |  :white_check_mark:  |  :white_check_mark: | 
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
| VRML 1.0 (.WRL)  |  :x:  |  :white_check_mark: | 
| VRML 2.0 (.WRL)  |  :x:  |  :white_check_mark: | 
| ThreeJS (.JSON)  | :x:  |  :white_check_mark: |  
| AutoCAD DXF (.DXF) |  :white_check_mark:  |  :x: | 
| POV-Ray (.POV) | :x: |  :white_check_mark: | 
| TECPLOT files (.TEC) | :x:  | :white_check_mark: | 
| Neutral Format (.NFF) | :white_check_mark:  | :x: | 
| S8 WorldToolkit (.NFF) | :white_check_mark:  | :x: |
| RtCW (.MDC) | :white_check_mark:  | :x: |
| Quake I (.MDL) | :white_check_mark:  | :white_check_mark: |
| Quake II (.MD2) | :white_check_mark:  | :x: |
| Quake III (.MD3) | :white_check_mark:  | :x: |
| Quake III Map (.PK3) | :white_check_mark:  | :x: |
| Raw Triangles (.RAW) | :white_check_mark:  | :white_check_mark: |
| Object Format (.OFF) | :white_check_mark:  | :x: | 
| SoftImage (.HRC) | :white_check_mark:  | :white_check_mark: | 
| BYU geometry (.BYU) | :white_check_mark:  | :white_check_mark: | 
| Digistar II VLA  ( .VLA )  | :white_check_mark:  | :white_check_mark: | 
| Biovision  ( .BVH )  | :white_check_mark:  | :x: | 
| Ogre XML ( .XML )  | :white_check_mark:  | :x: | 
| UnreaL ( .3D )  | :white_check_mark:  | :x: | 
| Izware Nendo ( .NDO )  | :white_check_mark:  | :x: | 
| 3D Terrain ( .HMP )  | :white_check_mark:  | :x: | 
| Terragen Terrain ( .TER )  | :white_check_mark:  | :x: | 
| BlitzBasic 3D ( .B3D )  | :white_check_mark:  | :x: |
| Extensible 3D ( .X3D )  | :x:  | :white_check_mark: |
| IFC/Step ( .IFC )  | :white_check_mark:  | :x: |
| Renderware ( .RWX )  | :x:  | :white_check_mark: |


**Note :** This software does not use a digitally signed installer, so
you might get a warning. You should dismiss it and continue.

-   Download the Installer.
-   When Windows says the installer is not trusted, click "more info"
    and then "run anyway".
-   Follow the instructions in the installer.
-   You can now launch the software from your desktop.

## Support

[![Visit homepage.](/images/homepage-here-yellowgreen.svg)](https://wiki.ptsource.eu/soft/polydraw/start)

