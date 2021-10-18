# entity

## Fields:

| Name                                 | Type                | Read Only |
| ------------------------------------ | ------------------- | --------- |
| is_valid()                           | boolean             | \*        |
| is_player()                          | boolean             | \*        |
| is_weapon()                          | boolean             | \*        |
| is_alive()                           | boolean             | \*        |
| is_dormant()                         | boolean             | \*        |
| is_local()                           | boolean             | \*        |
| is_enemy()                           | boolean             | \*        |
| is_visible(vector point)             | boolean             | \*        |
| looking_at()                         | entity              | \*        |
| has_flag(number flag)                | boolean             | \*        |
| get_index()                          | number              | \*        |
| get_eye_pos()                        | [vector](vector.md) | \*        |
| get_name()                           | string              | \*        |
| get_origin()                         | [vector](vector.md) | \*        |
| get_class_\__id()                    | number              | \*        |
| get_class_name()                     | string              | \*        |
| get_hitbox(number hitbox)            | [vector](vector.md) | \*        |
| get_bone(number bone)                | [vector](vector.md) | \*        |
| get_prop(string netvar)              | mixed               | \*        |
| set_prop(string netvar, mixed value) | fn                  | \*        |
| is_legit()                           | boolean             | \*        |
| set_resolve(number delta)            | fn                  | \*        |
| get_max_desync()                     | number              | \*        |
| get_misses_spread()                  | number              | \*        |
| get_misses_resolve()                 | number              | \*        |

## Usage:

```lua
-- if you supply a table name that will be used, otherwise it'll use the entities class 
health = ent:get_prop("m_iHealth") 
-- grabs the player's health 
simulation_time = ent:get_prop("DT_BaseEntity:m_flSimulationTime") --grabs player's simulation time
```
