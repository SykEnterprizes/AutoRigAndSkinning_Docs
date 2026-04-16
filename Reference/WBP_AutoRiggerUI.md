# Auto-Rigging and Skinning Tools within the Sky Mesh Surgery Toolkit Plugin (UE5)

## Overview

An **editor-only Unreal Engine 5 tool** for **Auto-Rigging and Skin Weighting Static Meshes**
using standard UE4 and UE5 Metahuman skeletons.

Designed for small studios and solo developers to quickly prototype and iterate on character meshes — taking a static mesh from nothing to a rigged, skinned skeletal mesh in **around 20 minutes**.

---

## What This Does

- Allows a user to select any humanoid static mesh and rig it with a UE4 or UE5 format skeleton, including optional twist, corrective root, and IK bones
- Allows a user to easily add skin weights and iterate quickly to adjust deformation using visual feedback tools

> **Editor-time only by design** — no runtime mesh rigging or skinning is available.

---

## Key Features

- Full UE4 and UE5 skeletons including twist and IK bones
- Simple UE4 and UE5 skeleton variants for lightweight use cases
- Adjustable skin weights with user-friendly capsule handles and visual heatmap feedback
- Easy bone placement with full user control over marker positions
- Left-to-right mirroring — only work on one side and mirror across
- No runtime or editor-only dependencies shipped with your project
- Tested and developed against **UE 5.0.3+**

---

## Demo Videos

▶ YouTube link here

---

## Quick Start

1. Enable the plugin
2. Open **WBP_AutoRigger**
3. Select a source static mesh
4. Position the bone markers to match your mesh's anatomy
5. Click **Initialize** to compute the rig
6. Adjust the capsule handles using heatmap feedback for each bone
7. Click **Re-Skin** to apply and test the updated weights on the mesh
8. Save the output skeletal mesh asset

See the full [Rigging Quick Start Guide](GettingStarted/RiggingQuickStart.md) for detailed steps.

---

## Requirements

- Unreal Engine **5.0.3 and above**
- Editor-only usage

---

## Known Limitations

- Initialized meshes are close to prototype-ready but will typically need some weight adjustment in complex areas such as shoulders and neck
- Source mesh must be humanoid, or otherwise suitable for the UE4 or UE5 skeleton convention layout

---

## Status

Actively maintained — new skeleton features, UI improvements, and additional skeleton formats are planned for upcoming releases.
