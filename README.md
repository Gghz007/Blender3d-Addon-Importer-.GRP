At one time I encountered a problem. How can you move a large building? How to move a building that consists of hundreds of assets. Without rebuilding in the new engine?
This was supposed to happen in 2 stages.
1. Export assets to Blender3D.
2. Export assets from Blender3D to the new engine.
Only the first addon for import into Blender3D has been implemented. The second addon for export to the engine was not made. If there is a request for this. Write, let's discuss.


How work Addon?

Step 1. Launch CryEngine1 (FarCryEditor). Select the desired group of StaticMeshes. Export to .grp

Step 2. Run a Clean Project on CryEngine5. Import .grp from Step 1

Step 3. Remove all unnecessary that was Imported. Should only be StaticMeshes

Step 4 Select all StaticMeshes. Export to .grp

Step 5. Download Assets FC1. https://goo.su/Sxc2D
Place the FBX files in the "Objects" folder. From this folder, the addon will search for the necessary assets. From which you need to build a group in the Blender3d scene. Next to the "Objects" folder, we place the .grp file itself

Step 6 Launch Blender3d (3.2). We look that in the scene the world scale (Unit Scale) is Metric and the value is 1.0

Step 7. Click File>Import>GRP select .grp

If there are a lot of StaticMeshes in the group, the plugin may seem to hang. But in fact, he will look for and select the necessary Assets to build a group. Just be patient and don't touch your PC
