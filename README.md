# Mixed Reality Ball Generator

**Mixed Reality Ball Generator** is an immersive mixed reality game where players use hand controllers to generate and launch virtual balls in a 3D space, interacting with the environment in real-time.

## Features
- Generate and launch virtual balls using hand controllers.
- Interactive 3D environment where balls move based on controller input.
- Real-time sound effects and physics interactions.

## Controls
- **Right Controller (Secondary Index Trigger / B Key)**: Generate and launch a ball with the right hand.
- **Left Controller (Primary Index Trigger / B Key)**: Generate and launch a ball with the left hand.
- **Erasers**: Use the left and right triggers to activate erasers that can delete generated objects.

### Script Descriptions:
- **SelfDestroy.cs**: Destroys objects after 40 seconds to avoid clutter in the game scene.
- **GenerateObjectR.cs**: Generates and launches balls from the right hand controller.
- **GenerateObjectL.cs**: Generates and launches balls from the left hand controller.
- **AppManagerScript.cs**: Handles player input for generating objects, scaling, and triggering erasers.
- **EraseMeScript.cs**: Destroys objects when they come into contact with an eraser.

## Installation
1. Clone or download this repository to your local machine.
2. Open the project in Unity (version 2020.3 or later).
3. Connect your mixed reality device (e.g., Oculus Rift, HTC Vive, etc.).
4. Run the scene and follow the in-game instructions.

## Requirements
- Unity 2020.3 or later.
- Mixed Reality headset (e.g., Oculus Rift, HTC Vive, etc.).
- Basic knowledge of Unity and Mixed Reality development.
