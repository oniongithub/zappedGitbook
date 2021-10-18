# renderer

## Example:

```lua
renderer.logo(0, 0, engine.screen_size().x, engine.screen_size().y, color.new(255, 255, 255, 150))
```

## Functions:

### create_font

Returns a font based on name, size, and boldness.

| Argument | Type   | Required |
| -------- | ------ | -------- |
| name     | string | +        |
| size     | number | +        |
| bold     | bool   | +        |

### create_texture

Returns a texture based on filename.

| Argument | Type   | Required |
| -------- | ------ | -------- |
| filename | string | +        |

### set_clip

Clips rendering to the given region.

| Argument | Type   | Required |
| -------- | ------ | -------- |
| x        | number | +        |
| y        | number | +        |
| w        | number | +        |
| h        | number | +        |

### remove_clip

Removes any set clip.

### image

| Argument | Type                          | Required |
| -------- | ----------------------------- | -------- |
| texture  | texture                       | +        |
| x        | number                        | +        |
| y        | number                        | +        |
| w        | number                        | +        |
| h        | number                        | +        |
| rotation | number                        | +        |
| color    | [color](../../types/color.md) | +        |

### line

| Argument | Type                          | Required |
| -------- | ----------------------------- | -------- |
| x1       | number                        | +        |
| y1       | number                        | +        |
| x2       | number                        | +        |
| y2       | number                        | +        |
| color    | [color](../../types/color.md) | +        |

### circle

| Argument | Type                          | Required |
| -------- | ----------------------------- | -------- |
| x        | number                        | +        |
| y        | number                        | +        |
| radius   | number                        | +        |
| color    | [color](../../types/color.md) | +        |

### filled_circle

| Argument | Type                          | Required |
| -------- | ----------------------------- | -------- |
| x        | number                        | +        |
| y        | number                        | +        |
| radius   | number                        | +        |
| color    | [color](../../types/color.md) | +        |

### triangle

| Argument | Type                                | Required |
| -------- | ----------------------------------- | -------- |
| vec1     | [vector2d](../../types/vector2d.md) | +        |
| vec2     | [vector2d](../../types/vector2d.md) | +        |
| vec3     | [vector2d](../../types/vector2d.md) | +        |
| color    | [color](../../types/color.md)       | +        |

### filled_triangle

| Argument | Type                                | Required |
| -------- | ----------------------------------- | -------- |
| vec1     | [vector2d](../../types/vector2d.md) | +        |
| vec2     | [vector2d](../../types/vector2d.md) | +        |
| vec3     | [vector2d](../../types/vector2d.md) | +        |
| color    | [color](../../types/color.md)       | +        |

### rect

| Argument | Type                          | Required |
| -------- | ----------------------------- | -------- |
| x        | number                        | +        |
| y        | number                        | +        |
| w        | number                        | +        |
| h        | number                        | +        |
| color    | [color](../../types/color.md) | +        |

### filled_rect

| Argument | Type                          | Required |
| -------- | ----------------------------- | -------- |
| x        | number                        | +        |
| y        | number                        | +        |
| w        | number                        | +        |
| h        | number                        | +        |
| color    | [color](../../types/color.md) | +        |

### gradient_rect

| Argument | Type                          | Required |
| -------- | ----------------------------- | -------- |
| x        | number                        | +        |
| y        | number                        | +        |
| w        | number                        | +        |
| h        | number                        | +        |
| vertical | bool                          | +        |
| color1   | [color](../../types/color.md) | +        |
| color2   | [color](../../types/color.md) | +        |

### text

| Argument | Type                          | Required |
| -------- | ----------------------------- | -------- |
| x        | number                        | +        |
| y        | number                        | +        |
| text     | string                        | +        |
| color    | [color](../../types/color.md) | +        |
| font     | font                          | -        |

### text_centered

| Argument   | Type                          | Required |
| ---------- | ----------------------------- | -------- |
| x          | number                        | +        |
| y          | number                        | +        |
| text       | string                        | +        |
| centered x | bool                          | +        |
| centered y | bool                          | +        |
| color      | [color](../../types/color.md) | +        |
| font       | font                          | -        |

### get_text_size

| Argument | Type   | Required |
| -------- | ------ | -------- |
| text     | string | +        |
| font     | font   | -        |

### logo

| Argument | Type                          | Required |
| -------- | ----------------------------- | -------- |
| x        | number                        | +        |
| y        | number                        | +        |
| w        | number                        | +        |
| h        | number                        | +        |
| color    | [color](../../types/color.md) | +        |

### lock_cursor

Locks the cursor from interactions.

### unlock_cursor

Unlocks the cursor from interactions.
