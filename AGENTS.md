# Instructions for Codex

## Workflow
- Never push directly to main.
- Always create a separate branch for changes.
- Always open a pull request.
- Keep changes small and focused.
- Do not modify unrelated files.
- Do not change deployment configuration unless explicitly asked.

## Code quality
- Follow the existing project structure and naming conventions.
- Add or update tests when behavior changes.
- Run lint, tests, and build before marking the task as complete.
- Explain what was changed and why in the pull request description.

## Safety
- Do not commit secrets, tokens, API keys, or private credentials.
- Do not edit production environment variables.
- Do not remove existing validation, auth, or permission checks without explicit approval.

## Pull request format
Include:
1. Summary
2. What changed
3. How it was tested
4. Risks / notes
