# Your portfolio

**Chat with one of our members in our group chat.**  
[![Gitter](https://badges.gitter.im/Join Chat.svg)](https://gitter.im/wddi?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

**Check out the project documentation**  
- [Project proposal](https://github.com/wddi/website/blob/docs/project-proposal.md)
- [Development Guide](https://github.com/wddi/website/blob/docs/development-guide.md)






# Project proposal

The purpose of this project is to have the Web Designers & Developers Ireland group practice their skills, share and learn about web development and design.

At the beginning we are proposing that the website should be initiated with the simplest technologies, leaving room for more advanced implementation later on.

HTML CSS and JavaScript should be the focus at the beginning and have the website use a simple framework like Bootstrap, Boilerplate or Foundation.

Github should be used to develop and contribute to this project and all tasks will be listed in the issue tracker.

Members can pick a task or will get assigned and can work on that task on their own time with no time limit.

When the project reaches the proposed milestone and we have most tasks done we push for the live version and fix any immediate bugs.

After the push to master we will re-evaluate the project and create a new set of tasks.

Members should choose their team according to their knowledge and interests, developers will mostly work with coding and back-end development and designers will do the front-end work.

This is the proposed website structure:

- Home - (home page)
- Articles - (parent of all web development pages)
- Contact - (contact page)



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
