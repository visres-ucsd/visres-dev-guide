# Vision Research - Development Guide

The purpose of this repository is to document a set of agreed-upon development practices that individuals and teams should use when writing code as part of UCSD vision research.

## How this is being made

This guide will be developed by collaborative effort over time. Anyone involved with Vision Research using code is encouraged to contribute to this document, by submitting feedback and questions as GitHub issues (or contributions by making pull requests).

It is acknowledged that the goal in our research context is generally not to produce production-ready, evergreen code for large teams, in the way it might be for industry software teams. Suggestions made here should therefore be restricted to high-yield practices that will noticeably increase productivity of small research teams/individuals, and allow code that is more reliable and reproducible.

## General Principles

Researchers should follow these general principles for all code-writing activities:

1. Continue to learn and employ [clean code](#writing-good-code) practices.
2. Use [code reviews](#code-review) for all code with published results.
3. Use [version control](#version-control) for each distinct project.

## Details

### Writing good code

This is a large topic, and the advice useful to a given individual will depend on their experience. The key personal check for everyone, therefore, is simply that the aim of writing clean code is kept in-mind whenever you are writing.

Some high-level tips for writing easy-to-read code are given [here](/guides/high-yield-code-quality-advice.MD). For more extensive projects, please also refer to the UCSD [style guide](/guides/general-style-guide.MD).

### Code review

Having someone else look through your code has many benefits, namely:

- **Improving code quality**: reviewer can pick up errors, and improve convoluted code that's more likely to cause errors.
- **Learning**: reviews allow us to share knowledge and skills that can improve everyone's work.
- **Easier collaboration**: reviews allow us to gain familiarity with the work of colleagues, making it easier to subsequently collaborate on projects.

In addition, the knowledge that someone will review your code may have the tendency to make you write better, more readable code in the first place!

### Version control

Version control software allows us to keep a history of changes for a set of files, and perform related actions such as compare versions. More information can be found [here](https://www.geeksforgeeks.org/version-control-systems/).

Code for specific studies within the Shiley Eye Institute should have its own repository, as should reused code. However, careful attention should be paid to security: please read [this guide](/guides/security-in-git-repos.MD) before initializing a new repo.

## Contributing to this guide

This is an ongoing effort. Anyone involved, or beginning to get involved, with coding in the Shiley Eye Institute should feel welcome to contribute. Questions or suggestions should be made through the issues tab in this GitHub repo, or by submitting a pull request.
