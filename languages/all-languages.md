# All-Language Guidelines

## Table of Contents

-   [All-Language Guidelines](#all-language-guidelines)
    -   [Table of Contents](#table-of-contents)
    -   [Formatting](#formatting)
    -   [Documentation](#documentation)
    -   [Testing](#testing)

These guidelines apply to all Bulldog Rocketry projects, regardless of language or environment.

## Formatting

-   Code must use a consistent format, as defined by the language's standard formatting tool.
-   There should be repository-level configuration files for the formatting tool.
    -   Examples: `.prettierrc`, `pyproject.toml`, `.clang-format`, etc.
-   This also includes sorting top-level dependency imports.

## Documentation

-   All functions, classes, and modules must be documented in a method appropriate for that language.
-   Additionally, use comments in your code to explain complex or non-obvious sections of code.

## Testing

-   All code should be tested.
-   There should exist both unit tests and end-to-end tests.
-   Test coverage should be measured and reported.
