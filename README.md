# Auto-Rigging and Skinning Tools withing the Syk Mesh Surgery Toolkit plugin (UE5)

## Overview
An **editor-only Unreal Engine 5 tool** for **Auto-Rigging and Skinweighting Static Meshes**
using standard UE4 and UE5 Metahuman skeletons.

Designed for Small studios and Solo developers to quickly prototype and iterate on character
meshes
---

## What This Does
- Allows a User to select any mesh and Rig it with a basic skeleton in the UE4 or UE5 format
  or have it add the extra twist, corrective roots and ik bones
- Allows a User to easily add skinweights and iterate quickly to adjust deformation

> **Editor-time only by design** — no runtime mesh Rigging or Skinning available.

---

## Key Features
- Full UE4 and UE5 skeletons including twist and ik
- Simple UE4 and UE5 skeletons 
- Adjustable skinweights with user friendly capsules and visual heatmap feedback
- Easy placement for bones, User has full control
- Mirroring so User only needs to work on one side
- No runtime editor-only dependencies
- Process of Rigging and Skinning reduced to ~20 mins for strong results
- Tested and developed against **UE 5.0.3+**

---

## Demo Videos
▶ YouTube link here

---

## Quick Start
1. Enable the plugin
2. Open the **WBP_AutoRigger**
3. Select a source Static Mesh
4. Set bone markups to desired positions
5. Initialize the mesh
6. Adjust the capsules using heatmap feedback for eaech bone
7. Hit Reskin to finalize and test the weights on the mesh 

---

## Requirements
- Unreal Engine **5.0.3**
- Editor-only usage

---

## Known Limitations
- Initialized meshes are close to prototype ready, but will always need adjustments in some areas
- Source mesh must be Humanoid, or suitable to use the UE4 or UE5 skeleton convetion layout

---

## Status
This plugin is under active development.
APIs, UI, and Skeleton features will improve over the next few iterationss .
