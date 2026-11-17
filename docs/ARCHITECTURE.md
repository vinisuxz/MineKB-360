MineKB 360 - Architecture

1. Objective

Enable USB keyboard and mouse controls in Minecraft: Xbox 360 Edition.

2. Target Platform

- Console: Xbox 360 RGH/JTAG
- Game: Minecraft Xbox 360 Edition
- Title ID: 584111F7
- Input devices: USB HID keyboard and mouse

3. Technical Approach

The project will investigate adapting the existing X360Remap plugin.

X360Remap provides keyboard and mouse input mapping to Xbox 360 controller inputs.

Reference:
https://github.com/HB-Agadir/x360remap

4. Components

- USB HID input handling
- Keyboard-to-controller mapping
- Mouse-to-controller mapping
- Minecraft-specific control profile
- DashLaunch plugin integration

5. Planned Controls

- WASD: Movement
- Mouse: Camera
- SPACE: Jump
- SHIFT: Crouch
- E: Inventory
- ESC: Pause
- Left mouse button: Break blocks
- Right mouse button: Place blocks

6. Development Stages

1. Study the X360Remap source code and license.
2. Verify compatibility with the console and Minecraft.
3. Identify the real configuration format.
4. Adapt the Minecraft control profile.
5. Test keyboard input.
6. Test mouse input.
7. Validate the complete control layout.

7. Important Notes

- The JSON profile is currently a project draft, not a confirmed X360Remap configuration.
- Do not install unverified plugins.
- Keep a backup of the DashLaunch configuration.
- Do not load X360Remap alongside hiddriver360.
- Preserve GPL-3.0 license requirements when modifying or redistributing X360Remap.
