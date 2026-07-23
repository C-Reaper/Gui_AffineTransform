# Project README

## Overview
This project is a simple GUI application that demonstrates affine transformations using a green fast car sprite. The application uses libraries such as WindowEngine, Sprite, and RenderPixel to handle window creation, rendering, and pixel manipulation.

## Features
- **Affine Transformations**: Displays an animated car with affine transformations.
- **Cross-platform Support**: Builds and runs on Linux, Windows, Wine, and WebAssembly environments.

## Project Structure

### Prerequisites
- C/C++ Compiler (GCC)
- Make utility
- Standard development tools
- Libraries: X11 for Linux, user32 and gdi32 for Windows, winmm for multimedia support

## Build & Run

### Building the Project
To build the project, navigate to the project directory and run:
```sh
make -f Makefile.linux all  # For Linux
make -f Makefile.windows all  # For Windows
make -f Makefile.wine all  # For Wine
make -f Makefile.web all  # For WebAssembly
```

### Running the Project
To execute the built application:
```sh
make -f Makefile.linux exe  # For Linux
make -f Makefile.windows exe  # For Windows
make -f Makefile.wine exe  # For Wine
make -f Makefile.web exe  # For WebAssembly
```

### Clean Build
To clean the build artifacts and rebuild:
```sh
make -f Makefile.linux do  # For Linux
make -f Makefile.windows do  # For Windows
make -f Makefile.wine do  # For Wine
make -f Makefile.web do  # For WebAssembly
```

### Debugging
To debug the application:
```sh
make -f Makefile.linux debug  # For Linux
make -f Makefile.windows debug  # For Windows
make -f Makefile.wine debug  # For Wine
make -f Makefile.web dg  # For WebAssembly
```

This README provides a comprehensive guide to building and running the project across different platforms.