# about
---
**penger:**
https://penger.neocities.org/

**model made by:**
https://github.com/Max-Kawula

**all models licensed under CC0:**
https://creativecommons.org/public-domain/cc0/

# other things
---
**inverted hulls:**
penger.obj has an inverted hull, you need backface culling to see the model correctly.

in blender after you import the model you can open the python console and paste this line:
bpy.context.object.active_material.use_backface_culling = True

**default materials**
blender forces me to use a principled bsdf when exporting objs so the mtl file has a bunch of random values attached to it. i'll consider fixing it later.
