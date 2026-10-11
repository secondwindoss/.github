# Contributing to Second Wind OSS projects

Thank you for helping. These guidelines apply to every repository in the organization that does not have its own `CONTRIBUTING.md`; a repository's own file takes precedence.

## Before you start

- Check the issue tracker of the project for an existing report or discussion.
- For anything larger than a bug fix, open an issue first so the change can be discussed before you spend time on it.

## The compatibility contract

Our forks promise users that their existing code and data keep working:

- Public APIs and import names stay unchanged unless a major version says otherwise.
- Data written by the original project stays readable, and data we write stays readable by the original, until a major version says otherwise.
- The original license and author credits stay in place.

A pull request that breaks one of these needs a very good reason and a major version.

## Pull requests

- Keep each pull request to one logical change, with tests that cover it.
- Add an entry to the changelog under the unreleased section.
- Write a one-sentence commit message that says what the change does.
- CI must pass. The project's README or development guide explains how to run the checks locally.

## Reporting bugs

Include the project version, the Python or Go version, the operating system, and the smallest example that reproduces the problem.
