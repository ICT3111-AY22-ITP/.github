# Guide

## Branches

### Main Branch

This is the main branch of the repository.

- Never commit directly to this branch
- Pull Requests from `develop` branch to be merged to this branch

### Develop Branch

This branch will consists all commits from all branches created for development.

- Pull Requests to be created to merge the codes to this branch

### Feature Branch

All features should be created as a feature branch.

- Branches will branch off from `develop` branch instead of `main`
- Branch to be named as
  > - `feat/<server/client>/<feature-name>`
  > - example `feat/api/dashboard` or `feat/client/dashboard`

## Commit Messages

- `feat` - new feature
- `fix` - a bug fix
- `refactor` - changes that is not related to feature or fix
- `style` - changes that does not affect the codes, related to code formatting
- `test` - including new or correcting previous tests

## References

Commit Messages are adapted from FreeCodeCamp  
[https://www.freecodecamp.org/news/how-to-write-better-git-commit-messages/]
