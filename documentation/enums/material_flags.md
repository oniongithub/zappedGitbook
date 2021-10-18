# material_flags

## Fields:

| Name        |
| ----------- |
| nodraw      |
| selfillum   |
| model       |
| flat        |
| nocull      |
| nofog       |
| ignorez     |
| halflambert |
| wireframe   |

## Usage:

```lua
function on_modelrender(model)
    material:set_flag(material_flags.ignorez, true)
    model:material_override(material)
end
```
