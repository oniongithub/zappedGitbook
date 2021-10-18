# game

## Example:

```lua
utils.log("current map is " .. game.map_name .. "\n", color.new(255, 255, 255))
```

## Variables:

| name        | type   | description                  |
| ----------- | ------ | ---------------------------- |
| fps         | number | Your current FPS.            |
| latency     | number | Your calculated latency.     |
| tickrate    | number | The server's tick rate.      |
| server_ip   | string | The server's IP.             |
| server_name | string | The server's name.           |
| map_name    | string | The server's map name.       |
| focused     | bool   | If CS:GO is the focused app. |
