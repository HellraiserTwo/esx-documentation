# OffServer

```lua
ESX.OffServer(table)
```

Unregisters a server > client listener.

## Example

```lua
local event = ESX.OnServer('ping', function(end)
    print('pong')
end)
ESX.OffServer(event)
```

## Arguments

|   **Argument**   |  **Data Type** | **Optional** |      **Default Value**       |       **Explanation**       |
|--------------|------------|----------|--------------------------|-----------------|
|  event |  table    | No       | -                        | Event table    |