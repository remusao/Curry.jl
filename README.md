# Curry

```julia
using Curry

@curry function f(x, y, z)
    x + y + z
end

a = f(42)
b = a(42)
c = b(42)

# Result => 42 + 42 + 42 = 126
```
