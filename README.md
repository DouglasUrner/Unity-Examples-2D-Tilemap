# Unity-Examples-2D-Tilemap

How to build a 2D world using Unity's Tilemap objects. The Tilemap engine was released in October of 217 in Unity 2017.2, tutorials and other reference materials that refer to earlier versions of Unity or that are dated before then are out of date with respect to the "state of the art." In Unity 2018.2 support for hexagonal tiles was added, and in Unity 2018.3 isometric 2D views got native support.

## Getting Started

1. Clone this repository.
1. Watch the 2nd and 3rd videos of the **Live Session: 2D World building w/ Tilemap & Cinemachine for 2D**.
1. Launch Unity.
1. Open the Penny Pixel project.
1. Try them out.

Items mentionoed in the tutorial videos, these are all included in the **2D Tilemap** [tutorial assets](), the links below will be helpful if you want to include them in other projects:

* [Unity 2D Extras][2d-extras] - be sure that you are choosing the right branch (version).
* [Cinemachine][]

## Key Points and Major Elements

* Grid
  - Parent of all Tilemaps (similar in concept to the UI Canvas)
  - Resolutions of the tiles and the grid need to match - otherwise you will have gaps (or overlaps).
    - Grid Cell Size: Cell size in Unity units.
    - Sprite Pixels per Unit: the number of pixels to span a unit.
* Tilemap  
  There can be multiple tilemaps (background, foreground, etc.).
  - Sort order (layers) on Tilemap renderer.
* Tile Palatte
* Tilemap Collider
* Working with sprite sheets:
  - Importing
  - Slicing
  - Scaling (pixels per unit)
 
## Sources:

The "offical word" from Unity:

* [2D Tilemap Asset Workflow: From Image to Level](https://blogs.unity3d.com/2018/01/25/2d-tilemap-asset-workflow-from-image-to-level/)
* **Live Session: 2D World building w/ Tilemap & Cinemachine for 2D**  
  A seres of eight video tutorials for beginners which builds on the blog post above:
  - 1: [Intro to 2D World building w/ Tilemap](https://unity3d.com/learn/tutorials/topics/2d-game-creation/intro-2d-world-building-w-tilemap) 2:34
  - 2: [Core Tilemap Concepts](https://unity3d.com/learn/tutorials/topics/2d-game-creation/core-tilemap-concepts?playlist=17093) 11:33
  - 3: [Tilemap Collider 2D and Composite Collider 2D](https://unity3d.com/learn/tutorials/topics/2d-game-creation/tilemap-collider-2d-and-composite-collider-2d?playlist=17093) 3:59
  - 4: [Confined Follow Camera with Cinemachine For 2D](https://unity3d.com/learn/tutorials/topics/2d-game-creation/confined-follow-camera-cinemachine-2d?playlist=17093) 9:08 - make the camera follow the player using [Cinemachine]().  
  - 5: [Using Rule Tiles With Tilemap](https://unity3d.com/learn/tutorials/topics/2d-game-creation/using-rule-tiles-tilemap?playlist=17093) 7:08
  - 6: [Random and Animated Tilemap Tiles](https://unity3d.com/learn/tutorials/topics/2d-game-creation/random-and-animated-tilemap-tiles?playlist=17093) 13:38
  - 7: [Custom Tilemap Brush To Spawn Prefabs](https://unity3d.com/learn/tutorials/topics/2d-game-creation/custom-tilemap-brush-spawn-prefabs?playlist=17093) 4:10
  - 8: [Questions and Answers for 2D Worldbuilding](https://unity3d.com/learn/tutorials/topics/2d-game-creation/questions-and-answers-2d-worldbuilding?playlist=17093) 7:22
  
  Useful assets and tools:
  - [Tutorial Assets][ta] Contains everything below.
  - [2D Extras][2d-extras] - clone from GitHub, includes Rule Tile support.
  - Cinemachine - intall with Unity Package Manager (Window > Package Manager).
  
* [Isometric 2D Environments with Tilemap](https://blogs.unity3d.com/2019/03/18/isometric-2d-environments-with-tilemap/) - Unity 2018.3

[ta]: http://bit.ly/tilemaplive
[2d-extras]: https://github.com/Unity-Technologies/2d-extras
[cinemachine]: 

Tutorial materials from third parties:

* [Introduction to the New Unity 2D Tilemap System](https://www.raywenderlich.com/23-introduction-to-the-new-unity-2d-tilemap-system)
* [Mastering Unity’s New Tilemap Editor: Building 2D Levels](https://gamedevacademy.org/mastering-unitys-new-tilemap-editor-building-2d-levels/)
* [How to Build a Complete 2D Platformer in Unity](https://gamedevacademy.org/how-to-build-a-complete-2d-platformer-in-unity/)
* [Tile Map Tutorial](https://www.2dtoolkit.com/doc/2.5/tilemap/tutorial.html)

### 2D Game Kit

* [Painting a Level](https://unity3d.com/learn/tutorials/projects/2d-game-kit/painting-level)

### Dungeon Generation

* [Procedural dungeon generation methods and the role of Unity on them](https://bladecast.pro/unity-tutorial/dungeon-prcedural-generation-overview-unity-2018)
* [How to procedurally generate a dungeon using the BSP method on Unity](https://bladecast.pro/unity-tutorial/how-to-procedurally-generate-a-dungeon-bsp-method-unity-tilemap)

### Understanding the Underlying Concepts

A *long* series of tutorials from Catlike Coding on hexagonal tiles and isometric worlds. Really good for understanding the underlying principles.

* [Constructing a Fractal](https://catlikecoding.com/unity/tutorials/constructing-a-fractal/)
* [Procedural Grid](https://catlikecoding.com/unity/tutorials/procedural-grid/)
* [Hex Map 1](https://catlikecoding.com/unity/tutorials/hex-map/part-1/)

Converting a 2D game to an isometric view:

* [Unity 2D Tile-Based Isometric and Hexagonal 'Sokoban' Game](https://gamedevelopment.tutsplus.com/tutorials/unity-2d-tile-based-isometric-and-hexagonal-sokoban-game--cms-29715)

### Finding spritesheets

* Unity Asset Store
* OpenGameArt
