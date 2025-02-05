# std::vector<bool> Performance Gotcha
This example demonstrates a common performance issue encountered when using std::vector<bool> in C++. Because of its space optimization, accessing elements is not as straightforward and can be significantly slower compared to standard vectors.  The solution illustrates alternative approaches for better performance.

## How to Reproduce the Bug
Compile and run `vectorBoolBug.cpp`. Observe the execution time.  Compare this to the solution's performance.