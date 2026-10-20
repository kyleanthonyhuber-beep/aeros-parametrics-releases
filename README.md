# Aeros Parametrics 0.4.1

Aeros Parametrics for Windows 0.4.1 (matches Android 0.22.1)

- Dimensions are now shown on screen while you edit a 2D sketch: each driving dimension gets a label (for example "60 mm") with a leader line, and sketch relations get small glyphs (H, V, ...). Click a dimension label to change its value, as on Android.
- In the plain 3D view the labels are hidden, so the model stays uncluttered.
- Tested on a real Surface Pro (Snapdragon X Elite, Adreno X1-85, 200 %): installed, CAD kernel loaded, 3D view edge to edge, dimension labels seen in sketch edit and absent in 3D.
- Still fully offline.

Downloads: x64 for Intel/AMD PCs, arm64 for Snapdragon (Windows on Arm) PCs. The installer is unsigned, so Windows SmartScreen may warn you: click More info > Run anyway.

| Windows | MSI | SHA-256 |
|---|---|---|
| x64 | [AerosParametrics-0.4.1-x64.msi](https://raw.githubusercontent.com/kyleanthonyhuber-beep/aeros-parametrics-releases/releases/AerosParametrics-0.4.1-x64.msi) | `e81d1fdc75bd6fe645026006d159cfcd6a3d1e73b08b7a0680e23ece804dd4af` |
| arm64 | [AerosParametrics-0.4.1-arm64.msi](https://raw.githubusercontent.com/kyleanthonyhuber-beep/aeros-parametrics-releases/releases/AerosParametrics-0.4.1-arm64.msi) | `d6fd7e9002f85e51149de326156a7853f4f04f248fe35ca6e16a21dd88a2aaaa` |

Snapdragon / Windows on ARM: use the arm64 MSI. The 3D view needs OpenGL 3.3; on Adreno install Microsoft's free "OpenCL, OpenGL, and Vulkan Compatibility Pack" from the Microsoft Store.
