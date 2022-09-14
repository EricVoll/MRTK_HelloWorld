# Mixed Reality Unity HelloWorld application

This repo contains a minimum Unity application you can clone and use as a starting point for your Mixed Reality project. The project is setup to build for Microsoft's HoloLens 2.
It uses MRTK v3 for its UX. The sample scene is almost empty (on purpose) and only demos how to interact with a hologram by using MRTK's interaction scripts. 

## Steps to re-create the project
If you want to start from a completely empty Unity project, you can follow this tutorial here, which gets your very close to this HelloWorld application already.
1. [Setting up a Unity project with MRTK v3](https://docs.microsoft.com/en-us/windows/mixed-reality/mrtk-unity/mrtk3-overview/setup)
1. Add a plane and cupe to the scene.
1. Add the "[ObjectManipulator](https://docs.microsoft.com/en-us/windows/mixed-reality/mrtk-unity/mrtk3-spatialmanipulation/packages/spatialmanipulation/object-manipulator)" and "[BoundsControl](https://docs.microsoft.com/en-us/windows/mixed-reality/mrtk-unity/mrtk3-spatialmanipulation/packages/spatialmanipulation/bounds-control)" scripts/behaviors to the Cube. In the "BoundsControl" script, edit the VisualPrefab to use the "Handle occlusion style" prefab.

That's it already! Happy hacking!
