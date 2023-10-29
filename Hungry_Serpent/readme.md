# Hungry Serpent Game

Welcome to the Snake Game implemented in C++! This classic arcade game allows you to control a snake as it moves around the screen, eating food and growing longer with each meal. Be careful not to collide with the walls or yourself!

## How to Play

### Controls

- **'a'**: Move the snake left
- **'d'**: Move the snake right
- **'w'**: Move the snake up
- **'s'**: Move the snake down
- **'x'**: Quit the game

### Objective

- Eat the 'F' (fruit) to grow your snake.
- Avoid running into the walls or the snake's own tail, as it will result in game over.

### Scoring

- Each 'F' eaten increases your score by 10 points.
- The game speed may increase as your score grows, making it more challenging.

## Compiling and Running

To compile and run the game, follow these steps:

1. Compile the code using a C++ compiler like g++:
   ```bash
   g++ -o snake Hungry_Serpent.cpp

2. Run the compiled program:
   ```bash
   ./snake
   ```

## Requirements

- C++ compiler (e.g., g++)
- Windows OS (for 'conio.h' library)
