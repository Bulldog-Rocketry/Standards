# Javascript Guidelines

## Table of Contents

-   [Javascript Guidelines](#javascript-guidelines)
    -   [Table of Contents](#table-of-contents)
    -   [Dependencies](#dependencies)
    -   [Formatting](#formatting)
    -   [Documentation](#documentation)
    -   [Testing](#testing)

## Dependencies

-   Use `yarn` or `npm` to manage dependencies.
-   The `node_modules` directory should be ignored in the `.gitignore` file.
-   The `package.json` and/or `yarn.lock` file(s) should be included in the repository.

## Formatting

-   Use `Prettier` to format your code.
-   When using TypeScript, use a Prettier plugin such as [`@trivago/prettier-plugin-sort-imports`](https://github.com/trivago/prettier-plugin-sort-imports) or VSC's `TypeScript: Sort Imports` command.
-   Prettier can be configured with a `.prettierrc` - [example](examples/javascript/.prettierrc)

## Documentation

-   Use comments/JSdoc to document your code.

## Testing

-   Use a program like `Jest` to write and run tests for your code.
-   You can also measure coverage with `Jest` to see how well you have written your tests.
