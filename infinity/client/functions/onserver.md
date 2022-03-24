# OnServer

```lua
ESX.OnServer(name, cb)
```

Registers a server > client event listener.

## Example

```lua
ESX.OnServer('ping', function()
    print('pong')
end)
```

## Arguments

|   **Argument**   |  **Data Type** | **Optional** |      **Default Value**       |       **Explanation**       |
|--------------|------------|----------|--------------------------|-----------------|
|  name |  string    | No       | -                        | Event name    |
|  cb        |  function    | No      | -                     | Function callback   |