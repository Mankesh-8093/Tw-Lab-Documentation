# Doxygen Documentation

## 1. Introduction

Doxygen is a documentation generator tool used to generate documentation from source code.

It supports programming languages like C, C++, Java and Python.

## 2. Features of Doxygen

- Generates HTML documentation.
- Generates PDF documentation through LaTeX.
- Documents classes and functions.
- Supports comments and diagrams.
- Helps developers understand source code.

## 3. Doxygen Comment Syntax

Doxygen uses special comments to describe code.

Example:

```cpp
/**
 * @brief Adds two numbers.
 * @param a First number.
 * @param b Second number.
 * @return Sum of two numbers.
 */
int add(int a, int b)
{
    return a + b;
}
```

## 4. Important Doxygen Commands

| Command | Description |
|---|---|
| @brief | Short description |
| @param | Describes function parameter |
| @return | Describes return value |
| @author | Specifies author |
| @file | Describes a file |
| @details | Detailed description |

## 5. Example C++ Program

```cpp
/**
 * @file main.cpp
 * @brief Simple addition program.
 * @author Mankesh Meena
 */

#include <iostream>
using namespace std;

/**
 * @brief Adds two integers.
 * @param a First number.
 * @param b Second number.
 * @return Sum of a and b.
 */
int add(int a, int b)
{
    return a + b;
}

/**
 * @brief Main function.
 */
int main()
{
    cout << add(10, 20);
    return 0;
}
```

## 6. Steps to Generate Documentation

1. Install Doxygen.
2. Open the project folder.
3. Run the command `doxygen -g` to generate a configuration file.
4. Edit the Doxyfile settings.
5. Run `doxygen Doxyfile`.
6. Open the generated HTML documentation.

## 7. Important Commands

```bash
doxygen --version
doxygen -g
doxygen Doxyfile
```

## 8. Advantages of Doxygen

- Automatically generates documentation.
- Saves development time.
- Makes code easier to understand.
- Supports HTML and LaTeX output.

## 9. Conclusion

Doxygen is a useful tool for generating professional documentation from source code.