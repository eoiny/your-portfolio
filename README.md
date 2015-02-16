# Your portfolio

**Check who is online right now and let's have a chat about this project!**  
[![Gitter](https://badges.gitter.im/Join Chat.svg)](https://gitter.im/wddi?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

## What are we going to do exactly?
Let's face the situation very simply: You have a new web developer and you want to show to your future prospects who you are and what services you offer. 
You need:
- Homepage
- References
- About
- Contact

The purpose of this project is to have the Web Designers & Developers Ireland group practice their skills, share and learn about web development and design.

Github should be used to develop and contribute to this project and all tasks will be listed in the issue tracker.

Members can pick a task or will get assigned and can work on that task on their own time with no time limit.

After the push to master we will re-evaluate the project and create a new set of tasks.


# Development Guide

**This document is still under development.**

## Branches

### Master

The `master` branch will contain the latest stable version of the application. **It must not be used for development**.

### Test

The `test` branch is similar to the `master` branch. It is used to test all the new code before release.

### Docs

The `docs` branch contains all documentation files. The preferred file format is **markdown** but other formats can be used if needed. No code must be pushed to this branch unless it is related to the documentation. Anyone can work directly on this branch, there is no need to create a new branch for every update as it is required for the `master` branch.

### Others

Each feature must be developed in its own branch.

## Development cycle

1. Create a new branch to work on.
2. Work on the branch until the code is ready to be pushed.
3. Push the branch to github.
4. Someone who is not the developer of this branch must evaluate/test the code.
  - If the code is working fine it can be merged in the master branch.
  - If the code has any issue it must be reported and the development goes back to item 2.

## Testing

It is desirable that the project have a 100% code coverage. Every new feature or code change is expected to be tested by any automated test tool being used in the project.
