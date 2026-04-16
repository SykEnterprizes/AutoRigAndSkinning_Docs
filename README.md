<<<<<<< Updated upstream
# Auto-Rigging and Skinning Tools withing the Syk Mesh Surgery Toolkit plugin (UE5)

## Overview
An **editor-only Unreal Engine 5 tool** for **Auto-Rigging and Skinweighting Static Meshes**
using standard UE4 and UE5 Metahuman skeletons.
=======
# Auto-Rigging and Skinning Tools within the Sky Mesh Surgery Toolkit Plugin (UE5)

## Overview

An **editor-only Unreal Engine 5 tool** for **Auto-Rigging and Skin Weighting Static Meshes**
using standard UE4 and UE5 Metahuman skeletons.

Designed for small studios and solo developers to quickly prototype and iterate on character meshes — taking a static mesh from nothing to a rigged, skinned skeletal mesh in **around 20 minutes**.
>>>>>>> Stashed changes

Designed for Small studios and Solo developers to quickly prototype and iterate on character
meshes
---

## What This Does
<<<<<<< Updated upstream
- Allows a User to select any mesh and Rig it with a basic skeleton in the UE4 or UE5 format
  or have it add the extra twist, corrective roots and ik bones
- Allows a User to easily add skinweights and iterate quickly to adjust deformation

> **Editor-time only by design** — no runtime mesh Rigging or Skinning available.
=======

- Allows a user to select any humanoid static mesh and rig it with a UE4 or UE5 format skeleton, including optional twist, corrective root, and IK bones
- Allows a user to easily add skin weights and iterate quickly to adjust deformation using visual feedback tools

> **Editor-time only by design** — no runtime mesh rigging or skinning is available.
>>>>>>> Stashed changes

---

## Key Features
<<<<<<< Updated upstream
- Full UE4 and UE5 skeletons including twist and ik
- Simple UE4 and UE5 skeletons 
- Adjustable skinweights with user friendly capsules and visual heatmap feedback
- Easy placement for bones, User has full control
- Mirroring so User only needs to work on one side
- No runtime editor-only dependencies
- Process of Rigging and Skinning reduced to ~20 mins for strong results
=======

- Full UE4 and UE5 skeletons including twist and IK bones
- Simple UE4 and UE5 skeleton variants for lightweight use cases
- Adjustable skin weights with user-friendly capsule handles and visual heatmap feedback
- Easy bone placement with full user control over marker positions
- Left-to-right mirroring — only work on one side and mirror across
- No runtime or editor-only dependencies shipped with your project
>>>>>>> Stashed changes
- Tested and developed against **UE 5.0.3+**

---

## Demo Videos

▶ YouTube link here

---

## Quick Start

1. Enable the plugin
<<<<<<< Updated upstream
2. Open the **WBP_AutoRigger**
3. Select a source Static Mesh
4. Set bone markups to desired positions
5. Initialize the mesh
6. Adjust the capsules using heatmap feedback for eaech bone
7. Hit Reskin to finalize and test the weights on the mesh 
=======
2. Open **WBP_AutoRigger**
3. Select a source static mesh
4. Position the bone markers to match your mesh's anatomy
5. Click **Initialize** to compute the rig
6. Adjust the capsule handles using heatmap feedback for each bone
7. Click **Re-Skin** to apply and test the updated weights on the mesh
8. Save the output skeletal mesh asset

See the full [Rigging Quick Start Guide](GettingStarted/RiggingQuickStart.md) for detailed steps.
>>>>>>> Stashed changes

---

## Requirements

- Unreal Engine **5.0.3 and above**
- Editor-only usage

---

## Known Limitations
<<<<<<< Updated upstream
- Initialized meshes are close to prototype ready, but will always need adjustments in some areas
- Source mesh must be Humanoid, or suitable to use the UE4 or UE5 skeleton convetion layout
=======

- Initialized meshes are close to prototype-ready but will typically need some weight adjustment in complex areas such as shoulders and neck
- Source mesh must be humanoid, or otherwise suitable for the UE4 or UE5 skeleton convention layout
>>>>>>> Stashed changes

---

## Status
<<<<<<< Updated upstream
This plugin is under active development.
APIs, UI, and Skeleton features will improve over the next few iterationss .
=======

Actively maintained — new skeleton features, UI improvements, and additional skeleton formats are planned for upcoming releases.
>>>>>>> Stashed changes
