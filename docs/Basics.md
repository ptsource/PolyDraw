## PTSourceDraw3D Basics

### Selections

In PTSourceDraw3D, most actions work on the current selection (all the vertices & triangles selected), or on everything if nothing is selected.
To select items, either click on an object in the "Objects List", or select the vertices & triangles individually by hitting "S" on your keyboard to change to selection mode, and drag a rectangle around the vertices & triangles you want.

You can also hold the "Control" key (or "Ctrl" key) as you click on individual vertices in the "Vertices List" & "Triangles List", or holding the "Control" key as you right-click near vertices in any of the views.

### Edit Modes

There are 5 different editing modes, as shown in the "Edit Mode" menu. The helpbar on the bottom shows the different operations you can do in each mode. For example, in "Move" mode, dragging the left mouse button around will move the view.
However, if you hold down the "Control" key on your keyboard, dragging the left mouse button around will move the currently selected vertices (or all vertices if nothing is selected).

The basic functions of each mode are:
* Edit mode (hit 'E'):	Move individual vertices.
* Select mode (hit 'S'):	Make a selection of vertices & triangles by dragging left mouse button.
* Zoom mode (hit 'Z'):	Change an object's size, or zoom a view in & out.
* Move mode (hit 'M'):	Move an object, or a view.
* Rotate mode (hit 'R'):	Rotate an object.

### Basic Tutorial to create 2 cubes, side by side.

* Create a new document (click on File->New, or hit 'Ctrl' and 'N')
* Insert a cube (click on Insert->Insert Cube, or hit 'I' then 'C'). The whole cube will automatically be selected.
* Change to Zoom mode (click on Edit Mode->Zoom, or hit 'Z')
* Hold down the "Control" key on your keyboard, press the left mouse button somewhere in a 2D View (Top, Front or Side View), and hold the button down while you drag the mouse up a little. The cube should be about half the size it started.
 * Change to Move mode (click on Edit Mode->Move, or hit 'M')
 * Hold down the "Control" key on your keyboard, press the left mouse button somewhere in the "Front View", and hold the button down while you drag the mouse a little, until the cube is on the left hand side of the Front View.
* Since the cube is already selected, make a copy of it by pressing Edit->Copy and then Edit->Paste (hit 'Ctrl' and 'C', then 'Ctrl' and 'V'). 
There should now be a second cube in the centre of the Front View. 
Note: Whenever you Paste an object, PTSourceDraw3D automatically changes to 'Move' Mode.
* Hold down the "Control" key while you drag the new cube to the right side of the Front View.
* The "Objects List" shows that there are 2 objects (both cubes). To change the name of the 'Clipboard Object', double click on it or hit 'Enter'. Type in a new name, such as '2nd Cube'.
* It should be obvious now that there are 2 cube objects. To change the color of a cube, click on that cube in the Objects List (to select it's vertices & triangles), then hit 'C' (or click on Color->'Set Triangle Colors'). You should see a color selection window. Click on the color you want. (For a large color range, click on 'Define Custom Colors').
* To set the colors of the front face of a cube, change to Select mode (hit 'S', or click on Edit Mode->Select).


