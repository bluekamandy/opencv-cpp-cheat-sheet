# OpenCV C++ Cheat Sheet

This document is a cheat sheet I created for myself but perhaps it will be useful to others. I will continue to work on it as I learn more about OpenCV. If you see mistakes or have suggestions, please feel free to contact me at masood@masoodkamandy.com.

## Getting Started with OpenCV and CMake

For this project we're going to build OpenCV from the source files and put them in a 'middleware' folder on our computer. Once you build a project once, it's not necessary to continually rebuild dependencies. Instead, it's best to have a middleware folder that you can use for multiple projects.

***Note:*** An alternative to this model is to use Git Submodules, which allow you to incorporate external code into your project. I introduce Git submodules in my CMake Cheat Sheet and my Git Cheat Sheet. Regardless of your approach, the CMake instructions will be the same.

OpenCV's source is [available on GitHub](https://github.com/opencv/opencv).



