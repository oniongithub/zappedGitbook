# materials

## Example:

```lua
params = {
    { "basetexture", "vgui/white_additive" },
    { "ignorez", "1" },
    { "nocull", "1" },
    { "nofog", "1" },
    { "selfillum", "1" }
}
material = materials.create("flat_ignorez", true, params)
```

## Functions:

### create

Creates a material.

| Argument   | Type   | Required |
| ---------- | ------ | -------- |
| name       | string | +        |
| flat       | bool   | +        |
| parameters | table  | +        |

### create

Creates a material.

| Argument | Type   | Required |
| -------- | ------ | -------- |
| name     | string | +        |
| vmt      | string | +        |

### find

Finds a material.

| Argument | Type   | Required |
| -------- | ------ | -------- |
| name     | string | +        |
