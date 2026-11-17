MineKB 360 - Configuration

Official X360Remap Configuration

The official plugin reads its configuration from:

"HDD:\X360RemapStudio\X360Remap.json"

Configuration Structure

- Each USB device is identified by its VID and PID.
- Keyboard mappings are stored in the "keys" array.
- Mouse button mappings are stored in the "buttons" array.
- Game-specific settings are stored in the "profiles" array.
- Each game profile uses a "titleId" field.

Minecraft Profile

- Game: Minecraft Xbox 360 Edition
- Title ID: "584111F7"
- Profile name: Minecraft

Important

The file "config/minecraft.json" in this repository is a planning draft. It is not directly loaded by X360Remap.

The final configuration must use the official X360Remap JSON schema and the actual VID/PID values of the connected USB devices.

Do not install or modify console plugins before compatibility checks.
