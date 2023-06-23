Step 1. Launch CryEngine1 (FarCryEditor). Select the desired group of static meshes. Export to .grp

Step 2. Run a clean project on CryEngine5. Import .grp from Step 1

Step 3. Remove all unnecessary that was imported. Should only be StaticMeshes

Step 4 Select all Static Meshes. Export to .grp

Step 5. Place the FBX files in the Objects folder. From this folder, the addon will search for the necessary assets. From which you need to build a group in the Blender3d scene. Next to the Objects folder, we place the .grp file itself

Step 6 Launch Blender3d. We look that in the scene the world scale (Unit Scale) is Metric and the value is 1.0

Step 7. Click File>Import>GRP select .grp

If there are a lot of Static Meshes in the group, the plugin may seem to hang. But in fact, he will look for and select the necessary Assets to build a group. Just be patient and don't touch your PC
