scene contains:
A diffuse red sphere
A reflective green cube
A transparent glass sphere
A checkerboard floor
Two light sources

All scene objects are rendered using ray tracing in the fragment shader

Local illumination uses the Phong lighting model, including:
Ambient lighting
Diffuse lighting
Specular highlights

Shadow rays are cast from each surface intersection toward each light source
The cube uses reflective ray tracing
The glass sphere implements transparent, glass-like refraction

The scene contains two light sources:
A warm primary light
A cooler blue secondary light

Interactive Controls:
Click and drag on the canvas to orbit the camera around the scene
Max bounces ontrols the maximum number of iterative ray-tracing bounce steps
Ambient Strength controls the amount of ambient illumination in the scene
Glass IOR controls the index of refraction of the glass sphere
Light 2 Power controls the intensity of the second blue light source