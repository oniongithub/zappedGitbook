# cvars

## Fields:

| Name                     | Type | Read Only |
| ------------------------ | ---- | --------- |
| set_value(mixed value)   | fn   | \*        |
| force_value(mixed value) | fn   | \*        |
| get_number()             | fn   | \*        |
| get_string               | fn   | \*        |

## Usage:

```lua
sv_cheats = cvars.find("sv_cheats")
sv_cheats:force_value(0)
```
