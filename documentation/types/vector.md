# vector

## Fields:

| Name                | Type   | Read Only |
| ------------------- | ------ | --------- |
| x                   | number |           |
| y                   | number |           |
| z                   | number |           |
| length()            | number | \*        |
| length2d()          | number | \*        |
| dist_to(vector vec) | number | \*        |
| normalize()         | fn     | \*        |

## Usage:

```lua
vec = vector.new(1, 2, 3)
utils.log(vec.x)
```
