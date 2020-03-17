# Ansi-Colors

ANSI escape sequences are a standard for in-band signaling to control the cursor location, color, and other options on video text terminals and terminal emulators.

Clone this project:

```
git clone https://github.com/endormi/ansi-colors.git
```

Run:

```
python example.py
```

Usage:

```python
from ansi_colors import *

print(text_color.blue + "Blue" + default)
print(text_color.light_blue + "Light Blue" + default)
print(highlight_color.blue + "Blue" + default)
print(extras.blink + text_color.blue + "Blink" + default)
```
