---
name: pi-commit-message
description: Use this skill before a git commit for git commit format.
---

# Git Commit Message Tool / Skill

Commit message format to use when using git commit

## Commit Message Format

Subject line format: `<type>(<scope>): <short description>`

Type options (choose one):

- `fix`: Bug fixes, dependency issues, broken functionality
- `feat`: New features or functionality
- `docs`: Documentation changes
- `refactor`: Code restructuring without behavior changes
- `test`: Test additions or modifications
- `chore`: Maintenance tasks, config updates

Body requirements (MUST include):

- Add a blank line after the subject
- Use bullet points (-) to describe exactly:
     1. What was identified/found
     2. What action was taken
     3. Verification step (tests pass, typecheck succeeds, etc.)

## Important requirements for commit message

- Do not use quotes, instead use backtick "`"
- Wrap file paths in backtick "`"
- If `.git/COMMIT_EDITMSG` was used, clean it up after use.
