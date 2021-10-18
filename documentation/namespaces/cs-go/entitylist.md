# entitylist

## Example:

```lua
chickens = entitylist.get_entities_by_class("CChicken")
for i=1, #chickens do 
    chicken = chickens[i]
    --we have a chicken
end
```

## Functions:

### get_entity

| Argument | Type   | Required |
| -------- | ------ | -------- |
| index    | number | +        |

### get_localplayer

### get_players

### get_enemies

### get_all

### get_player_weapon

| Argument | Type                            | Required |
| -------- | ------------------------------- | -------- |
| entity   | [entity](../../types/entity.md) | +        |

### get_player_weapons

| Argument | Type                            | Required |
| -------- | ------------------------------- | -------- |
| entity   | [entity](../../types/entity.md) | +        |

### get_entity_from_userid

| Argument | Type   | Required |
| -------- | ------ | -------- |
| userid   | number | +        |

### get_entity_from_handle

| Argument | Type   | Required |
| -------- | ------ | -------- |
| handle   | handle | +        |

### get_entities_by_class

| Argument | Type   | Required |
| -------- | ------ | -------- |
| class    | string | +        |

### get_entities_by_classid

| Argument | Type   | Required |
| -------- | ------ | -------- |
| classid  | number | +        |

### highest_entity_index
