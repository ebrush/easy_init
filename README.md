# Usage
```
@init('r', 'g', 'b', a=1.0)
class Color:
    pass
```
will be 100% equivalent to:
```
class Color:
    def __init__(self, r, g, b, a=1.0):
        self.r = r
        self.g = g
        self.b = b
        self.a = a
```

# Installation
`pip install easy_init`
