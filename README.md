# io_scene_sonic_heroes_anm

This plugin for Blender 3D allows you to import and export RenderWare animations (`.anm`) for Sonic Heroes. Based on [Renderware-.anm-IO-Tool](https://github.com/Shadowth117/Renderware-.anm-IO-Tool).

Poorly tested. Animation export may be incorrect due to broken keyframe sorting. Before exporting, make sure the keyframes contain the location and euler angle data for each axis. The first keyframes on the timeline must be set for each bone. 

## How to import animation

1. Import DFF model into Blender
2. Make armature active
3. Import ANM animation

## Requirements

* Blender 3D (2.81 and higher)
* [DragonFF](https://github.com/Parik27/DragonFF)
