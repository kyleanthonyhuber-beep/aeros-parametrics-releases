# Aeros Parametrics 0.4.3

Aeros Parametrics for Windows 0.4.3 (matches Android 0.22.3)

- Enter completes the active command, the same as OK / ✓: it ends the current line or shape chain, finishes a sketch, completes an edge, face or surface pick, and presses OK in an open dialog. In a text field, Enter does that field's own submit, and a multi-line field keeps its new line.
- A clicked sketch line, arc, circle or point, part edge or face, assembly component, or drawing item stays highlighted until you deselect it. Hovering with the mouse or pen shows a lighter pre-highlight first. Android uses the same shared colours and rules.
- Selected and hovered edges and sketch items are now drawn thick enough to see on high-DPI screens. Before this, core OpenGL drew them 1 pixel wide.
- Tested on a real Surface Pro (Snapdragon X Elite, Adreno X1-85, 200 %): the installer works, the CAD kernel loads and the viewport check passes. Sketch and edge highlights are visible, and the Enter check passes (Enter ends the line chain, then finishes the sketch).
- Still fully offline.

Downloads: x64 for Intel/AMD PCs, arm64 for Snapdragon (Windows on Arm) PCs. The installer is unsigned, so Windows SmartScreen may warn you: click More info > Run anyway.

| Windows | MSI | SHA-256 |
|---|---|---|
| x64 | [AerosParametrics-0.4.3-x64.msi](https://raw.githubusercontent.com/kyleanthonyhuber-beep/aeros-parametrics-releases/releases/AerosParametrics-0.4.3-x64.msi) | `443cc1a4adb1b72b2cc989984972c5f58debad73a17159380c02b358b3d12faa` |
| arm64 | [AerosParametrics-0.4.3-arm64.msi](https://raw.githubusercontent.com/kyleanthonyhuber-beep/aeros-parametrics-releases/releases/AerosParametrics-0.4.3-arm64.msi) | `af913281d84a975b2ad320705b712f73e4430ec86d35f502f5fd0418494c7bfc` |

Snapdragon / Windows on ARM: use the arm64 MSI. The 3D view needs OpenGL 3.3; on Adreno install Microsoft's free "OpenCL, OpenGL, and Vulkan Compatibility Pack" from the Microsoft Store.
