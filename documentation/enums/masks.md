# masks

## Fields:

| Name                       |
| -------------------------- |
| mask_all                   |
| mask_solid                 |
| mask_playersolid           |
| mask_visible               |
| mask_shot                  |
| mask_shot_hull             |
| mask_solid_brushonly       |
| mask_playersolid_brushonly |
| mask_current               |
| mask_deadsolid             |

## Usage:

```lua
engine.trace_ray(eye_pos, end_pos, local_player, masks.mask_shot)
```
