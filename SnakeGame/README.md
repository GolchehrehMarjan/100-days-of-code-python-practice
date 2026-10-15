# Snake Game 🐍

A classic Snake game built with Python's `turtle` module, using an object-oriented structure.

This project was built as part of Angela Yu's **100 Days of Code: The Complete Python Pro Bootcamp** (Days 20–21).

## How to play

- Use the **arrow keys** to steer the snake.
- Eat the blue food to grow and increase your score.
- The game ends if you hit the wall or run into your own tail.
- Click the window after a game over to close it.

## Run it

Requires Python 3 (turtle is included in the standard library).

```bash
python main.py
```

## Project structure

| File | Responsibility |
|------|----------------|
| `main.py` | Screen setup, key bindings, main game loop, collision checks |
| `snake.py` | `Snake` class: segments, movement, growth, direction control |
| `food.py` | `Food` class: random placement of the food |
| `scoreboard.py` | `Scoreboard` class: score display and game-over message |

## Credits

Project idea and guided walkthrough by [Angela Yu](https://www.udemy.com/course/100-days-of-code/).
