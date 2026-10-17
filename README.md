# Aeros Parametrics 0.3.3

Aeros Parametrics for Windows 0.3.3 (matches Android 0.21.2)

- Minimizable feature tree: the ▾ button in the Feature tree header shrinks the tree to its title so the viewport gets the space; ▸ brings it back. Works with mouse, touch and pen, and the app remembers the choice next time it starts. Same as Android 0.21.2.
- Toolbar tabs checked against Android: every tab in the part, assembly and drawing windows has the same buttons, in the same order, with the same labels and icons as Android 0.21.2. A new automated test compares the two, so they can't drift apart. Nothing needed changing. File keeps Units… and Settings… because Android's File tab has them too.
- Nothing else changed. Still fully offline.

Downloads: x64 for Intel/AMD PCs, arm64 for Snapdragon (Windows on Arm) PCs. The installer is unsigned, so Windows SmartScreen may warn you: click More info > Run anyway.

| Windows | MSI | SHA-256 |
|---|---|---|
| x64 | [AerosParametrics-0.3.3-x64.msi](https://raw.githubusercontent.com/kyleanthonyhuber-beep/aeros-parametrics-releases/releases/AerosParametrics-0.3.3-x64.msi) | `8539efb147baa7f9b42dd3f455b89bc0069d1f3375cdad78eb114e7cf8346606` |
| arm64 | [AerosParametrics-0.3.3-arm64.msi](https://raw.githubusercontent.com/kyleanthonyhuber-beep/aeros-parametrics-releases/releases/AerosParametrics-0.3.3-arm64.msi) | `81b4a3bcbc25a0dcfbfcb24435ce25d34913e4cd00d97a5a94aa48253764e7d4` |

Snapdragon / Windows on ARM: use the arm64 MSI. The 3D view needs OpenGL 3.3; on Adreno install Microsoft's free "OpenCL, OpenGL, and Vulkan Compatibility Pack" from the Microsoft Store.
