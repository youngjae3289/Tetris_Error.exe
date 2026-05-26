# AGENTS.md

## Project Context

- This project is an assignment-purpose HTML game.
- `main.html` is the main executable game file.
- `balance_editor.html` is a helper/editor file for tuning and reference.
- `Resources` is the game resource folder.

## Git Rules

- Git is managed through GitHub Desktop.
- Do not run `git init`, `git commit`, or `git push` directly.

## Editing Rules

- Do not delete or rename existing files.
- Do not rewrite the entire codebase at once.
- Make changes in small, understandable units.
- After making changes, explain which files were modified and why.

## Test Rules

- Use `main.html` as the primary execution target.
- For local server testing, use:

```bash
python3 -m http.server 8000
```

- Then open:

```text
http://localhost:8000/main.html
```
