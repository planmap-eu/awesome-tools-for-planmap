# awesome-tools-for-planmap


## VR and presentation

To visualize 3D models (meshes) in the simplest way as possible we can use several tools, depending if we do need to *edit* the meshes or not.

### osgviewer

is the best tool one can use as simple visualizer, for presentations, education etc:

- Very simple but supports texturing and several stereo modes. See here for a complete guide: http://www.openscenegraph.org/index.php/documentation/user-guides/54-osgviewer.
- It is based on the OpenSceneGraph toolkit which is relevant for 3d data visualization in the domain of VR, and possibly to create ad hoc visualization tools. OSG It is a complex toolkit but it is worth the effort.
- to enable stereo with osgviewer call with the --stereo arg:
```
osgviewer mesh1.ply mesh2.ply --stereo
```
- it also support loading raster as elevations maps with the --dem option. as far as I got [to be checked]

#### installation

osgviewer comes with the openscenegraph toolkit. So to obtain it you should install the whole toolkit downloading the appropriate installer from their website f you are on windows . on mac first try with homebrew, on linux with your own package manager.


## point clouds processing and visualization
### verde

python based point cloud processing with gridding algorithms. scipy-like /pandas based interface

http://www.fatiando.org/verde/latest/


## seismic interpretation
### opendtect

see  https://dgbes.com/index.php/software#free to have an idea. the free version might be enough for our use.

https://github.com/OpendTect/OpendTect


