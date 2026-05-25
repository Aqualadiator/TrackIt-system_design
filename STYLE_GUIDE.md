TrackIT Style Guide

2.1 Naming Conventions

| Element | Convention | Example |
|---------|------------|---------|
| Variables | camelCase | taskDeadline |
| Functions / Methods | camelCase | updateTaskProgress() |
| Classes | PascalCase | TaskManager |
| Files | kebab-case | task-management.js |
| Constants | UPPER_CASE | MAX_TASK_LIMIT |
| Database tables / fields | snake_case | task_id |

2.2 Formatting Rules

| Rule | Team Decision |
|------|---------------|
| Indentation | 4 spaces |
| Line length limit | Maximum 100 characters |
| Brace style | Opening brace on same line |
| Spaces vs. tabs | Spaces only |
| Blank lines between functions | 1 blank line |
| Max function length | 30 lines |

2.3 Commenting Standards

| Commenting Rule | Team Standard |
|-----------------|---------------|
| File/module header comment | Include file purpose and author |
| Function/method doc comment | Describe parameters and return values |
| Inline comments (when to use) | Only for complex logic |
| TODO comment format | // TODO: description |
| Language for comments | English |

2.4 Branch Naming Strategy

| Branch Type | Naming Format | Example |
|-------------|---------------|---------|
| Feature branch | feature/<short-description> | feature/task-tracking |
| Bug fix branch | bugfix/<short-description> | bugfix/login-error |
| Hotfix branch | hotfix/<short-description> | hotfix/reminder-issue |
| Release branch | release/<version> | release/v1.0 |

Part 3 — Commit Message Format

Format: `<type>(<scope>): <short description>`

Example: `docs(readme): add project description and team members`

| Type | When to Use | In Use? |
|------|-------------|---------|
| feat | Add new features | ✓ |
| fix | Fix bugs/errors | ✓ |
| docs | Documentation updates | ✓ |
| style | Code formatting changes | ✓ |
| refactor | Improve code structure | ✗ |
| test | Add or update tests | ✗ |
| chore | Maintenance tasks | ✓ |
