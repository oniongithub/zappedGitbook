# Callbacks

## List of all callbacks: <a href="list-of-all-callbacks" id="list-of-all-callbacks"></a>

## `on_command`

This callback will be executed on every command before it's processed.

### Parameters passed in callback:

| Name | Type                        | Description           |
| ---- | --------------------------- | --------------------- |
| cmd  | [usercmd](types/usercmd.md) | pre-processed command |

```lua
function on_command(cmd)
    cmd.viewangles.x = 0
end
```

## `on_esprender`

This callback will be executed when a player's ESP is rendered.

### Parameters passed in callback:

| Name | Type                | Description     |
| ---- | ------------------- | --------------- |
| ESP  | [esp](types/esp.md) | passed ESP type |

```lua
function on_esprender(esp)
    player = esp:get_player()

    if player:is_valid() and player:is_enemy() then
        esp:top_text("enemy", color.new(255, 255, 255))
    end
end
```

## `on_gameevent`

This callback will be executed when a game event occurs.

### Parameters passed in callback:

| Name  | Type                            | Description       |
| ----- | ------------------------------- | ----------------- |
| Event | [gameevent](types/gameevent.md) | passed game event |

```lua
function on_gameevent(event)
    utils.log(event:get_name() .. "\n", color.new(255, 255, 255))
end
```

## `on_framestagenotify`

This callback will be executed at stages of preparation for each frame.

### Parameters passed in callback:

| Name  | Type                     | Description       |
| ----- | ------------------------ | ----------------- |
| Stage | [stage](enums/stages.md) | passed stage enum |

```lua
function on_framestagenotify(stage)
    if stage == stages.frame_render_start then
        -- do shit here
    end
end
```

## `on_render`

This callback will be executed for every rendered frame.

```lua
function on_render()
    renderer.logo(0, 0, 50, 50, color.new(255, 255, 255, 150))
end
```

## `on_modelrender`

This callback will be executed when rendering a model.

### Parameters passed in callback:

| Name  | Type                    | Description       |
| ----- | ----------------------- | ----------------- |
| Model | [model](types/model.md) | passed model type |

```lua
function on_modelrender(model)
    if string.find(model:get_name(), "models/player") then
        -- do shit here
    end
end
```

## `on_shutdown`

This callback will be executed before a script is unloaded.

```lua
function on_shutdown()
    my_cvar.set_value(default_value)
end
```
