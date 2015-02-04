# Savage2Art

Blender (2.63) and K2 Importer/Exporter - Using armature of existing model with mesh and faces of another model
1. import model in blender
2. delete mesh, leave armature
3. append model (mesh and faces) of choice
4. make vertex groups that correspond to armature (skeleton to body attachment)
5. define material file to use and add a UVMap component to mesh body
6. triangulate faces
7. Reset pose position to Rest position: pose mode, select all bones, clear transformations -> all
8. export model
9. export UV map (for texturing)

NOTE: 
to import a .clip, you must first import the corresponding model, then import the clip

texture file names are referenced in the .material files