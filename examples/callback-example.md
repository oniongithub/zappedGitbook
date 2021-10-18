# Callback Example

> Author: @onion
>
> Name: `Callback Example`
>
> Description: `A display of callback usage and interaction with returned arguments.`

```lua
function on_gameevent(event)
    if (event:get_name() == "player_hurt") then
        attacker = entitylist.get_entity_from_userid(event:get_int("attacker"))
        attacked = entitylist.get_entity_from_userid(event:get_int("userid"))
        local localPly = entitylist.get_localplayer();

        if (attacker:is_valid() and attacked:is_valid() and localPly:is_valid()) then
            if (attacker == localPly and attacked ~= localPly) then
                utils.log("You hit " .. attacked:get_name() .. " for " .. tostring(event:get_int("dmg_health")) .. " health.\n", color.new(255, 0, 0));
            end
        end
    end
end
```
