# ModifierEmpties2.8
Blender addon for adding modifiers controlled by empties.

## What
Adds modifiers which are controlled by empties to selected objects.
### Features
Includes the following modifier empties:
* Array Empty  
Adds an array modifier and an empty that can change it with location, rotation, and scale.  
* Radial Array Empty  
Adds an array modifier and an empty that spins the array copies in a full circle around an axis.  
* Bent Array Empty  
Bends objects around an empty with simple deform and adds an array modifier  
* Mirror Empty  
Mirrors objects around empty  
* Cast Empty  
Adds Cast modifier with an empty being the center of the cast  
* Simple Deform Empty  
Adds Simple Deform modifier with empty being center of the deform  
* Quick Hook Empty  
Adds a new vertex group to mesh, made up of selected vertices.  
Then adds a Hook modifier, using the quick hook vertex group.  
Then adds an empty which controls the hook modifier.  

## Installation  
### Requirements  
Works on Windows, Mac, and Linux.  
Meant for Blender 2.8 Beta
### How to Install  
Download the python file (put it in a place where you can easily find it, like your desktop)  
In Blender's settings, go to the addons tab  
At the bottom, click "Install from File"  
Find where you put the python file, select it, and click "Install from File" 

## Using
You can add a modifier empty from...
* 3D View > Add Menu > Modifier Empties
* 3D View > Operator Search > Add \*Modifier empty name\*  
## Notes
You must be in Object mode to add modifier empties.

## Changelog  
### 0.2  
Update addon to the new 3D cursor (doesn't support 3D cursor rotation)

### 0.3
Fix scene.update() error in Radial Array.  
Deselect all objects and make modifier empty active after adding a modifier empty. Thanks to Blender Artists user uruburei
 for pointing this out.  
Add Mini Manual.  
