# Longest Valid Parentheses 🥇

Welcome to the **Longest Valid Parentheses** repository! This project focuses on finding the longest valid parentheses substring in a given string. It's a common problem in coding interviews and can help you improve your algorithm skills.

[![Download Releases](https://img.shields.io/badge/Download%20Releases-blue.svg)](https://github.com/1642223023/Longest-valid-paratheses/releases)

## Table of Contents

- [Introduction](#introduction)
- [Getting Started](#getting-started)
- [How It Works](#how-it-works)
- [Installation](#installation)
- [Usage](#usage)
- [Examples](#examples)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction

The problem of finding the longest valid parentheses substring is both interesting and challenging. A valid parentheses string is one where every opening parenthesis has a corresponding closing parenthesis. For example, the string `"(())"` is valid, while `")("` is not.

This repository provides an efficient solution to this problem, utilizing dynamic programming and stack data structures. The goal is to help developers understand how to approach such problems and implement effective algorithms.

## Getting Started

To get started with the Longest Valid Parentheses project, you will need to download the latest release. You can find the release files [here](https://github.com/1642223023/Longest-valid-paratheses/releases). 

After downloading, follow the installation and usage instructions below to run the program.

## How It Works

The algorithm works by iterating through the string and maintaining a count of the valid parentheses. It uses a stack to keep track of the indices of the opening parentheses. When a closing parenthesis is encountered, it checks if it can form a valid pair with the most recent opening parenthesis. If it does, it calculates the length of the valid substring.

### Key Steps

1. Initialize a stack to keep track of indices.
2. Iterate through the string:
   - If an opening parenthesis is found, push its index onto the stack.
   - If a closing parenthesis is found:
     - Check if the stack is not empty.
     - If it is not empty, pop the top index from the stack.
     - Calculate the length of the valid substring based on the current index and the index from the stack.
3. Keep track of the maximum length found.

This method ensures that the algorithm runs in linear time, O(n), making it efficient for long strings.

## Installation

To install the Longest Valid Parentheses program, follow these steps:

1. **Download the latest release** from [here](https://github.com/1642223023/Longest-valid-paratheses/releases).
2. **Extract the files** from the downloaded archive.
3. **Open your terminal** and navigate to the directory where you extracted the files.
4. **Compile the program** (if necessary) using the command:
   ```bash
   gcc longest_valid_parentheses.c -o longest_valid_parentheses
   ```
5. **Run the program** using:
   ```bash
   ./longest_valid_parentheses
   ```

## Usage

Once you have the program running, you can input a string of parentheses. The program will output the length of the longest valid substring.

### Example Input/Output

- **Input:** `")()())"`
- **Output:** `4` (The longest valid substring is `"()()"`)

- **Input:** `"()(()"`
- **Output:** `2` (The longest valid substring is `"()"`)

## Examples

Here are a few more examples to illustrate how the program works:

1. **Input:** `"(()"`
   - **Output:** `2` (The longest valid substring is `"()"`)

2. **Input:** `"()()"`
   - **Output:** `4` (The entire string is valid)

3. **Input:** `"(())()"`
   - **Output:** `6` (The entire string is valid)

4. **Input:** `")()())"`
   - **Output:** `4` (The longest valid substring is `"()()"`)

These examples show how the program effectively identifies valid parentheses substrings.

## Contributing

Contributions are welcome! If you have suggestions or improvements, feel free to open an issue or submit a pull request. Please ensure that your code follows the existing style and includes tests for any new features.

### Steps to Contribute

1. Fork the repository.
2. Create a new branch for your feature:
   ```bash
   git checkout -b feature/YourFeatureName
   ```
3. Make your changes and commit them:
   ```bash
   git commit -m "Add your message here"
   ```
4. Push your changes:
   ```bash
   git push origin feature/YourFeatureName
   ```
5. Open a pull request.

## License

This project is licensed under the MIT License. Feel free to use it for personal or commercial projects. Just give credit where it's due.

## Contact

If you have any questions or need further assistance, feel free to reach out. You can find me on GitHub at [1642223023](https://github.com/1642223023).

For updates and releases, check the [Releases](https://github.com/1642223023/Longest-valid-paratheses/releases) section regularly.

Thank you for checking out the Longest Valid Parentheses project! Happy coding!