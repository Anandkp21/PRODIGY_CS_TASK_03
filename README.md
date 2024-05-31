---

# Password Complexity Checker Tool

A simple command-line tool to assess the strength of a password based on various criteria such as length, inclusion of uppercase and lowercase letters, digits, and special characters.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Example](#example)
- [License](#license)
- [Contributing](#contributing)

## Overview

The Password Strength Assessment Tool checks the strength of a password by evaluating its length, the presence of both uppercase and lowercase letters, digits, and special characters. It provides feedback on how to improve the password strength and categorizes it as strong, moderate, or weak.

## Features

- **Length Check:** Ensures the password is at least 8 characters long.
- **Uppercase and Lowercase Check:** Verifies the presence of both uppercase and lowercase letters.
- **Digit Check:** Confirms the inclusion of at least one digit.
- **Special Character Check:** Checks for the presence of at least one special character.

## Installation

### Prerequisites

- Python 3.x
- Pip (Python package installer)

### Steps

1. **Clone the repository:**
   ```sh
   git clone https://github.com/Anandkp21/PRODIGY_CS_TASK_03.git
   ```

2. **Navigate to the project directory:**
   ```sh
   cd password-strength-tool
   ```

3. **Run the tool:**
   ```sh
   python PassChecker.py
   ```

## Usage

1. **Run the password strength assessment tool:**
   ```sh
   python PassChecker.py
   ```

2. **Enter your password:**
   - The tool will prompt you to enter a password for assessment.

3. **View the assessment:**
   - The tool will evaluate the password and provide feedback on its strength and how to improve it.

## Example

### Running the Password Strength Assessment Tool
```sh
$ python password_strength_tool.py
Enter your password: ExamplePassword123!
Password is strong.
```

### Weak Password Example
```sh
$ python password_strength_tool.py
Enter your password: weakpass
Password should be at least 8 characters long.
Password should contain both uppercase and lowercase letters.
Password should contain at least one digit.
Password should contain at least one special character.
Password is weak.
```

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
