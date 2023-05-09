# Git hooks demo

## Git hooks used in this demo
- pre-commit
  - avoid commit to main
  - avoid console.log
- commit-msg
  - enforce conventional commits
- post-commit
  - automatic push to current branch


### Conventional commit messages

Format: 
```
  feat: add hat wobble
  ^--^  ^------------^
  |     |
  |     +-> Summary in imperative tense.
  |
  +-------> Type
```

Types:
- `feat`: (new feature for the user, not a new feature for build script)
- `fix`: (bug fix for the user, not a fix to a build script)
- `docs`: (changes to the documentation)
- `style`: (formatting, missing semi colons, etc; no production code change)
- `refactor`: (refactoring production code, eg. renaming a variable)
- `test`: (adding missing tests, refactoring tests; no production code change)
- `chore`: (updating grunt tasks etc; no production code change)
