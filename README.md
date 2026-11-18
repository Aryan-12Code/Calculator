# calculator

A simple R package that provides basic arithmetic and mathematical operations.

## Features

- **Addition**: `add(a, b)`
- **Subtraction**: `subtract(a, b)`
- **Multiplication**: `multiply(a, b)`
- **Division**: `divide(a, b)`
- **Square**: `square(a)`
- **Cube**: `cube(a)`

## Installation

You can install the development version of `calculator` from [GitHub](https://github.com/Aryan-12Code/Calculator) using `devtools` or `remotes`:

```r
# install.packages("remotes")
remotes::install_github("Aryan-12Code/Calculator")
```

## Usage

```r
library(calculator)

# Basic arithmetic operations
add(10, 5)        # Returns 15
subtract(10, 5)   # Returns 5
multiply(10, 5)   # Returns 50
divide(10, 5)     # Returns 2

# Power operations
square(4)         # Returns 16
cube(3)           # Returns 27
```

## License

MIT
