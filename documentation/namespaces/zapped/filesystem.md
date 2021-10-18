# filesystem

## Example:

```lua
luas = filesystem.get_files_by_extension("C:\\zapped\\lua", ".lua")

for i = 1, #luas do
    utils.log("found " .. luas[i] .. "\n", color.new(255, 255, 255))
end
```

## Functions:

### get_directories

Gets directories within a path.

| Argument | Type   | Required |
| -------- | ------ | -------- |
| path     | string | +        |

### get_files

Gets files within a path.

| Argument | Type   | Required |
| -------- | ------ | -------- |
| path     | string | +        |

### get_files_by_extension

Gets files within a path with the given extension.

| Argument  | Type   | Required |
| --------- | ------ | -------- |
| path      | string | +        |
| extension | string | +        |

### file_exists

Returns if a given file is found on the system.

| Argument | Type   | Required |
| -------- | ------ | -------- |
| filename | string | +        |
