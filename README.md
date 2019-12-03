# CPPND: Capstone Snake Game Example

This is the Snake Game project with extension level of dificulty. The number of levels of difficulty added was 2 and I used concepts of OOP like polymorphism and inheritance e.g.

## Dependencies for Running Locally
* cmake >= 3.7
  * All OSes: [click here for installation instructions](https://cmake.org/install/)
* make >= 4.1 (Linux, Mac), 3.81 (Windows)
  * Linux: make is installed by default on most Linux distros
  * Mac: [install Xcode command line tools to get make](https://developer.apple.com/xcode/features/)
  * Windows: [Click here for installation instructions](http://gnuwin32.sourceforge.net/packages/make.htm)
* SDL2 >= 2.0
  * All installation instructions can be found [here](https://wiki.libsdl.org/Installation)
  * Note that for Linux, an `apt` or `apt-get` installation is preferred to building from source.
* gcc/g++ >= 5.4
  * Linux: gcc / g++ is installed by default on most Linux distros
  * Mac: same deal as make - [install Xcode command line tools](https://developer.apple.com/xcode/features/)
  * Windows: recommend using [MinGW](http://www.mingw.org/)

## Basic Build Instructions

1. Clone this repo.
2. Make a build directory in the top level directory: `mkdir build && cd build`
3. Compile: `cmake .. && make`
4. Run it: `./SnakeGame`.



## Rubric Point

- The project demonstrates an understanding of C++ functions and control structures
 
   In main.cpp, rendererLevel1.cpp, rendererLevel2.cpp  e.g;
   
- The project accepts user input and processes the input.

   In main.cpp, user input to choose the game level;
   
- The project uses Object Oriented Programming techniques

   Add new classes renderer.cpp, rendererLevel1.cpp, rendererLevel2.cpp, renderer.cpp.
   
- Classes use appropriate access specifiers for class members

  In files *.h, renderer, rendererLevel1, rendererLevel2.
  
- Class constructors utilize member initialization lists

  Construtors in classes call constructors and Base class constructors to initialize variables and objects
  
- Classes abstract implementation details from their interfaces

  Heritance with virtual method in rendererBase class
  
- Classes follow an appropriate inheritance hierarchy

  Heritance from Class renderer with virtual method implemented in child classes
  
- Derived class functions override virtual base class functions

  Virtual classes implemented in rendererLevel1, rendererLevel2 classes
  
- The project makes use of references in function declarations

  In classes rendererLevel1, rendererLevel2 in render function parameters
