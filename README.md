# SyntaX for Pygame 🐍🛡️

The Python bridge of the **SyntaX** ecosystem. This library provides a high-level, object-oriented wrapper for Pygame, mirroring the "Pure Power" philosophy of the C++ version.

## Features
* **Consistent API:** Similar structure to `SyntaX_for_SDL` for easy transition.
* **Smart Defaults:** Comes pre-configured with the official SyntaX Neon Purple.
* **Simplified Loop:** Handle events, clearing, and rendering with minimal code.
* **Lightweight:** No overhead, just pure Pythonic efficiency.

## Installation

### Prerequisites
* **Python 3.x**
* **Pygame CE or Pygame:**
  ```bash
  pip install pygame-ce
  ```

### Setup
1. Clone the repository:
   ```bash
   git clone [https://github.com/hypernova-developer/SyntaX_for_Pygame.git](https://github.com/hypernova-developer/SyntaX_for_Pygame.git)
   ```
2. Import the `Engine` class in your project:
   ```python
   from betterpygame import Engine
   ```

## Quick Start

```python
from betterpygame import Engine

def main():
    # Initialize SyntaX Engine
    app = Engine("SyntaX Python Power", 1280, 720)

    while app.is_running():
        app.update() # Handle events
        app.clear()  # Neon Purple background
        app.render() # Update display at 60 FPS

if __name__ == "__main__":
    main()
```

## License
Part of the SyntaX Project. Maintained by @hypernova-developer.
