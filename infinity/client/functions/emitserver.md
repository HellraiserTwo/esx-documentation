# EmitServer

```lua
ESX.EmitServer(name, ...)
```

Triggers a server-side event.

## Example

```lua
ESX.EmitServer('ping')
```

## Arguments

|   **Argument**   |  **Data Type** | **Optional** |      **Default Value**       |       **Explanation**       |
|--------------|------------|----------|--------------------------|-----------------|
|  name |  string    | No       | -                        | Event name    |
|  ...        |  any    | Yes      | -                     | Event arguments   |