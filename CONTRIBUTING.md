# Contributing Guidelines

Thank you for your interest in contributing. To ensure this project remains stable and maintainable, all contributors must follow these strict rules. If your Pull Request (PR) ignores these guidelines, it will be closed without review.

## 1. No Blind Pull Requests
Do not write code and submit a PR without discussing it first. 
* If you want to add a feature, **open an Issue** detailing what you want to build and why it adds value. 
* Wait for approval from a maintainer before writing any code. Unsolicited architectural changes will be rejected.

## 2. Reporting Bugs
If you find a bug, open an Issue and include:
* The exact error message or stack trace.
* The steps required to reproduce the bug consistently.
* The environment you are running (OS, Python version).
Saying "it doesn't work" is not a bug report and will be closed.

## 3. Code Standards
All code must align with the existing architecture. 
* **Formatting:** Code must be formatted according to PEP-8 standards.
* **Linting:** Your code must pass `pylint` with zero critical or major errors before submission.
* **Typing:** Use Python type hints (`typing` module) for all function parameters and return types.

## 4. The PR Process
1. Fork the repository.
2. Create a new branch for your feature (`git checkout -b feature/your-feature-name`).
3. Write your code and ensure it passes all linting rules.
4. Submit the PR with a clear title and a description referencing the original Issue you opened.
