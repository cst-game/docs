---
tags:
  - ClientObject
---
A part that changes the lighting settings locally when touched by the local player character.
# Config
- `Ambient`:  The lighting hue applied to areas that are occluded from the sky. Default is `[255, 255, 255]`
- `Brightness`: The intensity of the illumination in the place. Default is `0`
- `ClockTime`: A numerical representation (in hours) of the current time of day used by `Lighting`. Default is `0`
- `ColorShift_Bottom`: The hue represented in light reflected in the opposite surfaces to those facing the sun or moon. Default is `[255, 255, 255]`
- `ColorShift_Top`: The hue represented in light reflected from surfaces facing the sun or moon. Default is `[255, 255, 255]`
- `EnvironmentDiffuseScale`: Ambient light that is derived from the environment. Default is `0`
- `EnvironmentSpecularScale`: Specular light derived from environment. Default is `0`
- `ExposureCompensation`: This property determines the exposure compensation amount which applies a bias to the exposure level of the scene prior to the tonemap step. Default is `0`
- `FadeDuration`: The length of time it takes for the tween to be completed. Default is `3`
- `FogColor`: Color of the `Lighting` fog. Default is `[120, 120, 120]`
- `FogEnd`: Depth from the current camera that the fog will be fully opaque. Default is `100000`
- `FogStart`: Depth from the current camera that the fog will begin to show. Default is `0`
- `GeographicLatitude`: The geographic latitude, in degrees, of the scene, influencing the result of `Lighting` time on the position of the sun and moon. Default is `0`
- `OutdoorAmbient`: The lighting hue applied to outside areas. Default is `[255, 255, 255]`
- `Reset`: Property that forces the lighting to reset to it's original properties. All other properties are ignored if this is set to true. Default is `false`
# Tags
- `LightingChanger`