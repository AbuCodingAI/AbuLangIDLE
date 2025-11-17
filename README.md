# AbuLang

A natural-language programming language that compiles to Python, designed for readability and ease of use.

## Installation

### 📥 Download

🪟 **Windows (No Python Required)**  

Download all 3 parts:
- [Part 1](https://github.com/AbuCodingAI/AbuLang/releases/latest/download/AbuLang-1.0-Windows.part1) (20 MB)
- [Part 2](https://github.com/AbuCodingAI/AbuLang/releases/latest/download/AbuLang-1.0-Windows.part2) (20 MB)
- [Part 3](https://github.com/AbuCodingAI/AbuLang/releases/latest/download/AbuLang-1.0-Windows.part3) (2 MB)
- [INSTALL.bat](https://github.com/AbuCodingAI/AbuLang/releases/latest/download/INSTALL.bat)

**To Install:**
1. Download all 4 files to the same folder
2. Run `INSTALL.bat`
3. Done! Run `AbuLang.exe`

## Quick Start

### Running AbuLang Files

```bash
# With Python
python AbuLang.py myfile.abu

# With standalone executable
AbuLang.exe myfile.abu

# Interactive IDLE
python AbuLang.py
```

### Building from Source

```bash
# Full build (includes AI libraries)
build_exe.bat

# Light build (no AI libraries, faster & smaller)
build_exe_light.bat
```

---

## Language Reference

### Structure / Definition

| Alias | Syntax | Description |
|-------|--------|-------------|
| `defin` `define` | `defin my_func():` | Define a function |
| `decla` `declare` | `decla MyClass:` | Declare a class |
| `creat` `create` `make` | `creat obj = MyClass()` | Create an object |
| `initi` `init` `start` | `initi(self)` | Initialize a class |
| `retur` `return` `yield` | `retur value` | Return a value |
| `exitp` `exit` `quit` | `exitp` | Exit program |

### Data Handling

| Alias | Syntax | Description |
|-------|--------|-------------|
| `setva` `assign` `setto` | `setva x = 10` | Assign variable |
| `delet` `remove` | `delet x` | Delete variable |
| `appen` `append` `addto` | `appen list value` | Append to list |
| `remov` `remove` `delet` | `remov list value` | Remove from list |
| `merge` `combine` | `merge dict1 dict2` | Merge dictionaries |
| `getit` `retrieve` | `getit dict key` | Get dictionary value |
| `setit` `modify` | `setit dict key value` | Set dictionary value |
| `clear` `reset` | `clear obj` | Clear list or dict |
| `copyv` `duplicate` | `copyv new = old` | Copy structure |

### I/O Commands

| Alias | Syntax | Description |
|-------|--------|-------------|
| `show` `displ` | `show "text"` | Display output |
| `ask` `read` `sysask` | `ask "prompt"` | Get user input |
| `write` `writi` `savef` | `write file "text"` | Write to file |
| `readf` `readfile` `loadf` | `readf file` | Read file contents |
| `loggi` `log` | `loggi "message"` | Log information |
| `pausi` `wait` | `pausi 2` | Pause for seconds |

### System Commands

| Alias | Syntax | Description |
|-------|--------|-------------|
| `libra` `library` `import` | `libra math` | Import a Python library |
| `inclu` `include` | `inclu pkg name` | Include module content |
| `conne` `connect` | `conne addr` | Connect to server |
| `disco` `disconnect` | `disco` | Disconnect socket |
| `uploa` `sendf` | `uploa url data` | Upload data |
| `downl` `fetchf` | `downl url` | Download file |
| `listd` `dirls` | `listd path` | List directory |
| `maked` `mkdir` | `maked path` | Create directory |
| `remov` `rmdir` | `remov file` | Remove file |
| `execa` `system` | `execa cmd` | Execute shell command |

### Logic / Flow Control

| Alias | Syntax | Description |
|-------|--------|-------------|
| `check` `if` `condi` | `check condition:` | Conditional check |
| `elifi` `elseif` | `elifi condition:` | Else-if branch |
| `other` `else` | `other:` | Else branch |
| `loopf` `repeat` | `loopf i in range(5):` | For loop |
| `while` `until` | `while condition:` | While loop |
| `break` `stop` | `break` | Break loop |
| `conti` `skip` | `conti` | Continue loop |
| `handl` `tryex` | `handl:` | Try block start |
| `catch` `except` | `catch Exception as e:` | Catch error |
| `final` `finally` | `final:` | Finally block |

### Math / Numeric

| Alias | Syntax | Description |
|-------|--------|-------------|
| `plus` `+` | `plus a b` | Add numbers |
| `minus` `-` | `minus a b` | Subtract numbers |
| `multi` `*` | `multi a b` | Multiply numbers |
| `divid` `/` | `divid a b` | Divide numbers |
| `expon` `^` `pow` | `expon a b` | Exponentiation |
| `modul` `mod` | `modul a b` | Modulo remainder |
| `perce` `%` | `perce value` | Convert to percent |
| `floor` `lowes` | `floor x` | Floor value |
| `ceili` `highv` | `ceili x` | Ceiling value |
| `absof` `abslt` | `absof x` | Absolute value |
| `sumup` `total` | `sumup data` | Sum of list |
| `avera` `mean` | `avera data` | Average of list |

### String Operations

| Alias | Syntax | Description |
|-------|--------|-------------|
| `strip` `trim` | `strip text` | Trim spaces |
| `lower` `downc` | `lower text` | Lowercase string |
| `upper` `uppec` | `upper text` | Uppercase string |
| `replc` `replace` | `replc text old new` | Replace text |
| `findt` `search` | `findt text word` | Find substring |
| `joinc` `merge` | `joinc list` | Join list into string |
| `formt` `format` | `formt text` | Format string |
| `lengt` `count` | `lengt text` | String length |

### Statistics (with libra stat)

| Alias | Syntax | Description |
|-------|--------|-------------|
| `meanv` `mean` `average` | `meanv data` | Calculate mean |
| `modev` `mode` | `modev data` | Calculate mode |
| `rangev` `range` | `rangev data` | Calculate range |
| `outli` `outlier` | `outli data` | Find outliers (Z-score) |

### GUI Widgets (Tkinter)

| Alias | Syntax | Description |
|-------|--------|-------------|
| `canvas` | `canvas` | Drawing surface |
| `label` | `label` | Display text |
| `btn` `button` | `btn` | Clickable button |
| `inputbox` `ipbx` `textfield` | `inputbox` | Text input field |
| `window` | `window` | Main application window |
| `slider` | `slider` | Slider control |
| `checkbox` `cbx` `tickbox` | `checkbox` | Checkbox |
| `dropdown` `selector` | `dropdown` | Dropdown menu |
| `container` | `container` | Frame container |
| `scrollbar` | `scrollbar` | Scrollbar |

### Layout Managers

| Alias | Syntax | Description |
|-------|--------|-------------|
| `place` | `place` | Simple automatic layout (pack) |
| `arrange` | `arrange` | Grid-based layout |
| `position` | `position` | Absolute positioning |
| `show_it` | `show_it` | Display widget |
| `spacex` `space_x` `gapx` `marginx` | `spacex` | Horizontal spacing |
| `spacey` `space_y` `gapy` `marginy` | `spacey` | Vertical spacing |

### Colors

| Alias | Value | Description |
|-------|-------|-------------|
| `red` | `(255, 0, 0)` | Pure red color |
| `green` | `(0, 255, 0)` | Pure green color |
| `blue` | `(0, 0, 255)` | Pure blue color |
| `white` | `(255, 255, 255)` | White color |
| `black` | `(0, 0, 0)` | Black color |
| `yellow` | `(255, 255, 0)` | Yellow color |

### Events

| Alias | Syntax | Description |
|-------|--------|-------------|
| `onclick` | `onclick` | Mouse click event |
| `onkey` | `onkey` | Any key press event |
| `onhover` | `onhover` | Mouse enters widget |
| `onleave` | `onleave` | Mouse leaves widget |

### Shape Drawing

| Alias | Syntax | Description |
|-------|--------|-------------|
| `def_box` | `def_box canvas type x1 y1 x2 y2 color` | Draw rectangle/oval |
| `def_circle` | `def_circle canvas x y radius color` | Draw circle |
| `get_coords` `coords` | `get_coords canvas obj` | Get coordinates |

### Pygame (DISPLAY)

| Alias | Syntax | Description |
|-------|--------|-------------|
| `screen` `setup` `start` | `screen` | Initialize pygame |
| `makescreen` | `makescreen` | Create display window |
| `refresh` | `refresh` | Update display (flip) |
| `update` | `update` | Update portions |
| `draw` | `draw` | Draw surface (blit) |
| `fill` | `fill` | Fill surface with color |

### Multi-Format Support

| Alias | Syntax | Description |
|-------|--------|-------------|
| `switch(format)` | `switch(yaml)` | Switch to format mode |
| `save_as(file)` | `save_as(file.yaml)` | Save buffer to file |
| `get_line` | `get_line 2 file.txt` | Get line from file |

---

## Advanced Features

### Inverse Walrus Operator (=:)

```abu
y = 6
x =: 2*y    # Assigns x=12 and shows "x>y 12"
```

### Local Variable Management

```abu
defin my_func():
    dx = 4
    # dx is automatically saved as local

# Access later
local(my_func) dx
local->global(my_func, dx)
```

### String Filtering

```abu
items = ["apple", "apricot", "banana"]
filtered = isolate([ap] from items)
show filtered  # ["apple", "apricot"]
```

---

## Examples

### Calculator Program

```abu
# Calculator Program
show "=== AbuLang Calculator ==="

x = ask "First number: "
y = ask "Second number: "

x = float(x)
y = float(y)

oper = ask "Operation (+, -, *, /): "

check oper == "+":
    show plus(x, y)
elifi oper == "-":
    show minus(x, y)
elifi oper == "*":
    show multi(x, y)
elifi oper == "/":
    show divid(x, y)
other:
    show "Invalid operation"

show "Done!"
```

### GUI Application

```abu
libra UI

window = ui.Tk()
window.title("Hello AbuLang")
window.geometry("400x300")

label = ui.Label(window, text="Welcome to AbuLang!")
label.pack(spacey=20)

defin on_click():
    show "Button clicked!"

btn = ui.Button(window, text="Click Me", command=on_click)
btn.pack(spacey=10)

window.mainloop()
```

### Game with Pygame

```abu
libra DISPLAY

ds.init()
screen = ds.display.set_mode((800, 600))
ds.display.set_caption("AbuLang Game")

running = True
while running:
    loopf event in ds.event.get():
        check event.type == ds.QUIT:
            running = False
    
    screen.fill(black)
    ds.draw.circle(screen, red, (400, 300), 50)
    ds.display.flip()

ds.quit()
```

---

## Features

- Natural language syntax - reads like English
- Multiple aliases for every command
- Full Python compatibility - use any Python library
- Interactive IDLE environment
- GUI support (Tkinter)
- Game development support (Pygame)
- Multi-format file support (YAML, JSON, etc.)
- Built-in statistics and math functions
- File I/O and system operations
- No parentheses needed for most commands

---

## License

See LICENSE file for details.
