# gameevent

## Fields:

| Name                                 | Type    | Read Only |
| ------------------------------------ | ------- | --------- |
| get_name()                           | string  | \*        |
| get_bool(string key)                 | boolean | \*        |
| get_int(string key)                  | number  | \*        |
| get_string(string key)               | string  | \*        |
| set_bool(string key, bool value)     | fn      | \*        |
| set_int(string key, number value)    | fn      | \*        |
| set_string(string key, string value) | fn      | \*        |

## Usage:

```lua
function on_gameevent(event)
    utils.log(event:get_name() .. "\n", color.new(255, 255, 255))
end
```
