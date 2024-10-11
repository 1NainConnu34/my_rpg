# My RPG

## Description
This project is an RPG (Role Playing Game) developed in C, using the CSFML (Simple and Fast Multimedia Library for C). The game was created by **[Marlon830](https://github.com/Marlon830)**, **[Rodzpm](https://github.com/Rodzpm)**, **[emaurel](https://github.com/emaurel)** and me.

## Requirements

Before compiling and running the game, you need to install the necessary libraries:

### Required Libraries:
- **CSFML** (Graphics, Window, System, Audio)
- **Math Library** (`libm`)

#### Installing CSFML on Ubuntu/Debian:
```bash
sudo apt-get install libcsfml-dev
```

#### Installing CSFML on Arch Linux:
```bash
sudo pacman -S csfml
```

## Compilation

The project comes with a Makefile to simplify the compilation process.

To compile the game, run the following command in the terminal:
```bash
make
```

This will generate an executable named **my_rpg**.

## Execution

Once the compilation is complete, you can run the game with the following command:
```bash
./my_rpg
```

## Cleaning

To remove the object files and the generated executable, you can use the following commands:
```bash
make clean   # Removes only the object files
make fclean  # Removes both the object files and the executable
```

## Recompiling from Scratch

If you want to clean everything and recompile the project, use:
```bash
make re
```
