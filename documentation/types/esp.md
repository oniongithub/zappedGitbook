# esp

{% hint style="info" %}
You can access`esp` instance through the on_esprender callback.
{% endhint %}

## Fields:

| Name                               | Type                | Read Only |
| ---------------------------------- | ------------------- | --------- |
| get_player()                       | [entity](entity.md) | \*        |
| left_text(string text, color)      | fn                  | \*        |
| right_text(string text, color)     | fn                  | \*        |
| top_text(string text, color)       | fn                  | \*        |
| bottom_text(string text, color)    | fn                  | \*        |
| left_bar(number fraction, color)   | fn                  | \*        |
| right_bar(number fraction, color)  | fn                  | \*        |
| top_bar(number fraction, color)    | fn                  | \*        |
| bottom_bar(number fraction, color) | fn                  | \*        |
| alpha()                            | number              | \*        |
