# jubilant-octo-couscous
Experimental dumping ground for me test GitHub Pages rendering.

ie: [This README shows up on Pages here](https://gpshead.github.io/jubilant-octo-couscous/).

## code snippet rendering

```python
def gpshead(python):
    yield from gpshead(python)
```

... Can i control the background color of that for good vs bad code examples?

### greens?

📗
```python
from typing import TypeVar
MeType = TypeVar('Me')
def gpshead(python: MeType) -> MeType:
    yield from gpshead(python)
```

### reds?

🛑
```python
def gpshead(python: complex) -> None:
    yield from gpshead(python)
```

## Would you like to play a game?

**The only winning move**
:   is not to play.
_According to WHOPR_.\
This definition looks wrong in the github markdown on the source tree view, it
does not understand lines starting with a `:` as a definition.  But The Github
Pages Jekyll view is happy with it.
