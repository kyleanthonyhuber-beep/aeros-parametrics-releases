# Aeros Parametrics 0.3.2

0.3.2 is the first public build with full Android v0.21.1 parity. 0.3.1 was tagged but never published, because its x64 MSI (100.99 MB) went over GitHub's 100 MB file limit. 0.3.2 has all of the 0.3.1 parity work plus the size fix: the bundled Java runtime no longer includes the jdk.localedata module, both MSIs are under 97 MB, and CI now enforces that limit. Dates and numbers are formatted with the built-in English/root locale data.

From 0.3.1: Every button from the Android v0.21.1 layout now does the real thing (0.3.0 showed "coming in 0.3.x" for about 25 of them).
- Part: Shell, Draft, Mirror, Pattern, Hole, Sweep, Loft, reference Plane / Axis / Point, Configurations and design table, 3D Sketch (lines, arcs, locks, typed points, 3D constraints), 3D constraints between faces/edges, Tangent edges, sketch Offset / Mirror / Project / Use face edges / Sketch plane…, Sketch on this plane, all nine surface tools, Edge flange, Hem, Sketched bend, Sheet defaults — with the Android dialogs, fields and defaults.
- Analysis: the Android Analyse (FEA), Optimise shape, Design for load and Load report dialogs; Export optimised shape, Hide analysis results.
- File: Versions… (the content each save replaces, newest 10), Share… (the file is written to the share folder and shown selected in Explorer — Windows has no share sheet; drag it into mail or chat), STEP / STL / OBJ export with the mesh dialog.
- Assembly: linked part files, sub-assemblies, Reload linked parts, Export / Import STEP assembly, Move…, Material…, Colour…, Configuration…, Use editor part, Open in editor, mate edit / flip / suppress / delete and value prompts.
- Drawing: model picker and single views, tap-to-place step, projected / section / detail views, scale, hidden lines, dimensions, notes, GD&T annotations, Sheet & title block, Drawing units, Configuration.
- Settings: custom background and model colour pickers. A loading card shows until the first part frame.

| Windows | MSI | SHA-256 |
|---|---|---|
| x64 | [AerosParametrics-0.3.2-x64.msi](https://raw.githubusercontent.com/kyleanthonyhuber-beep/aeros-parametrics-releases/releases/AerosParametrics-0.3.2-x64.msi) | `1d70739cbf44c139f5450efd76c5b8f81a71a17dff33ffedd799f3c8e70fca7e` |
| arm64 | [AerosParametrics-0.3.2-arm64.msi](https://raw.githubusercontent.com/kyleanthonyhuber-beep/aeros-parametrics-releases/releases/AerosParametrics-0.3.2-arm64.msi) | `a50464b9c5f419688b565fff5f895716ddac7f9fe0a5655267ffcd8cd01a44dd` |

Snapdragon / Windows on ARM: use the arm64 MSI. The 3D view needs OpenGL 3.3; on Adreno install Microsoft's free "OpenCL, OpenGL, and Vulkan Compatibility Pack" from the Microsoft Store.
