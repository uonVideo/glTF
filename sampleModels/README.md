Each sample model is provided in the following formats:
* glTF (.gltf) with separate resources: .bin (geometry, animation, skins), .glsl (shaders), and image files
* glTF (.gltf) with embedded resources
* Binary glTF (.glb) using the [KHR_binary_glTF](https://github.com/KhronosGroup/glTF/blob/master/extensions/Khronos/KHR_binary_glTF/README.md) extension
* glTF (.gltf) using the [KHR_binary_glTF](https://github.com/KhronosGroup/glTF/blob/master/extensions/Khronos/KHR_materials_common/README.md) extension
* Original COLLADA (.dae)

See the `README.txt` in each model's directory for usage restrictions.

| Model                                  | Screenshot | Description|
|----------------------------------------|------------|------------|
| [box](box)                             | ![](box/screenshot/screenshot.png)               | One mesh and one material. Start with this. |
| [boxWithoutIndices](boxWithoutIndices) | ![](boxWithoutIndices/screenshot/screenshot.png) | Box without indices for testing the `drawArrays` path. |
| [boxTextured](boxTextured)             | ![](boxTextured/screenshot/screenshot.png)       | Box with one texture. Start with this to test textures. |
| [boxSemantics](boxSemantics)           | ![](boxSemantics/screenshot/screenshot.png)      | Includes extra uniforms to test all uniform semantics. |
| [duck](duck)                           | ![](duck/screenshot/screenshot.png)              | The COLLADA duck. One texture. |
| [boxAnimated](boxAnimated)             | ![](boxAnimated/screenshot/screenshot.png)       | Rotation and Translation Animations. Start with this to test animations. |
| [CesiumMilkTruck](CesiumMilkTruck)     | ![](CesiumMilkTruck/screenshot/screenshot.png)   | Textured. Multiple nodes/meshes. Animations. |
| [RiggedSimple](RiggedSimple)           | ![](RiggedSimple/screenshot/screenshot.png)      | Animations. Skins. Start with this to test skinning. |
| [RiggedFigure](RiggedFigure)           | ![](RiggedFigure/screenshot/screenshot.png)      | Animations. Skins. |
| [CesiumMan](CesiumMan)                 | ![](CesiumMan/screenshot/screenshot.png)         | Textured. Animations. Skins. |
| [monster](monster)                     | ![](monster/screenshot/screenshot.png)           | Textured. Animations. Skins. |
| [brainsteam](brainsteam)               | ![](brainsteam/screenshot/screenshot.png)        | Animations. Skins. |