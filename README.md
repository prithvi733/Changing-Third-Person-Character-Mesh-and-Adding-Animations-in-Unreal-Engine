# Changing-Third-Person-Character-Mesh-and-Adding-Animations-in-Unreal-Engine
# Aim
To replace the default third person character mesh with a custom skeletal mesh and apply new animations using an animation blueprint.

# Procedure:
1.Import New Character Mesh and Animations:
.In the *Content Browser, import a new *Skeletal Mesh along with its Animations (FBX files).
.Ensure the mesh is rigged correctly (ideally to the UE4 Mannequin Skeleton or compatible with it).

2.Replace Character Mesh:
.Open the ThirdPersonCharacter Blueprint (usually found in ThirdPersonBP/Blueprints).
.Select the Mesh component.
.In the *Details Panel, change the *Skeletal Mesh to the newly imported mesh.

3.Set Animation Blueprint:
.If available, assign a matching Animation Blueprint in the Details Panel under the Animation section.
.If not available, create one:
  *Right-click in the Content Browser → Animation → Animation Blueprint.
  *Choose the correct skeleton.
  *In the AnimGraph, set up state machines or direct animation nodes.
  *Compile and save.

  4.Preview and Test:
     .Place the character in the level.
     .Press Play to test idle, walk, and run animations based on character movement.

 # Output:

 ![image](https://github.com/user-attachments/assets/c51d7a31-19c8-4178-b97a-f9b7c97db434)

 ![image](https://github.com/user-attachments/assets/f116d04d-4cab-4523-9fc0-b12c9016bb48)

![image](https://github.com/user-attachments/assets/563954f0-6f16-4fa7-8de0-e8bbd34aeab9)

# Result:

The default Third Person Character was successfully replaced with a custom skeletal mesh, and animations were applied using an Animation Blueprint. The character now visually reflects new assets and performs the desired movement animations.

  

