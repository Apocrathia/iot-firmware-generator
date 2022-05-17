# Process for compiling

## What needs to be imported
- Device SDK
- Operating System
- Application Code
This is configured via the `CMakeLists.txt` file within the `include` statement.

## What needs to be configured dynamically
- `CMakeLists.txt` values

## What needs to be executed
- export PICO_SDK_FETCH_FROM_GIT=on
- mkdir build
- cd build
- cmake ..