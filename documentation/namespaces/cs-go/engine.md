# engine

## Example:

```lua
if (engine.in_game()) then end
```

## Functions:

### in_game

Returns if you're in game.

### client_cmd

Executes the command received (similar to console).

| Argument | Type   | Required |
| -------- | ------ | -------- |
| cmd      | string | +        |

### taking_screenshot

Returns if you're taking a screenshot.

### player_for_userid

Returns player id related to the userid acquired from a [gameevent](../../types/gameevent.md).

| Argument | Type   | Required |
| -------- | ------ | -------- |
| userid   | number | +        |

### localplayer

Returns the entity index of the local player.

### max_clients

Returns maximum number of clients.

### screen_size

Returns size of screen.

### get_viewangles

Returns client side view angles.

### set_viewangles

Sets client side view angles.

| Argument   | Type                            | Required |
| ---------- | ------------------------------- | -------- |
| viewangles | [vector](../../types/vector.md) | +        |

### trace_ray

Traces a ray.

| Argument | Type                            | Required |
| -------- | ------------------------------- | -------- |
| start    | [vector](../../types/vector.md) | +        |
| end      | [vector](../../types/vector.md) | +        |
| skip     | entity                          | +        |
| mask     | [masks](../../enums/masks.md)   | +        |

### trace_ray_hull

Traces a ray hull.

| Argument | Type                            | Required |
| -------- | ------------------------------- | -------- |
| start    | [vector](../../types/vector.md) | +        |
| end      | [vector](../../types/vector.md) | +        |
| mins     | [vector](../../types/vector.md) | +        |
| maxs     | [vector](../../types/vector.md) | +        |
| skip     | entity                          | +        |
| mask     | [masks](../../enums/masks.md)   | +        |

