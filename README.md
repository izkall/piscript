# Piscript: A Lightweight Scripting Language for Fun and Learning 🎮✨

![Piscript Logo](https://img.shields.io/badge/Piscript-v1.0-blue?style=flat&logo=python)

Welcome to the **Piscript** repository! This project aims to provide a simple yet powerful scripting language that draws inspiration from Python while focusing on speed and ease of use. With built-in graphics capabilities and support for functional programming, Piscript is perfect for anyone looking to learn, experiment, or create retro-style visual programs.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Examples](#examples)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features 🚀

- **Lightweight and Fast**: Built in C for optimal performance.
- **Graphics Display**: A built-in 128x128 pixel graphics display for creating engaging visuals.
- **Functional Programming**: Supports functional programming paradigms for cleaner code.
- **Matrix Math**: Built-in support for matrix operations.
- **WebAssembly**: Compile your scripts to WebAssembly using Emscripten.
- **Ideal for Learning**: Perfect for beginners and experienced programmers alike.
- **Retro Style**: Create pixel art and retro games easily.

## Installation 🛠️

To get started with Piscript, you need to download the latest release. You can find the release files [here](https://github.com/izkall/piscript/releases). Download the appropriate file for your system and follow the instructions below to set it up.

### Steps:

1. Download the release file from the [Releases section](https://github.com/izkall/piscript/releases).
2. Extract the downloaded file.
3. Follow the instructions in the README file included in the extracted folder.

## Getting Started 📚

Once you have installed Piscript, you can start creating your own scripts. The syntax is similar to Python, making it easy to pick up for those familiar with Python programming.

### Example Script

```python
# A simple script to draw a square
def draw_square(size):
    for i in range(4):
        move_forward(size)
        turn_right(90)

draw_square(50)
```

## Usage 🎨

You can run your Piscript files directly from the command line. Use the following command to execute a script:

```bash
piscript your_script.pis
```

### Built-in Functions

Piscript comes with a variety of built-in functions for graphics, math, and more. Here are a few examples:

- `move_forward(distance)`: Moves the cursor forward by the specified distance.
- `turn_right(angle)`: Turns the cursor to the right by the specified angle.
- `draw_circle(radius)`: Draws a circle with the specified radius.

## Examples 🖼️

### Drawing a Circle

```python
# Draw a circle
def draw_circle(radius):
    for i in range(360):
        move_forward(radius)
        turn_right(1)

draw_circle(30)
```

### Creating a Simple Game

You can also create simple games using Piscript. Here’s a basic example of a game loop:

```python
# Simple game loop
while True:
    clear_screen()
    draw_square(50)
    if user_input() == 'exit':
        break
```

## Contributing 🤝

We welcome contributions to Piscript! If you would like to help out, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push your changes to your forked repository.
5. Create a pull request.

Please make sure to follow the coding standards and include tests for any new features.

## License 📜

Piscript is licensed under the MIT License. See the LICENSE file for more details.

## Contact 📬

For questions, suggestions, or feedback, feel free to reach out:

- GitHub: [izkall](https://github.com/izkall)
- Email: izkall@example.com

Explore the world of Piscript and unleash your creativity! For the latest releases, check out the [Releases section](https://github.com/izkall/piscript/releases). Happy coding!