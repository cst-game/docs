---
tags:
  - ClientObject
---
> [!note]
> This is not featured in the tower kit currently. Sit tight!

Changes the speed or jump power of a player.
# Resetting Properties
The `Reset` attribute resets your speed to the default walk speed of 16 and jump power of 50. It resets all stats.
## Resetting Single Stat
To reset a single stat, `AffectsSpeed` or `AffectsJump` attribute must be set to true for what you want to reset and change it to the default.
# Config
- `AffectsJump`: Decides if the modifier will affect the jump power of a player. Default is `false`
- `AffectsSpeed`: Decides if the modifier will affect the walk speed of a player. Default is `true`
- `JumpPower`: The jump power applied to a player if `AffectsJump` is true. Default is `50`
- `WalkSpeed`: The walk speed applied to a player if `AffectsSpeed` is true. Default is `16`
- `FadeDuration`: The length of the tween that changes the player's settings. Default is `3`
- `Duration`: The amount of time that the effect lasts. If it is less than or equal to `0`, the effect is infinite. Default is `0`
- `Reset`: Property that forces the walk speed and jump power of a player to reset to it's original properties. All other properties are ignored if this is set to true. Default is `false`
# Tags
- `PlayerModifier`