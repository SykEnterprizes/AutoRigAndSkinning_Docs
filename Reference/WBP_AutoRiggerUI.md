# Auto-Rigging and Skinning Tools within the Sky Mesh Surgery Toolkit Plugin (UE5)

## User Interface Overview

The AutoRigging Tool UI is intentionally divided into separate UI.
Controls are shown or hidden based on the selected mode to reduce clutter and improve clarity.

## Menu Mode Selector

At the top of the tool is the UI Choice selector.

- This determines which menu we will be viewing
  
Available Modes
---
- Rigging and Skinning Controls
- Save and Load
- Bone Visualizing

## Initiate

- Takes the input mesh and calculates approprate capsule radii for the skinning.  
- Generates CapsuleRigHandles based on those radii
- Provides the user a base Rigged and skinned mesh according to the build options and skinning settings

## ReSkin

- Takes the users changes to the CapsuleRigHandles and skinning settings, and ReSkins the current mesh

## Build Options

- Template changes between UE4 default skeleton and UE5 default skeleton
- Add Bones : True to add Stated bones - False to leave them out

## Mesh

- Choose a Static Mesh to use as an Input

## Skinning Options

- Blendzone Multiplier 
