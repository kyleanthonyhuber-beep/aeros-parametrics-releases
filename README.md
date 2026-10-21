# Aeros Parametrics 0.4.4

Aeros Parametrics for Windows 0.4.4 (matches Android 0.22.4)

- Clicking the active tool's button again (for example Line) turns that tool off and switches to Select, and the Select button shows as selected. Esc does the same. Android uses the same shared rule.
- Sketch lines are now white instead of green. The green was the 3D-sketch colour, which Windows used for every sketch line; it never meant "fully constrained". It became very visible once 0.4.3 drew lines thicker. Selection (yellow) and hover (light blue) highlights stay distinct. Constraint state still shows through the point colours (blue = free, white = fixed) and the status text. Problem lines stay red.
- Still fully offline.

Downloads: x64 for Intel/AMD PCs, arm64 for Snapdragon (Windows on Arm) PCs. The installer is unsigned, so Windows SmartScreen may warn you: click More info > Run anyway.

| Windows | MSI | SHA-256 |
|---|---|---|
| x64 | [AerosParametrics-0.4.4-x64.msi](https://raw.githubusercontent.com/kyleanthonyhuber-beep/aeros-parametrics-releases/releases/AerosParametrics-0.4.4-x64.msi) | `83e90dfc453072a1210a12e077e909f8f8593c4d6274d7826e59788973df8b76` |
| arm64 | [AerosParametrics-0.4.4-arm64.msi](https://raw.githubusercontent.com/kyleanthonyhuber-beep/aeros-parametrics-releases/releases/AerosParametrics-0.4.4-arm64.msi) | `8d62cde6c158fd72105f51ca34e04a2131eb4c0ccfd7bd2f5f3154cd38df6282` |

Snapdragon / Windows on ARM: use the arm64 MSI. The 3D view needs OpenGL 3.3; on Adreno install Microsoft's free "OpenCL, OpenGL, and Vulkan Compatibility Pack" from the Microsoft Store.
