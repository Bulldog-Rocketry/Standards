# Contributing Guidelines

## Table of Contents

-   [Contributing Guidelines](#contributing-guidelines)
    -   [Table of Contents](#table-of-contents)
    -   [Overview](#overview)
    -   [Commits](#commits)
    -   [Pull Requests](#pull-requests)

## Overview

This document outlines the guidelines for contributing to Bulldog Rocketry repositories. These guidelines are intended to ensure consistency and quality across all repositories. Please read this document carefully before contributing to any repository.

## Commits

-   Commits should be made under your UMD email address and your full name.
    -   To change your email configuration, use the following command:
        ```bash
        git config user.email "internetid123@d.umn.edu"
        ```
    -   To change your name configuration, use the following command:
        ```bash
        git config user.name "Firstname Lastname"
        ```
-   Commit messages should be clear, concise, and descriptive of all the changes made.
-   Commit messages should be in the present tense.
    -   Good Example: `Add new feature`
    -   Bad Example: `Added new feature`

## Pull Requests

-   Pull requests should be made from a fork of the repository.
-   When submitting a pull request, commits within should be squashed into as few commits as makes sense. This helps keep the commit history clean and easy to read. To squash commits, use the following command:
    ```bash
    # origin/dev refers to the upstream version of the dev branch. If you don't have a dev branch, replace `dev` with the branch you're merging into, such as `main` or `prod`.
    git rebase -i origin/dev
    ```
    This will open an interactive rebase window where you can squash commits together. For more information on squashing commits, see [this guide](https://www.internalpointers.com/post/squash-commits-into-one-git).
-   The rebase operation described above also ensures that you won't meet any conflicts with the dev branch when merging your pull request. If you do encounter conflicts, resolve them locally with another rebase and push the changes to your fork. GitHub will automatically update the pull request with the new changes.
