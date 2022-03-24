# Emit

```lua
ESX.Emit(name, ...)
```

Triggers a client-side event.

## Example

```lua
ESX.Emit('ping')
```

## Arguments

|   **Argument**   |  **Data Type** | **Optional** |      **Default Value**       |       **Explanation**       |
|--------------|------------|----------|--------------------------|-----------------|
|  name |  string    | No       | -                        | Event name    |
|  ...        |  any    | Yes      | -                     | Event arguments   |