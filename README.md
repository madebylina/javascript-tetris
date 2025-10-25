# Tetris Game - Pure JavaScript

A classic Tetris game built with vanilla **HTML5**, **CSS3**, and **JavaScript**. No frameworks, no libraries - just good old JavaScript. Great for learning game development and modern JavaScript.

## How to Play

### Play Online

Want to jump right in? Just click the link below:

**[🎮 Play Tetris Online](https://hoffhannisyan.github.io/javascript-tetris)**

### Run Locally

If you prefer to run it on your machine:

1. Clone the repo or download the ZIP
2. Extract if you downloaded the ZIP
3. Find the project folder
4. Open `index.html` in your browser
5. That's it! No build steps or installations needed.

### Controls

- **Enter**: Start or restart the game
- **Space**: Pause/unpause
- **Arrow Left** (←): Move left
- **Arrow Right** (→): Move right
- **Arrow Up** (↑): Rotate piece
- **Arrow Down** (↓): Drop faster

### How to Win

Stack the falling pieces to make complete horizontal lines. When you fill a line, it disappears and you get points. The game gets faster as you level up. Game over when the pieces stack up to the top.

## Browser Support

Works in any modern browser that supports HTML5 Canvas, ES6+ JavaScript, and CSS3.

## What You'll Learn

This project is great for learning:

- **Modern JavaScript**: ES6+ features like classes, arrow functions, and private fields
- **OOP Design**: Clean code structure using the MVC pattern
- **Canvas API**: How to draw and animate 2D graphics
- **Game Dev Basics**: Game loops, collision detection, state management, and handling user input
- **Clean Code**: Good practices for organizing and writing maintainable code

## Tech Stack

- **HTML5**: Canvas element for rendering the game
- **CSS3**: Styling and layout
- **JavaScript ES6+**: All the game logic

## Key Concepts Used

- Private class fields for encapsulation
- Static constants for game config
- Matrix operations for rotating pieces
- Collision detection with coordinate checking
- Timer-based game loop with `setInterval`
- Event-driven keyboard handling
- State management for game flow

## Features

- Full movement system (left, right, down, rotate)
- Line clearing with scoring
- Progressive difficulty (speeds up as you level up)
- Preview of next piece
- Pause and resume
- Game over detection and restart
- Keyboard controls

## Code Structure

The game uses the **MVC pattern** to keep things organized:

### 🎮 Controller
Handles user input and coordinates between Game and View
- Manages keyboard events
- Controls game timing
- Handles state transitions (start, pause, restart)
- Calculates speed based on level

### 🎯 Game (Model)
Contains all the game logic
- Generates and manages pieces
- Detects collisions
- Manages the board state
- Handles line clearing and scoring
- Tracks level progression

### 🎨 View
Handles all the rendering
- Sets up the canvas
- Draws the game board
- Renders the pieces
- Shows UI elements (score, level, next piece)
- Displays different screens (start, pause, game over)

## Main Algorithms

1. **Piece Rotation**: Rotates the matrix 90 degrees
2. **Collision Detection**: Checks boundaries and existing pieces
3. **Line Clearing**: Finds complete rows and removes them
4. **Scoring**: Calculates points based on lines cleared and level
5. **Speed Control**: Adjusts drop speed as levels increase

## What You Get

- No dependencies - pure vanilla JavaScript
- Modern ES6+ syntax
- Clean, readable code
- Handles edge cases properly
- Optimized for performance

## Contributing

Want to improve it? Contributions are welcome! Since this is an educational project, improvements that help others learn are especially appreciated.

Some ideas:
- Better documentation
- Performance tweaks
- New features (hold piece, ghost piece, etc.)
- Touch controls for mobile
- Visual improvements
- Accessibility features

Check out the [contributing guidelines](./.github/CONTRIBUTING.md) before submitting.

## License

MIT License - free to use for learning, personal projects, or whatever you want. See the [LICENSE](./LICENSE) file.

---

**Good for**: Learning JavaScript, getting into game dev, coding bootcamps, CS courses, or anyone who wants to see how a real game works under the hood.
