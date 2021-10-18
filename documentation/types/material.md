# material

## Fields:

| Name                                     | Type | Read Only |
| ---------------------------------------- | ---- | --------- |
| refresh()                                | fn   | \*        |
| set_flag(material_flag flag, bool state) | fn   | \*        |

## Usage:

```lua
function on_modelrender(model)
    material:set_flag(material_flags.ignorez, true)
    model:material_override(material)
end
```
