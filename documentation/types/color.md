# color

## Fields:

| Name              | Type   | Read Only |
| ----------------- | ------ | --------- |
| r                 | number |           |
| g                 | number |           |
| b                 | number |           |
| a                 | number |           |
| set(r, g, b, a)   | fn     | \*        |
| from_hsv(h, s, v) | fn     | \*        |
| new(r, g, b, a)   | fn     | \*        |

## Usage:

```lua
col = color.new(255, 255, 255)
col.set(0, 0, 255) --changes color to blue
col.from_hsv(0, 100, 100) --changes color to red
```
