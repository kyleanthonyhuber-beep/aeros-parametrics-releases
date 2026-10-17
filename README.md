# Aeros Parametrics 0.2.2

Fixes 0.2.1 failing to launch.
- Fixed: mixed LWJGL versions (all LWJGL modules now 3.4.2) and the bundled Java runtime missing jdk.unsupported (sun.misc.Unsafe), which crashed startup.
- New: native Windows on ARM64 build (Snapdragon X / Adreno). Pick the arm64 MSI on ARM PCs; x64 is still provided.
- New: if OpenGL 3.3 is missing or too old, a dialog explains what to install ('OpenCL, OpenGL, and Vulkan Compatibility Pack' from the Microsoft Store on Windows on ARM) instead of crashing.
- New: startup log at %LOCALAPPDATA%\Aeros Parametrics\logs\aeros.log; startup errors are shown in a dialog.
- New: Aeros blue/green/gold app icon (installer, shortcuts, window).

| Windows | MSI | SHA-256 |
|---|---|---|
| x64 | [AerosParametrics-0.2.2-x64.msi](https://raw.githubusercontent.com/kyleanthonyhuber-beep/aeros-parametrics-releases/releases/AerosParametrics-0.2.2-x64.msi) | `a1dd9b4820830c453b256aaf6417a299e1f3a542dc5e9548f40461c2ab5cb147` |
| arm64 | [AerosParametrics-0.2.2-arm64.msi](https://raw.githubusercontent.com/kyleanthonyhuber-beep/aeros-parametrics-releases/releases/AerosParametrics-0.2.2-arm64.msi) | `f10f94f5df0c196c5c50cab937dbacf4cd83b163cf234f4a95185e09cb6b47b3` |

Snapdragon / Windows on ARM: use the arm64 MSI. The 3D view needs OpenGL 3.3; on Adreno install Microsoft's free "OpenCL, OpenGL, and Vulkan Compatibility Pack" from the Microsoft Store.
