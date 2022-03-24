# On

```lua
ESX.On(name, cb)
```

Registers a client > client event listener.

## Example

```lua
ESX.On('ping', function()
    print('pong')
end)
```

## Arguments

|   **Argument**   |  **Data Type** | **Optional** |      **Default Value**       |       **Explanation**       |
|--------------|------------|----------|--------------------------|-----------------|
|  name |  string    | No       | -                        | Event name    |
|  cb        |  function    | No      | -                     | Function callback   |