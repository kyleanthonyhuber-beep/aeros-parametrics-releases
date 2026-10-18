# Aeros Parametrics 0.3.4

Aeros Parametrics for Windows 0.3.4 (matches Android 0.21.2)

- All the import and export options are now easy to reach. Version 0.3.3 already had them in the File tab, but on a Surface-size screen only the first 8 or so File buttons fit. Touch, pen and mouse drags couldn't scroll the row, so Import STEP, the Export buttons, Share and the rest were stuck off screen. Now each one is in the same place as on Android and works with the normal Windows Open/Save dialogs, which start in Documents. Your files stay on your PC.
  - Part window, File tab: Import STEP (it asks whether to open an assembly STEP as an assembly or as one body, and offers to switch units, like Android), Export STEP, Export STEP to app storage, Export STL, Export OBJ, Export flat pattern DXF (saves straight away), Share (STEP, STL or project), Open, Save, Save as, Save in app storage, Open from app storage, Versions, Debug log (now with Share).
  - Assembly window: File > Export STEP and Import STEP assembly. Analysis > Parts list now shows the list with masses and has Export CSV, like Android.
  - Drawing window, Export tab: PDF and DXF save to the exports folder first, then let you Save a copy, Share or press OK, as on Android.
  - Design table: CSV export and import. Optimised shape STL. Shortcuts: Export and Import now really write and read a file.
- Slide through the tabs and tool rows like on Android, with a finger swipe or flick, the pen, a mouse drag, the mouse wheel, Shift+wheel or a trackpad. Dragging never presses the button under your finger, and a quick tap still works.
- Each tab has the same buttons as Android, in the same order, with the same labels and icons, and no desktop-only extras.
- How it's tested: every tab is now checked in the app as it is actually drawn on screen, at 1440×960 and 1280×800, including that every button can be reached by sliding the row. On each build, the installed app goes through every tab using real mouse, wheel and touch input. Every import and export is tested with real files through the CAD kernel.
- Android is unchanged. Still fully offline.

Downloads: x64 for Intel/AMD PCs, arm64 for Snapdragon (Windows on Arm) PCs. The installer is unsigned, so Windows SmartScreen may warn you: click More info > Run anyway.

| Windows | MSI | SHA-256 |
|---|---|---|
| x64 | [AerosParametrics-0.3.4-x64.msi](https://raw.githubusercontent.com/kyleanthonyhuber-beep/aeros-parametrics-releases/releases/AerosParametrics-0.3.4-x64.msi) | `84713200be30beb8791abe7f5576258040d09563dba634a31c1656106d050a87` |
| arm64 | [AerosParametrics-0.3.4-arm64.msi](https://raw.githubusercontent.com/kyleanthonyhuber-beep/aeros-parametrics-releases/releases/AerosParametrics-0.3.4-arm64.msi) | `dd731ebb91a0005ffe81c66bf35c74c951525889ee0379aa980f39eaa21821a1` |

Snapdragon / Windows on ARM: use the arm64 MSI. The 3D view needs OpenGL 3.3; on Adreno install Microsoft's free "OpenCL, OpenGL, and Vulkan Compatibility Pack" from the Microsoft Store.
