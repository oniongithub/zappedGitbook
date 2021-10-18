# usercmd

{% hint style="info" %}
You can access `usercmd` instance through the on_command callback.
{% endhint %}

## Fields:

| Name                 | Type                | Read Only |
| -------------------- | ------------------- | --------- |
| commandnumber        | number              | \*        |
| tick_count           | number              | \*        |
| viewangles           | [vector](vector.md) |           |
| forwardmove          | number              |           |
| sidemove             | number              |           |
| weaponselect         | number              |           |
| get_button()         | fn                  |           |
| set_button(button)   | fn                  |           |
| unset_button(button) | fn                  |           |
