# Store Sample Project

A sample project for [ezEngine](https://github.com/ezEngine/ezEngine) that demonstrates the use of a large number of high quality assets.

![Thumbnail](Thumbnail.jpg)

* The 'Main' scene demonstrates the use of many assets.
* The 'ObjectZoo' scene is used to inspect all available assets.
* Some prefabs use random object placement to add variaty.
* When 'playing' you can only walk around and pick small objects up with the 'E' key, there is currently no gameplay in this sample.
* See the 'SimplePlayer' prefab and visual script as an example how to make a very basic player controller.
* The used assets were made for offline renderers and thus have polygon counts that are way beyond what would be used in a real-time application. EZ has built-in mesh simplification in the [mesh asset](https://ezengine.net/pages/docs/graphics/meshes/mesh-asset.html). The sample uses this feature to significantly reduce the triangle count.
* It also uses [fill lights](https://ezengine.net/pages/docs/graphics/lighting/fill-light-component.html) and dynamic lights with shadow fading, to create decent indoor lighting while maintaining high rendering performance. Note that it also disables shadow casting on floor and ceiling geometry, to not waste performance for things that cannot cast a shadow onto anything.
* The scene is set up to use [occlusion culling](https://ezengine.net/pages/docs/performance/occlusion-culling.html) to great effect. The walls and some larger pieces of furniture are setup as [occluders](https://ezengine.net/pages/docs/graphics/occluder-component.html).
* There is also some clever reuse of assets, by scaling them such that they appear very different, to increase the percieved object variety.

## Assets

All assets are either under CC0 license or a similar permissive license that allows redistribution.

Assets are provided by:

* https://polyhaven.com
* https://www.sharetextures.com
* https://free3d.com
* https://kenney.nl
* https://freesound.org
* https://sonniss.com
