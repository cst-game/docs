---
tags:
---
A part that teleports a player from one part to another.
> [!note]
> The part has a distinction in the tower kit as `TeleportStart` and `TeleportEnd`.
> **TeleportStart**
> ![[teleportStart.png]]
> **TeleportEnd**
> ![[teleportEnd.png]]

# Config
- `Id`: The teleport id that links teleport parts together. Default is `102`
- `IsSafetyNet`: Denotes if a teleport part is a safety net. Does nothing but forces the part to be invisible. Default is `false`
- `IsStart`: Denotes if the teleport part is the entrance or exit of a link. When `IsStart` is set to true, players cannot come out of that specific teleport part. Default is `false`
- `Offset`: The offset added to the player when it exits a teleport. Default is `0, 10, 0`
- `Thunder`: Denotes if a teleport will make a thunder sound when exiting. Default is `false`
- `Type`: Decides what can be teleported. `Humanoid` is the only working option. Default is `Humanoid`
# Tags
- `TeleportPart`