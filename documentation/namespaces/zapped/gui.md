# gui

## Example:

```lua
test = gui.add_dropdown("test", "option 1", "option 2", "option 3")
utils.log("selected: " .. test:get_value() .. "\n", color.new(255, 255, 255))
```

## Functions:

### add_checkbox

| Argument | Type   | Required |
| -------- | ------ | -------- |
| title    | string | +        |
| default  | bool   | -        |

### add_slider

| Argument | Type   | Required |
| -------- | ------ | -------- |
| title    | string | +        |
| min      | number | +        |
| max      | number | +        |
| default  | number | -        |

### add_dropdown

| Argument | Type                    | Required |
| -------- | ----------------------- | -------- |
| title    | string                  | +        |
| options  | variadic string / array | +        |

### add_dropdown_multi

| Argument | Type                    | Required |
| -------- | ----------------------- | -------- |
| title    | string                  | +        |
| options  | variadic string / array | +        |

### add_keybind

| Argument | Type   | Required |
| -------- | ------ | -------- |
| title    | string | +        |
| default  | number | -        |

### add_colorpicker

| Argument | Type   | Required |
| -------- | ------ | -------- |
| title    | string | +        |
| default  | color  | -        |

### add_textbox

| Argument | Type   | Required |
| -------- | ------ | -------- |
| title    | string | +        |
| default  | string | -        |

### add_numberfield

| Argument | Type   | Required |
| -------- | ------ | -------- |
| title    | string | +        |
| default  | number | -        |

### add_filedropdown

| Argument   | Type                    | Required |
| ---------- | ----------------------- | -------- |
| title      | string                  | +        |
| path       | string                  | +        |
| extensions | variadic string / array | +        |

### add_spacer

| Argument | Type   | Required |
| -------- | ------ | -------- |
| title    | string | +        |
| spacing  | number | -        |

### add_button

| Argument | Type     | Required |
| -------- | -------- | -------- |
| title    | string   | +        |
| callback | function | +        |

### find

Finds control by its identifier (use dev console "list" command).

| Argument   | Type   | Required |
| ---------- | ------ | -------- |
| identifier | string | +        |

### get_alpha

Returns alpha that the ui is being rendered at.
