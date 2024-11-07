# Lab 07 - Smoke with Unity's Shader Graph

## Team 
Worked with Clara! 

## Gif of Smoke Vortex 
<img src = "https://github.com/thumun/lab07-smoke/blob/main/Untitled%20video%20-%20Made%20with%20Clipchamp.gif?raw=true"/>

The shape is not exactly what I wanted it to be, but it does look smoke-like! 

## Shadergraph Screenshots 
<img src = "https://github.com/thumun/lab07-smoke/blob/main/Screenshot%202024-11-06%20194051.png?raw=true"/>
<img src = "https://github.com/thumun/lab07-smoke/blob/main/Screenshot%202024-11-06%20194129.png?raw=true"/>

I added a sine wave just for fun (and I think it adds a more stylized look to the smoke effect). 

## Details:
The smoke has the following attributes (in accordance with the lab guidelines): 
- Displace your vertices by adding to them the mesh's surface normals that have themselves been added to a Perlin noise texture
- The Perlin noise texture should apply a positive and negative displacement; this means you'll need to use some math nodes to remap the RGB value to the range [-1, 1]
- The vertex displacement should be minimal at the bottom of the cylinder and extreme at the top of the cylinder
- The smoke should animate over time
- The fragment output of your shader should be __opaque when viewed at a glancing angle__ and __transparent when viewed head-on__.
- The smoke should fade into transparency at its top

Assets used: 
- A [mesh](smoke_cylinder.obj) 
- A [Perlin noise generator](http://kitfox.com/projects/perlinNoiseMaker/) 

