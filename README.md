# Godot Standard Light Shader
This shader attempts to replicate Godot's default lighting, meant to be used as a starting point for creating a custom lighting shader.

To be more specific, it replicates the look of the Godot 4.1.1 standard material with the *Lambert* diffuse mode, and the *Schlick-GXX* specular mode.

The shader is essentially a very barebones version of the [internal Godot shader](https://github.com/godotengine/godot/blob/09a2a7c54eae05708894476a8d9a25dae95bbdf7/drivers/gles3/shaders/scene.glsl).

Here's quick comparison of the shader and the standard material with various roughness settings, for both metallic and dielectric materials:

![image](https://github.com/RustyRoboticsBV/GodotStandardLightShader/blob/main/TestResults.png?raw=true)

Happy shader coding!
