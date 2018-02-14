# CS 4331-001 - Virtual Reality Project 1
## Due: February 20, 2018

### Contributors
 - Individual project; All work was completed by Simon Woldemichael.

### Work Distribution
 - Individual project

### Grade Requirements
 - For a C
   - [x] Customize your dream house with your own style of floor and ceiling
   - [x] Have at least 10 models at appropriate locations
   - [x] Have appropriate lighting
 - For a B
   - [x] Add an additional 5 unique models
   - [x] Give the use control over the lighting (light switch within the scene)
   - [x] Be able to navigate around the space
 - For an A
   - [x] Interact with certain objects (Clickable sound player and box that spawns other boxes)
	
### Planned timeline and sources as to how everything was achieved
1) Add a skybox.
   - [Example 1](https://aframe.io/aframe/examples/test/shaders/)
   
2) Add home frame with outer walls that cannot be walked through (maybe a cool shader too)
   - [Preventing walking through walls example](https://webvr.donmccurdy.com/walls/)

3) Add a ground plane with a realistic texture
   - [Example 1](https://aframe.io/examples/showcase/hello-metaverse/)
   - The ground plane also holds up the entire scene given there is -10 m/s gravity in the scene
   
4) Add 1 main room and a surrounding area outside of the main room

5) Add 15 models to the scene
   - For simplicity, use .gltf format models (sources below)
   - [If needed, compress the number of faces on all of them in MeshLab](https://www.shapeways.com/tutorials/polygon_reduction_with_meshlab)
   - *All* models should be below 800-900KB for mobile space optimization/efficiency
  
6) Add an animation to a model to make it a dynamic object
   - [Example 1](https://blog.prototypr.io/learning-a-frame-how-to-do-animations-2aac1ae461da)
   - [Example 2](https://aframe.io/docs/0.7.0/introduction/models.html)

7) Add a water 'shader' to make up a swimming pool
   - [Example 1](https://webvr.donmccurdy.com/water/)

8) Remove default lighting to give the user control over lighting
   - [Example 1](https://aframe.io/docs/0.7.0/introduction/javascript-events-dom-apis.html)
   - This is achieved by following [very basic DOM concepts](https://aframe.io/docs/0.7.0/introduction/javascript-events-dom-apis.html)
   - When the user clicks on a 'light switch', the lighting within the room will to and from grey and white

9) Add a music player or radio of some sort and allow the user to stop and play the song
   - [Resonant bodies play positional sound (really cool)](https://github.com/etiennepinchon/aframe-resonance)
   - Stopping and playing the radio is achieved using the same concepts applied to control lighting

10) Helpful sources:
    - https://github.com/donmccurdy/aframe-extras/issues/149
    - https://stackoverflow.com/questions/42087566/add-speed-to-wasd-controls-for-a-frame
    - https://stackoverflow.com/questions/41669122/how-do-i-copy-the-position-and-rotation-of-a-camera-child-a-frame-entity-to-use

### External model sources
  - Radio: https://sketchfab.com/models/e7172544d7984d3b8b7ac0cc6c9ae693
  - Table: https://sketchfab.com/models/28e73c5dd9674b349a0c7ba06fb34e1c
  - Phone: https://sketchfab.com/models/d77a5f2004004822b527edb8090fcbcf
  - Dog:  https://sketchfab.com/models/335f2250195c407bac91695fbdd193e1
  - Robot: https://sketchfab.com/models/331bc62673a9416591c0bf6b186caa8c
  - Car: https://sketchfab.com/models/e6af23e051644eaabba1299709aa6f2b
  - Couch: https://sketchfab.com/models/0bbeae4fe59b4e44bed8d06f5cb415bf
  - CRT TV: https://sketchfab.com/models/5ab87913300f474a96b218b10c9ab3d4
  - GameCube: https://sketchfab.com/models/ff244730d22e4581a3f505201e63925e
  - Amazon Echo: https://sketchfab.com/models/d09319ec6c8245f2bc7f20d96a4f328a
  - Tree: https://sketchfab.com/models/7016d1d32fe748f0a8b3f5eb39374bc4
  - Pool table: https://sketchfab.com/models/625c012402074e91a1a534b771920a17
  - Computer monitor: https://sketchfab.com/models/1cfebc1b09a54c0e96d87b7179237285
  - Bed: https://sketchfab.com/models/86d5c8b1addf4f138d8f0c2cf06e9ba0

### Video demonstration
   - (Video embed here :soon:)