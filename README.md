# Aeros Parametrics 0.4.0

Aeros Parametrics for Windows 0.4.0 (matches Android 0.22.0)

- New **Dimensions** tab right after 2D Sketch. It replaces the Constraints tab in the same place, so Ctrl+4, the remembered tab and your settings keep working.
- Inside a sketch the row starts with the dimension tools: **↔ Dimension** (smart, D), and new **⟷ Linear** (Shift+D), **∠ Angular** (Shift+A), **R Radius** (Shift+U) and **Ø Diameter** (Shift+O). After them come all the sketch relations: Coincident, Horizontal, Vertical, Parallel, Perpendicular, Tangent, Concentric, Equal, Symmetric, Collinear, Fix.
- The new dimensions work like the others: tool mode or selection first, they stay armed, and the value dialog opens after placing. A circle can now take a radius, and an arc a diameter.
- Command search, shortcuts (F1), help and the user guide are updated. Same change as Android 0.22.0, button for button.
- Tested on a real Surface Pro (Snapdragon X Elite, Adreno X1-85, 2880×1920 at 200 %): installed over 0.3.5, the CAD kernel loaded, the 3D view is drawn edge to edge, maximized and windowed.
- Still fully offline.

Downloads: x64 for Intel/AMD PCs, arm64 for Snapdragon (Windows on Arm) PCs. The installer is unsigned, so Windows SmartScreen may warn you: click More info > Run anyway.

| Windows | MSI | SHA-256 |
|---|---|---|
| x64 | [AerosParametrics-0.4.0-x64.msi](https://raw.githubusercontent.com/kyleanthonyhuber-beep/aeros-parametrics-releases/releases/AerosParametrics-0.4.0-x64.msi) | `0144c27b5341e5ed91192b62094cc89a499bef9a22ea8451b6c48f0529c6a42e` |
| arm64 | [AerosParametrics-0.4.0-arm64.msi](https://raw.githubusercontent.com/kyleanthonyhuber-beep/aeros-parametrics-releases/releases/AerosParametrics-0.4.0-arm64.msi) | `144798b6e7a544ef5f1000ca4450af5d5064246e83e4689f594efc1feccddeda` |

Snapdragon / Windows on ARM: use the arm64 MSI. The 3D view needs OpenGL 3.3; on Adreno install Microsoft's free "OpenCL, OpenGL, and Vulkan Compatibility Pack" from the Microsoft Store.
