# model

## Fields:

| Name                        | Type                | Read Only |
| --------------------------- | ------------------- | --------- |
| get_entity()                | [entity](entity.md) | \*        |
| get_name()                  | string              | \*        |
| material_override(material) | fn                  | \*        |
| color_modulate(color)       | fn                  | \*        |
| draw()                      | fn                  | \*        |

## Usage:

```lua
function on_modelrender(model)
    if string.find(model:get_name(), "models/player") then
        -- shit goes here
    end
end
```
