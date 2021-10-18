# control

## Fields:

| Name                                      | Type  | Read Only |
| ----------------------------------------- | ----- | --------- |
| get_value()                               | mixed | \*        |
| set_value(mixed value)                    | fn    | \*        |
| update_items((variadic or array) options) | fn    | \*        |

## Usage:

```lua
test = gui.add_dropdown("test", "option 1", "option 2", "option 3")
utils.log("selected: " .. test:get_value() .. "\n", color.new(255, 255, 255))
```
