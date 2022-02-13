# usercmd

{% hint style="info" %}
You can access `usercmd` instance through the on\_command callback.
{% endhint %}

## Fields:

| Name                  | Type                | Read Only |
| --------------------- | ------------------- | --------- |
| commandnumber         | number              | \*        |
| tickcount             | number              | \*        |
| viewangles            | [vector](vector.md) |           |
| forwardmove           | number              |           |
| sidemove              | number              |           |
| weaponselect          | number              |           |
| get\_button()         | fn                  |           |
| set\_button(button)   | fn                  |           |
| unset\_button(button) | fn                  |           |
