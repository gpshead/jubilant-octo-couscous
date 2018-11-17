# jubilant-octo-couscous
Experimental dumping ground for me test GitHub Pages rendering.

ie: [This README shows up on Pages here](https://gpshead.github.io/jubilant-octo-couscous/).

## code snippet rendering

normal:

```python
def gpshead(python):
    yield from gpshead(python)
```

can i control the formatting of that?

greens?

<span style="background-color:#e2f3eb;border-left-color:#0b8043;">
  
```python
# 📗
from typing import TypeVar
MeType = TypeVar('Me')
def gpshead(python: MeType) -> MeType:
    yield from gpshead(python)
```

</span>

reds?

<span style="background-color:#fbe9e7;border-left-color:#c53929;">

```python
# 🛑
def gpshead(python: complex) -> None:
    yield from gpshead(python)
```

</span>
