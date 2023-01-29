# WebGL04

In order to complete this task, various objectives must be achieved. One of which was rectifying the Blazor.Expansions.Canvas component, which was accomplished by adhering to the instructions provided in the tutorial. Additionally, we were required to incorporate the outcomes of prior assignments such as enabling the pawn to move using the W and S keys and incorporating shadows for the various objects in the scene.

In this task at hand, we are required to tackle a number of different objectives. One of which was rectifying the Blazor.Expansions.Canvas component, which was accomplished by utilizing the provided tutorial. Additionally, we incorporated the outcomes from previous activities, including the ability to move the pawn using the W and S keys, as well as incorporating shadows for the various objects in the scene.

The implementation of shadows was executed using a similar method as before. Specifically, a shader fragment was devised and compiled into a program specifically tailored for this purpose. 

In order to add textures to the elements in the demo, such as the ship, floor, and objects, we made modifications to the "texture" field in the level.json actor list. This simple change allowed us to apply textures to the different elements of the demo.

In order to accomplish the task of applying textures to the various elements of the demo, such as the ship, floor, and objects, all that was necessary was to adjust the "texture" field within the level.json actor list. Additionally, to ensure that the texture would repeat seamlessly, the prepareBuffers task within Game.razor.cs was modified to allow for tiling on any cube, including the floor.

(see image for final results)
