# Repository Overview

- **Name**: Python Flappy Bird AI
- **Primary Language**: Python 3.10
- **Frameworks/Libraries**: pygame (game loop and rendering), neat-python (planned/optional)
- **Entry Point**: `flappy_bird.py`

## Structure

- `flappy_bird.py`: Main game logic (Bird, Pipe, Base classes, and main loop)
- `imgs/`: Game assets
  - `bg.png`, `base.png`, `pipe.png`, `bird1.png`, `bird2.png`, `bird3.png`
- `imgs_b286d95d6d.zip`: Asset archive (not required at runtime)
- `.zencoder/rules/repo.md`: This documentation file

## Setup

1. Install Python 3.10+
2. Install dependencies:
   - `pip install pygame`
   - If you plan to use NEAT later: `pip install neat-python`

## Run

- From the project root:
  - `python "c:\Users\saura\Python Flappy Bird AI\flappy_bird.py"`

## Notes

- Window size: 600x800
- Ensure `imgs/` contains all required images; paths are relative to project root.
- The game currently uses keyboard or loop logic for the bird. NEAT is imported but not actively used.

## Recent Fixes

- Consolidated duplicate `Pipe` classes into one and corrected image references and collision.
- Fixed main loop pipe handling (addition/removal and scoring) and proper draw call with pipes and score.
