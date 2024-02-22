# Repository Guidelines

## Naming

-   Repositories should be named in all lowercase with dashes separating words.
    -   Good Example: `discord-bot`
    -   Bad Example: `RocketryBot`
-   Do not include the words "bulldog" or "rocketry" in the repository name; they are already part of the organization name, and so are redundant.
    -   When taken as a whole, the repository name will read as `Bulldog-Rocketry/my-repository-name`

## Contents

-   All repositories should contain a `README.md` file that contains a brief description of the repository's purpose and usage.
-   All repositories should contain a `.gitignore` file that is appropriate for the language and environment used in the repository.
-   Repositories may contain a `.vscode` folder with settings and extensions for Visual Studio Code.
    -   This is not required, but is recommended for consistency and ease of use.
    -   If a `.vscode` folder is included, it should contain:
        -   A `settings.json` file with settings for the repository.
        -   An `extensions.json` file with a list of recommended extensions for the repository.

## Commits

- Commits should be made under your UMD email address and your full name.
  - To change your email configuration, use the following command:
    ```bash
    git config user.email "internetid123@d.umn.edu"
    ```
  - To change your name configuration, use the following command:
      ```bash
      git config user.name "Firstname Lastname"
      ```
