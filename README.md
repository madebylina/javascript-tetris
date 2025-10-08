# Tetris Game - Pure JavaScript Implementation

A complete implementation of the classic Tetris game built entirely with vanilla **HTML5**, **CSS3**, and **JavaScript** - no external libraries or frameworks required. This project serves as an excellent educational resource for students learning game development, object-oriented programming, and modern JavaScript concepts.

## How to Play

### Play Online
You can play the game directly in your browser without downloading anything:

**[🎮 Play Tetris Online](https://hoffhannisyan.github.io/javascript-tetris)**

### Play Locally
To play the game locally, follow these steps:

1. Clone the repository or download the ZIP file
2. If downloaded as ZIP, extract the files
3. Navigate to the project directory
4. Open `index.html` in any modern web browser
5. No additional installation or build process required!

### Game Controls
- **Enter**: Start the game or restart after game over
- **Space**: Pause/Resume the game
- **Arrow Left** (←): Move tetromino left
- **Arrow Right** (→): Move tetromino right
- **Arrow Up** (↑): Rotate the tetromino clockwise
- **Arrow Down** (↓): Soft drop (faster descent)

### Objective
Stack falling tetromino pieces to create complete horizontal lines. When a line is completed, it disappears and you earn points. The game speeds up as you progress through levels. The game ends when pieces reach the top of the playing field.
## Browser Compatibility

This game works in all modern browsers that support:
- HTML5 Canvas API
- ES6+ JavaScript features (classes, arrow functions, const/let)
- CSS3 features

## Educational Purpose

This Tetris implementation is specifically designed for learning and teaching purposes, demonstrating:

- **Modern JavaScript ES6+ features**: Classes, private fields, static methods, and arrow functions
- **Object-Oriented Programming**: Clean separation of concerns using MVC (Model-View-Controller) pattern
- **HTML5 Canvas API**: 2D graphics rendering and animation techniques
- **Game development fundamentals**: Game loops, collision detection, state management, and user input handling
- **Clean code practices**: Proper encapsulation, meaningful naming conventions, and code organization

## Technical Implementation Details

### Core Technologies Used
- **HTML5**: Semantic structure and Canvas element for game rendering
- **CSS3**: Styling and responsive design principles
- **JavaScript ES6+**: Modern language features and best practices

### Key Programming Concepts Demonstrated
- **Private class fields** (`#privateField`) for proper encapsulation
- **Static constants** for configuration management
- **Matrix operations** for tetromino rotation algorithms
- **Collision detection** using coordinate-based boundary checking
- **Timer-based game loops** with `setInterval` and dynamic speed calculation
- **Event-driven programming** for keyboard input handling
- **State management** for game flow control (start, pause, game over)

### Game Features Implemented
- Complete tetromino movement system (left, right, down, rotation)
- Line clearing algorithm with proper scoring system
- Progressive difficulty with increasing drop speed
- Next piece preview functionality
- Pause and resume gameplay
- Game over detection and restart capability
- Responsive keyboard controls

## Code Architecture

The game follows the **MVC (Model-View-Controller)** design pattern for clean separation of concerns:

### 🎮 Controller Class
- **Purpose**: Manages user input and coordinates between Game and View
- **Key responsibilities**:
  - Keyboard event handling
  - Game timing and drop intervals
  - Game state transitions (start, pause, restart)
  - Speed calculation based on level progression

### 🎯 Game Class (Model)
- **Purpose**: Contains all game logic and state management
- **Key responsibilities**:
  - Tetromino generation and management
  - Collision detection algorithms
  - Board state management
  - Line clearing and scoring system
  - Level progression logic

### 🎨 View Class
- **Purpose**: Handles all visual rendering using HTML5 Canvas
- **Key responsibilities**:
  - Canvas setup and management
  - Game board rendering
  - Tetromino piece visualization
  - UI elements (score, level, next piece)
  - Screen state rendering (start, pause, game over)

### Key Algorithms Implemented

1. **Tetromino Rotation**: Matrix rotation algorithm for 90-degree clockwise/counterclockwise rotation
2. **Collision Detection**: Boundary checking for walls, floor, and existing pieces
3. **Line Clearing**: Row completion detection and removal with proper array manipulation
4. **Scoring System**: Progressive scoring based on lines cleared and current level
5. **Drop Speed Calculation**: Dynamic timing adjustment based on game level

## Learning Outcomes

By studying and working with this code, students will learn:

- How to structure a complete JavaScript application using classes
- Canvas API fundamentals for 2D game development
- Game loop implementation and timing management
- State management patterns in interactive applications
- Event handling and user input processing
- Algorithm implementation (rotation, collision detection)
- Object-oriented design principles in JavaScript

## Code Quality Features

- **No external dependencies**: Pure vanilla JavaScript implementation
- **Modern ES6+ syntax**: Uses latest JavaScript features appropriately
- **Clean code principles**: Readable, maintainable, and well-documented
- **Proper error handling**: Graceful handling of edge cases
- **Performance optimized**: Efficient rendering and game loop implementation

## Contributing

Contributions are welcome! This project is designed to be educational, so improvements that enhance learning value are especially appreciated. Please check out the [contributing guidelines](./.github/CONTRIBUTING.md) before submitting pull requests.

### Areas for Contribution
- Code documentation and comments
- Performance optimizations
- Additional game features (hold piece, ghost piece, etc.)
- Mobile touch controls
- Visual enhancements
- Accessibility improvements

## License

This project is open source under the [MIT License](./LICENSE), making it free to use for educational purposes, personal projects, and learning.

---

**Perfect for**: JavaScript students, game development beginners, coding bootcamps, computer science courses, and anyone interested in learning clean, modern JavaScript through a practical project.
