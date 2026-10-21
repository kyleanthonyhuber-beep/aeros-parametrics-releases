# Aeros Parametrics 0.4.5

Aeros Parametrics for Windows 0.4.5 (matches Android 0.22.5)

- Inches and the ANSI drafting standard are now the default everywhere: new installs, new parts, the sample part, new drawings (ANSI B sheets, third-angle projection, "DIMENSIONS IN INCHES"), and every fallback when no units are known.
- Why mm still showed before: the sample part was built in millimetres, and new parts copied the units of the part that was open, so "40 mm" kept appearing even with Settings on Inches. New parts now follow Settings → Length unit.
- Updating: if you picked Millimetres in Settings yourself, that choice is kept. Every file keeps its own units, so a millimetre part still opens in millimetres.
- Measure: "Normal distance" now follows the part's units (it stayed in mm in inch parts).
- Dimension and Size dialogs now show the value in the part's units. Before, an inch part showed the millimetre number (e.g. "60") but read it back as inches, so pressing OK without typing turned 60 mm into 60 in. The feature tree shows fillet radii in the part's units, too.
- Still fully offline.

Downloads: x64 for Intel/AMD PCs, arm64 for Snapdragon (Windows on Arm) PCs. The installer is unsigned, so Windows SmartScreen may warn you: click More info > Run anyway.

| Windows | MSI | SHA-256 |
|---|---|---|
| x64 | [AerosParametrics-0.4.5-x64.msi](https://raw.githubusercontent.com/kyleanthonyhuber-beep/aeros-parametrics-releases/releases/AerosParametrics-0.4.5-x64.msi) | `6d95baad1f5c9f8b556d64ea877a0fe1054a1419a8546525f21590390f97c4c3` |
| arm64 | [AerosParametrics-0.4.5-arm64.msi](https://raw.githubusercontent.com/kyleanthonyhuber-beep/aeros-parametrics-releases/releases/AerosParametrics-0.4.5-arm64.msi) | `f853ad388f3e5c8a3074ead07309a1898b171b79350381706fd9fa95d1e64163` |

Snapdragon / Windows on ARM: use the arm64 MSI. The 3D view needs OpenGL 3.3; on Adreno install Microsoft's free "OpenCL, OpenGL, and Vulkan Compatibility Pack" from the Microsoft Store.
