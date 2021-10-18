# GUI Example

> Author: @onion
>
> Name: `GUI Example`
>
> Description: `A display of GUI control usage and interaction.`

```lua
local newCheckbox = gui.add_checkbox("New Checkbox", true)
local newSlider = gui.add_slider("New Slider", 0, 100, 69)

local newButton = gui.add_button("Print Values", function()
    utils.log("Checkbox: " .. tostring(newCheckbox:get_value()) ..
            "\nSlider:   " .. tostring(newSlider:get_value()) .. "\n")
end)
```
