# Coding Standards

## Purpose

This document outlines the coding standards and best practices for ClearFracture projects. Following these standards ensures consistency, maintainability, and quality across our codebase.

## General Principles

* Write clear, readable, and maintainable code
* Follow the principle of least surprise
* Keep it simple - avoid over-engineering
* Document complex logic and non-obvious decisions
* Write code for humans first, computers second

## Code Quality

### Code Structure

* Keep functions and methods focused on a single responsibility
* Limit function length to what can be understood at a glance (typically under 50 lines)
* Use meaningful and descriptive names for variables, functions, and classes
* Avoid deep nesting - prefer early returns and guard clauses
* Keep files organized and appropriately sized

### Documentation

* Add comments to explain "why", not "what" (code should be self-documenting for "what")
* Document all public APIs, including parameters, return values, and exceptions
* Keep documentation up-to-date with code changes
* Include examples for complex functionality
* Use clear and concise language

### Version Control

* Write clear, descriptive commit messages
* Keep commits atomic and focused on a single change
* Reference issue/ticket numbers in commit messages when applicable
* Review your own changes before creating a pull request
* Ensure code is properly tested before committing

## Code Review Standards

### Submitting Code for Review

* Ensure all tests pass before requesting review
* Provide context and explanation in the pull request description
* Keep pull requests focused and reasonably sized
* Respond promptly to review feedback
* Be open to suggestions and alternative approaches

### Reviewing Code

* Be constructive and respectful in feedback
* Focus on the code, not the person
* Explain the reasoning behind suggestions
* Approve changes that improve the codebase, even if not perfect
* Recognize good work and clever solutions

## Testing

* Write tests for new functionality
* Maintain or improve test coverage with changes
* Ensure tests are reliable and not flaky
* Write clear test names that describe what is being tested
* Include both positive and negative test cases

## Security

* Never commit secrets, credentials, or sensitive data
* Validate and sanitize all user inputs
* Follow security best practices for the language and framework
* Keep dependencies up-to-date
* Report security vulnerabilities responsibly

## Performance

* Consider performance implications of code changes
* Avoid premature optimization
* Profile and measure before optimizing
* Document performance-critical sections

## Consistency

* Follow existing code style and patterns in the project
* Use language-specific style guides and linters
* Maintain consistency within a file and across the project
* When in doubt, discuss with the team before deviating from established patterns
