# Test build
This directory contains a test build of the project

## Building & Running
Run `make PROJECT=lifesensor_test build flash monitor` from the projects root

## Adding tests
To add the unit test of a component,
append the component name to the `TEST_COMPONENTS` variable
in the `CMakeLists.txt` .