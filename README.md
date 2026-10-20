# Aeros Parametrics 0.4.2

Aeros Parametrics for Windows 0.4.2 (matches Android 0.22.2)

- Sketch dimension labels and relation glyphs are no longer drawn beneath the feature tree, Properties or the toolbars: a label that would be covered moves into the visible part of the view, as on Android. The plain 3D view still shows none.
- Screen readers: the Dimension, Linear, Angular, Radius and Diameter buttons read the same longer descriptions as Android; the feature tree's minimize button is a full 48 dp target.
- Camera clip planes cover the grid around the target (Android 0.21.3 fix): an empty part no longer cuts the view in half.
- Help: Fillet/Chamfer is Ctrl+6 (was shown as Ctrl+4), Surfaces Ctrl+7, Sheet Metal Ctrl+8.
- Tested on a real Surface Pro (Snapdragon X Elite, Adreno X1-85, 200 %): installed, CAD kernel loaded, viewport check passed, labels beside (not under) the panels in sketch edit and absent in 3D.
- Still fully offline.

Downloads: x64 for Intel/AMD PCs, arm64 for Snapdragon (Windows on Arm) PCs. The installer is unsigned, so Windows SmartScreen may warn you: click More info > Run anyway.

| Windows | MSI | SHA-256 |
|---|---|---|
| x64 | [AerosParametrics-0.4.2-x64.msi](https://raw.githubusercontent.com/kyleanthonyhuber-beep/aeros-parametrics-releases/releases/AerosParametrics-0.4.2-x64.msi) | `74830647fc24adfebaba91433674d876b4b165de23191702d36fd24d8f6f8380` |
| arm64 | [AerosParametrics-0.4.2-arm64.msi](https://raw.githubusercontent.com/kyleanthonyhuber-beep/aeros-parametrics-releases/releases/AerosParametrics-0.4.2-arm64.msi) | `eca2fea638f179a8110dccb3a9d89e507782ecc1dfa60056945e8c3841e001bf` |

Snapdragon / Windows on ARM: use the arm64 MSI. The 3D view needs OpenGL 3.3; on Adreno install Microsoft's free "OpenCL, OpenGL, and Vulkan Compatibility Pack" from the Microsoft Store.
