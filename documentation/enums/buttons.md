# buttons

## Fields:

| Name         |
| ------------ |
| in_attack    |
| in_attack2   |
| in_jump      |
| in_duck      |
| in_forward   |
| in_back      |
| in_moveleft  |
| in_moveright |
| in_use       |
| in_reload    |
| in_score     |
| in_walk      |
| in_weapon1   |
| in_weapon2   |

## Usage:

```lua
function on_command(cmd)
    if cmd:get_button(buttons.in_attack) then
        -- shit goes here
    end
end
```
