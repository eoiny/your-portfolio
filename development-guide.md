# Development Guide

**This document is still under development.**

## Branches

### Master

The `master` branch have the latest stable version of the application. **It must not be used for development**.

### Test

The `test` branch is similar to the `master` branch. It is used to have all the new code tested before release.

### Docs

The `docs` branch have all documentation files. The prefered file format is **markdown** but other formats can be used if needed. No code must be pushed to this branch unless it is realted to the documentation. Anyone can work directly on this branch, there is no need to create a new branch for every update as it is required for the `master` branch.

### Others

Each feature must be developed in its own branch.

## Development cycle

1. Create a new branch to work on.
2. Work on the branch until the code is ready to be pushed.
3. Push the branch to github.
4. Someone who is not the developer of this branch must evaluate/test the code.
  - If the code is working fine it can be merged in the master branch.
  - If the code have any issue it must be reported and the development goes back to item 2.

## Testing

It is desirable that all project have a 100% code coverage. Every new feature or code change is expected to be tested by any automated test tool being used in the project.