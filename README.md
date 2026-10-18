# Aeros Parametrics 0.3.5

Aeros Parametrics for Windows 0.3.5 (matches Android 0.21.2)

- Fixed: the 3D view no longer looks cut in half. In 0.3.4 a new or empty part showed the grid only in the top half of the window, with a hard line through the origin and blank background below it. The view's near clipping plane was placed just in front of the origin, because an empty part counts as 1 mm across. So everything closer to you than the origin was cut away: the near half of the grid and the axes. The viewport now keeps the whole visible grid, and the view is drawn edge to edge at every Windows scaling setting (100–250 %).
- The window always opens inside your screen (taking the taskbar into account), and stays inside it after a resize, maximize or restore, or after moving it to a monitor with different scaling.
- How it's tested:
  - A new test draws the part window with real OpenGL at 100, 150, 200 and 250 % scaling. It checks that the 3D image is exactly the viewport's size, that the grid reaches the bottom-left and bottom-right corners, and that the screen really shows the 3D image there, not the background behind it. This test failed on the 0.3.4 code and passes now.
  - The installed app was also run at 150 % and 175 % Windows scaling on x64 and Arm test machines: maximized, then restored to a smaller window, then maximized again. Each run took full-resolution screenshots and checked that the bottom half of the view is drawn and nothing is clipped off the window.
  - Tested on a real Surface Pro (Snapdragon X Elite, Adreno X1-85, 2880×1920 at 200 %): installed over 0.3.4, the CAD kernel loaded and the 3D view runs on the Adreno GPU, drawn edge to edge.
- Android is unchanged. Still fully offline.

Downloads: x64 for Intel/AMD PCs, arm64 for Snapdragon (Windows on Arm) PCs. The installer is unsigned, so Windows SmartScreen may warn you: click More info > Run anyway.

| Windows | MSI | SHA-256 |
|---|---|---|
| x64 | [AerosParametrics-0.3.5-x64.msi](https://raw.githubusercontent.com/kyleanthonyhuber-beep/aeros-parametrics-releases/releases/AerosParametrics-0.3.5-x64.msi) | `8354abea3e1bbcf6cc0ac24b40d350aad4ac219f6573f967b3b6f6b2bf7b6bf8` |
| arm64 | [AerosParametrics-0.3.5-arm64.msi](https://raw.githubusercontent.com/kyleanthonyhuber-beep/aeros-parametrics-releases/releases/AerosParametrics-0.3.5-arm64.msi) | `979993c1000c5a59eb7be72b4aa319945175a926434b047f7e1588482915da1d` |

Snapdragon / Windows on ARM: use the arm64 MSI. The 3D view needs OpenGL 3.3; on Adreno install Microsoft's free "OpenCL, OpenGL, and Vulkan Compatibility Pack" from the Microsoft Store.
