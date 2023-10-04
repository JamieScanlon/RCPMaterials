# RCPMaterials
## Reality Composer Pro Dynamic Materials Library.
Reality Composer Pro has the ability to use a nodal shader graph to create dynamic procedural materials. 
The implementation is based on [MaterialX](https://materialx.org) but currently the application only exposes a basic set of nodes 
to work with and importing complex materials from programs like Houdini are not yet supported.

This `usd` file contains a number of primatives that can be used as building blocks to create your own
dynamic textures. It leverages the node graph capability of Reality Composer Pro to encapsulate basic units of funtionality into a 
single node that you can use with other nodes to create more complex materials

![Screenshot of a some of the primatives contained in the library.](Screenshot%201.png)

![Screenshot of one of the nodes in the editor.](Screenshot%202.png)

## Primatives
The following is a list of the Shader Graph nodes this library currently provides. This list is always growing!
### Shape Functions
1. Circle
2. Outline Circle (ring)
3. Rectangle
4. Rounded Rectange
5. Outline Rectangle
6. Rounded Outline Rectangle
7. Polygon

### Shape Modifiers
1. Annular (make an outlined shape)
2. Rounded (make a shape with rounded corners)
3. Tile

### General Purpose
1. Random (provides a random value given a seed)
2. Warp
3. Rays

## Apple Documentation

For more infomation on Shader graph see [Apple's Documentation](https://developer.apple.com/documentation/visionos/designing-realitykit-content-with-reality-composer-pro#Build-materials-in-Shader-Graph) for Reality Composer Pro

Development is ongoing and contributions are welcome.

MIT License.
