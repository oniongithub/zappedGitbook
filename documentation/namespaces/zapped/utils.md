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

### event_log

Logs to the event logger in the given color.

| Argument   | Type   | Required |
| ---------- | ------ | -------- |
| text       | string | +        |
| in console | bool   | +        |

### world_to_screen

Screen coordinates of an in game position.

| Argument | Type                                | Required |
| -------- | ----------------------------------- | -------- |
| position | [vector2d](../../types/vector2d.md) | +        |

### set_clan_tag

Changes your user's clantag.

| Argument | Type   | Required |
| -------- | ------ | -------- |
| clantag  | string | +        |

### set_name

Changes your user's name.

| Argument | Type   | Required |
| -------- | ------ | -------- |
| name     | string | +        |

### delay_call

Calls function after waiting 'delay' in seconds.

| Argument | Type     | Required |
| -------- | -------- | -------- |
| function | function | +        |
| delay    | number   | +        |

### timestamp

Grabs the unix timestamp.

### timezone_adjust

The offset for your computer's timezone.

### format_timestamp

Formats the given timestamp using [std::put_time](https://en.cppreference.com/w/cpp/io/manip/put_time).

| Argument  | Type   | Required |
| --------- | ------ | -------- |
| timestamp | number | +        |
| format    | string | +        |

### pattern_scan

Pointer to the given pattern in the module provided.

| Argument | Type    | Required |
| -------- | ------- | -------- |
| module   | module  | +        |
| pattern  | pattern | +        |

### create_interface

Pointer to the created interface.

| Argument       | Type   | Required |
| -------------- | ------ | -------- |
| module         | module | +        |
| interface name | string | +        |

### copy

Copies the given string to clipboard.

### paste

Returns the current clipboard text.
