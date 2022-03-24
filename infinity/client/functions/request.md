# Request

```lua
ESX.Request(name, ...)
```

Triggers a server callback.

## Example

```lua
ESX.Request('ping')
```

## Arguments

|   **Argument**   |  **Data Type** | **Optional** |      **Default Value**       |       **Explanation**       |
|--------------|------------|----------|--------------------------|-----------------|
|  name |  string    | No       | -                        | Event name    |
|  ...        |  any    | Yes      | -                     | Event arguments   |