# Super Mario Bros Java Game

A Java implementation of the classic Super Mario Bros game, developed by Phạm Lê Ngọc Sơn.

## Project Description

This project is a recreation of the classic Nintendo game Super Mario Bros using Java. The game features familiar gameplay mechanics, enemies, and environments from the original game, implemented with a Model-View-Controller architecture.

## Project Structure

The project follows a modular architecture organized into the following packages:

### /src/manager
Contains classes responsible for managing game components and core functionality:
- **GameEngine.java**: The main class that initializes the game and runs the game loop
- **MapManager.java**: Manages map creation and game world interactions
- **SoundManager.java**: Handles all game sounds and music
- **InputManager.java**: Manages keyboard and mouse input
- **Camera.java**: Controls the game camera and viewport
- **MapCreator.java**: Responsible for creating game maps
- **GameStatus.java**: Enum that tracks the current game state
- **ButtonAction.java**: Defines player actions and controls

### /src/model
Contains game objects and their behaviors:
- **GameObject.java**: Base class for all game objects
- **Map.java**: Represents the game map
- **EndFlag.java**: End-level flag object
- Subdirectories for various game elements:
  - **/prize**: Power-ups and collectibles
  - **/hero**: Mario character implementation
  - **/enemy**: Enemy characters
  - **/brick**: Map blocks and platforms

### /src/view
Handles the UI and rendering:
- **UIManager.java**: Main UI component that renders the game
- **ImageLoader.java**: Loads and manages game images and sprites
- **Animation.java**: Handles sprite animations
- **MapSelection.java**: UI for map selection
- **StartScreenSelection.java**: UI for the start screen
- **MapSelectionItem.java**: Individual map selection components

### /src/media
Contains game assets:
- Images, sprites, and other graphical resources
- Sound effects and music
- Fonts

## Features

- Classic Super Mario Bros gameplay
- Multiple levels with different challenges
- Original enemies: Goombas, Koopas, etc.
- Power-ups: Mushrooms, Fire Flowers, etc.
- Lives system and score tracking
- Interactive environment with breakable blocks and hidden items
- Fluid animations and controls

## How to Play

1. **Start the Game**: Run the GameEngine class
2. **Navigation**: Use the arrow keys to navigate menus
3. **Select**: Press Enter/Return to select menu options
4. **Controls**:
   - Left/Right Arrow Keys: Move Mario
   - Space: Jump
   - F: Fireball (when powered up)
   - P: Pause/Resume game
   - Esc: Return to the main menu

## System Requirements

- Java Runtime Environment (JRE) 8 or higher
- 64-bit operating system
- 2GB RAM minimum
- Graphics card with support for 2D rendering

## Development

This project was developed using:
- Java
- Swing for the GUI components
- Custom game engine for physics and collision detection

## Credits

- Developed by: Phạm Lê Ngọc Sơn
- Original game by Nintendo