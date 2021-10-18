# zapped

## Example:

```lua
utils.log(zapped.username .. " injected at " .. utils.format(zapped.inject_time, "%T"), color.new(255, 255, 255)) 
-- this prints "[username] injected at 13:37:00"
```

## Variables:

| name         | type                          | description                      |
| ------------ | ----------------------------- | -------------------------------- |
| desync_side  | number                        | Modifyable desync side.          |
| inject_time  | number                        | Injection time (unix timestamp). |
| manual_dir   | number                        | Manual aa direction.             |
| rainbow      | [color](../../types/color.md) | The global rainbow.              |
| userid       | number                        | userid                           |
| username     | string                        | username                         |
| users_online | number                        | Total users online.              |
