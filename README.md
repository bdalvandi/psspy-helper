# PSSPY Helper

## Overview

PSSPY Helper is a Python module designed to add Object-Oriented Programming (OOP) capabilities to the `psspy` module of PSS/E (Power System Simulator for Engineering). This enhancement allows for more intuitive and structured interactions with the PSS/E API, facilitating the development of more maintainable and reusable code for power system simulations.

## Features

- **Object-Oriented Design**: Simplifies interactions with `psspy` by introducing OOP principles.
- **Modular Structure**: Promotes code reusability and maintainability.
- **Enhanced Readability**: Makes scripts easier to understand and follow.
- **Improved Efficiency**: Streamlines complex tasks in power system simulations.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/bdalvandi/psspy-helper.git
   ```

2. Navigate to the project directory:
   ```bash
   cd psspy-helper
   ```

## Usage
To use PSSPY Helper, import the necessary classes and modules into your Python script. Below is a basic example to get you started:
```bash
import psspy
from psspy_helper import PSSPYHelper

# Initialize PSSPY Helper
helper = PSSPYHelper()

# Example usage
helper.load_case('example_case.sav')
helper.run_powerflow()
```

## Project Status
This is an ongoing project that is not yet finished. Contributions and feedback are highly appreciated to help improve and complete the module.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Contact
For any questions or inquiries, please contact Behdad Dalvandi at b.dalvandi@gmail.com.

