# Repository Guidelines

## Table of Contents

-   [Repository Guidelines](#repository-guidelines)
    -   [Table of Contents](#table-of-contents)
    -   [Metadata](#metadata)
        -   [Repository Name](#repository-name)
        -   [Repository Description](#repository-description)
    -   [Contents](#contents)
    -   [Branches](#branches)
    -   [Contributing](#contributing)

## Metadata

### Repository Name

-   Repositories should be named in all lowercase with dashes separating words.
    -   Good Example: `discord-bot`
    -   Bad Example: `RocketryBot`
-   Do not include the words "bulldog" or "rocketry" in the repository name; they are already part of the organization name, and so are redundant.
    -   When taken as a whole, the repository name will read as `Bulldog-Rocketry/my-repository-name`

### Repository Description

-   Repositories should contain a brief description of the repository's purpose and usage.
    -   This should be included in the `README.md` file.
    -   This should also be included in the repository's description on GitHub.

## Contents

-   All repositories should contain a `README.md` file that contains a brief description of the repository's purpose and usage.
-   All repositories should contain a `.gitignore` file that is appropriate for the language and environment used in the repository.
-   Repositories may contain a `.vscode` folder with settings and extensions for Visual Studio Code.
    -   This is not required, but is recommended for consistency and ease of use.
    -   If a `.vscode` folder is included, it should contain:
        -   A `settings.json` file with settings for the repository.
        -   An `extensions.json` file with a list of recommended extensions for the repository.

## Branches

-   The default branch for all repositories should be `main` or `prod`, whichever makes more sense for the project.
-   There should be a `dev` branch that is used for development work.
-   Feature branches should be created off of the `dev` branch, and pull requests should be made back to the `dev` branch.

## Contributing

See [Contributing Guidelines](contributing.md)
