# Final-Project

*It's simple game about D. Trump.*

![](https://github.com/Daniil-Aleshin/Python-Final-Project/blob/main/game%20images/game%201.PNG)

press **UP** button for jump

press **RIGHT** butoon for going to the right

press **LEFT** button for going to the left

press **SPACE** for shooting balls



## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install pygame.

```bash
pip install pygame
```


## Usage
```python
import pygame
import random

WIDTH = 360  # weidth of window
HEIGHT = 480 # height of window
FPS = 30 # frame rate per second

# creating game and window
pygame.init()
pygame.mixer.init()  # for sound
screen = pygame.display.set_mode((WIDTH, HEIGHT))
pygame.display.set_caption("My Game")
clock = pygame.time.Clock()

# Game loop
running = True
while running:
    # Process (event) input
    # Update
    # Visualization (assembly)
```

# License

[AIU](http://alatoo.edu.kg/)

### Project has done by:
@Daniil-Aleshin;     *Daniil Aleshin*

*Aiperi Aidarova*

*Meerlan Tynarbekov*
