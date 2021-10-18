# playerresources

## Example:

```lua
wins = playerresources.get_prop(entitylist.get_localplayer(), "m_iCompetitiveWins")
```

## Function:

### get_prop

Returns value of prop for the given player.

| Argument | Type                                     | Required |
| -------- | ---------------------------------------- | -------- |
| entity   | [entity](../../types/entity.md) / number | +        |
| netvar   | string                                   | +        |
