# godot-psx-shaders

![Godot PSX Shaders](https://i.imgur.com/11s4nQs.png)

## About

With those shaders you're able to emulate PSOne graphic limitations inside Godot engine. There's a bunch of parameters to tweak, like mesh resolution, vertex cull distance, specular intensity, reflection intensity(reflections are done via CubeMap), alpha scissor and so on. They're not hard to use and pretty self explanatory. ~~For some reason, GitHub is not accepting any of my gifs.~~

## Limitations

No real-time shadows support, shading at top-dow view looks kinda broken, CubeMap reflection doesn't work in editor sometimes.

## Tips

Disable all texture filters, use low resolution textures, disable real-time shadows to avoid a lot of glitches, if you don't want any shading just replace ```diffuse_lambert_wrap``` for ```unshaded```.
