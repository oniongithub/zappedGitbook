# gametrace

## Fields:

| Name         | Type                | Read Only |
| ------------ | ------------------- | --------- |
| entity       | [entity](entity.md) | \*        |
| hitbox       | number              | \*        |
| hitgroup     | number              | \*        |
| fraction     | number              | \*        |
| end_position | [vector](vector.md) | \*        |

## Usage:

```lua
local tr = engine.trace_ray(eye_pos, end_pos, local_player, masks.mask_shot)
local ent = tr.entity
```
