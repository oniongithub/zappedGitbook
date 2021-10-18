# http

## Example:

```lua
content = http.get("https://random_page.php?search=1337")
```

## Functions:

### get

Gets the content of a webpage.

| Argument | Type   | Required |
| -------- | ------ | -------- |
| URL      | string | +        |

### download

Downloads from a given URL to a given location on the system.

| Argument | Type                           | Required |
| -------- | ------------------------------ | -------- |
| URL      | string                         | +        |
| filename | st[r](../../types/color.md)ing | +        |
