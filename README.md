 Calcolo Numerico (Numerical Calculus)

**Author**: Francesco Ferrillo  
**Description**: A collection of exercises, assignments and small projects from the university course "Calcolo Numerico" (Numerical Calculus), implemented mainly in MATLAB/Octave and possibly other tools.

![License](https://img.shields.io/badge/license-Educational-lightgrey)
![Language](https://img.shields.io/badge/language-MATLAB%2FOctave-blue)
![Status](https://img.shields.io/badge/status-in%20progress-yellow)

## Table of Contents

- [Overview](#overview)
- [Technologies](#technologies)
- [Implemented Methods](#implemented-methods)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Contributing](#contributing)

## Overview

This repository contains coursework and code related to the Numerical Calculus course. It demonstrates implementation of numerical algorithms for solving mathematical problems such as root finding, interpolation, integration, and systems of equations.

## Technologies

- **MATLAB / GNU Octave** — main language for implementing numerical methods
- **PDF / Reports** — documentation and explanations of the methods


Update this section to reflect your actual folder names.

## Implemented Methods

This course typically covers methods such as:

- Root finding (Bisection, Newton-Raphson, Secant)
- Numerical integration (Trapezoidal, Simpson’s)
- Numerical differentiation
- Linear systems (Gaussian elimination, LU decomposition)
- Interpolation (Lagrange, Newton polynomials)
- Approximation and least squares
- Eigenvalues and eigenvectors

List the ones you have actually implemented in your repo.

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/FrancescoFerrillo/Calcolo-Numerico.git
   cd Calcolo-Numerico
   ```

2. Open MATLAB or GNU Octave.

3. Navigate to the folder containing the scripts and run them as needed.

## Usage

For example, to run a script implementing the Newton-Raphson method:
```matlab
newton_method(@(x) x^2 - 2, 1.0, 1e-6)
```

Or to test a numerical integration:
```matlab
result = simpson_integral(@(x) sin(x), 0, pi)
```

Adjust these examples to match the actual function names in your repository.

## Contributing

If you want to expand or improve this repository:

1. Fork the repository
2. Create a feature branch (`feature-new-method`)
3. Add or improve scripts and documentation
4. Submit a Pull Request

Please follow consistent coding style and include comments.
