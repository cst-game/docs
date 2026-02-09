---
tags:
  - ClientObject
---
The `BalloonPart` attaches a balloon to a player or other character that moves them in a certain direction with a set velocity.
# Config
- `BalloonColor`: Sets the balloon's color. Default is `[0, 255, 127]`
- `DismountOnJump`: Disconnects the balloon attached to the local player if this is set on the balloon attached to them. Default is `true`
- `Duration`: The length of time before the balloon is automatically disconnected from a character. Setting it to `0` or lower never removes it from a character. Default is `5`
- `MoveDir`: The direction in which the `Velocity` is applied. Must be a unit vector. Default is `0, 1, 0`
  > [!tip]
  > `MoveDir` is automatically converted to a unit vector
- `RandomColor`: Decides if a random color is applied instead of `BalloonColor`. Default is `false`
- `RestrictPlayer`: Limits the activation to only characters with a player character. Default is `true`
- `RopeLength`: Length of the rope that attaches the player to the balloon. Default is `1.5`
- `Velocity`: The velocity that is applied to the balloon to make it move. It is applied in the direction of the `MoveDir`
# Tags
- `BalloonPart`