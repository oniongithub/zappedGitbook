# stages

## Fields:

| Name                           |
| ------------------------------ |
| frame_start                    |
| frame_net_update_start         |
| frame_net_postdataupdate_start |
| frame_net_postdataupdate_end   |
| frame_render_start             |
| frame_render_end               |

## Usage:

```lua
function on_framestagenotify(stage)
    if stage == stages.frame_render_start then
        -- shit goes here
    end
end
```
