![image](/penger/screenshots/penger-obj.png)

# About
---
A collection of Penger models in obj format.

**Penger:**  
https://penger.city/

**Model made by:**  
https://github.com/Max-Kawula

**All models licensed under Penger Public License:**  
No copyright. If you are having fun, you are allowed to use and distribute whatever you want. You can't forbid anyone to use penger freely. No requirements.

# Other things
---
**inverted hulls:**  
penger.obj has an inverted hull, which is 2nd mesh used to create an outline around penger.
this may make the model appear to be textured incorrectly depending your rendering method.

For Blender, these viewport settings will show the model correctly.
![viewport](/penger/screenshots/viewport-settings.png)

This python line will do the same but for EEVEE
`bpy.context.object.active_material.use_backface_culling = True`
make sure you are using the EEVEE renderer.
