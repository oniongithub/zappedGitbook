# utils

## Examples:

```lua
utils.log("hello. i will be printed in console.\n", color.new(255, 255, 255))
```

## Functions:

### log

Prints text to console in the given color.

| Argument | Type                          | Required |
| -------- | ----------------------------- | -------- |
| text     | string                        | +        |
| color    | [color](../../types/color.md) | -        |

### notify

Sends a notification in the given color.

| Argument | Type                          | Required |
| -------- | ----------------------------- | -------- |
| text     | string                        | +        |
| color    | [color](../../types/color.md) | -        |

### event\_log

Logs to the event logger in the given color.

| Argument   | Type   | Required |
| ---------- | ------ | -------- |
| text       | string | +        |
| in console | bool   | +        |

### world\_to\_screen

Screen coordinates of an in game position.

| Argument | Type                                | Required |
| -------- | ----------------------------------- | -------- |
| position | [vector2d](../../types/vector2d.md) | +        |

### set\_clan\_tag

Changes your user's clantag.

| Argument | Type   | Required |
| -------- | ------ | -------- |
| clantag  | string | +        |

### set\_name

Changes your user's name.

| Argument | Type   | Required |
| -------- | ------ | -------- |
| name     | string | +        |

### delay\_call

Calls function after waiting 'delay' in seconds.

| Argument | Type     | Required |
| -------- | -------- | -------- |
| function | function | +        |
| delay    | number   | +        |

### timestamp

Grabs the unix timestamp.

### timezone\_adjust

The offset for your computer's timezone.

### format\_timestamp

Formats the given timestamp using [std::put\_time](https://en.cppreference.com/w/cpp/io/manip/put\_time).

| Argument  | Type   | Required |
| --------- | ------ | -------- |
| timestamp | number | +        |
| format    | string | +        |

### find\_pattern

Pointer to the given pattern in the module provided.

| Argument | Type    | Required |
| -------- | ------- | -------- |
| module   | module  | +        |
| pattern  | pattern | +        |

### create\_interface

Pointer to the created interface.

| Argument       | Type   | Required |
| -------------- | ------ | -------- |
| module         | module | +        |
| interface name | string | +        |

### copy

Copies the given string to clipboard.

### paste

Returns the current clipboard text.
