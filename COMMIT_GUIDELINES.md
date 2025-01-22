# Commit Message Conventions

A concise guide to writing clear and consistent commit messages.

---

## Why Commit Message Conventions?
- Improve collaboration and readability.
- Facilitate debugging and tracking changes.
- Enable automation tools to parse commit messages.

---

## Commit Message Structure

### Standard Format
```
<type>(<scope>): <short description>

<optional detailed description>

<optional footer>
```

### Example
```
feat(auth): add user login functionality

Implemented user login using JWT. Updated tests and documentation.

BREAKING CHANGE: Updated authentication endpoint.
```

---

## Common Types

- **feat:** A new feature.
  - Example: `feat(ui): add dark mode toggle`
- **fix:** A bug fix.
  - Example: `fix(auth): resolve login issue`
- **docs:** Documentation changes only.
  - Example: `docs(readme): update installation instructions`
- **style:** Changes to formatting or code style (no logic changes).
  - Example: `style(css): format header styles`
- **refactor:** Code restructuring without changing behavior.
  - Example: `refactor(api): simplify request handler`
- **test:** Adding or updating tests.
  - Example: `test(user): add tests for profile update`
- **chore:** Maintenance tasks (e.g., updating dependencies).
  - Example: `chore(deps): bump axios to 0.21.2`

---

## Best Practices
- **Use [imperative mood](https://en.wikipedia.org/wiki/Imperative_mood):** Write messages as commands (e.g., "Add" instead of "Added").
- **Keep descriptions short:** Limit the first line to 50 characters.
- **Add details:** Use the body for context if necessary.
- **[Reference issues](https://docs.github.com/en/issues/tracking-your-work-with-issues/using-issues/linking-a-pull-request-to-an-issue#linking-a-pull-request-to-an-issue-using-a-keyword):** Mention related tickets (e.g., `Fixes #123`).

---

## Example Workflow
1. **Write commits for logical changes:**
   - Bad: `fix all bugs`
   - Good: `fix(auth): resolve token expiration issue`

2. **Use tools like `commitlint` or `Better Commit` to enforce standards.**

3. **Automate changelogs using conventional commits.**

---

Use clear commit messages to make your codebase more maintainable and collaborative!

