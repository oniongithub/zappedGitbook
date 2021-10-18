# walkbot

## Examples:

```lua
walkbot.log("walkbot target: " . walkbot.get_destination() . "\n", color.new(255, 255, 255))
```

## Functions:

| name              | type                            | description                      |
| ----------------- | ------------------------------- | -------------------------------- |
| get_entity()      | [entity](../../types/entity.md) | Entity being targetted (if any). |
| get_destination() | string                          | Destination label.               |
| get_distance()    | number                          | Distance to the destination.     |

