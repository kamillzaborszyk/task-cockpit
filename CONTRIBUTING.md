# Contributing

Task Cockpit 2.0 is in alpha. Please open an issue before large architectural changes.

## Validation checklist

1. Open `app/index.html` locally.
2. Check Dashboard, List, Kanban, and Settings.
3. Test drag-and-drop planning.
4. Test light and dark mode.
5. Check the browser console for errors.
6. Extract the inline script and run `node --check`.
7. Update `CHANGELOG.md` for user-visible changes.

## Commit messages

Use Conventional Commit-style messages, for example:

```text
feat(stats): add seven-day completion trend
fix(planning): clear stale today ordering after due-date change
experiment(outlook): test calendar compose integration
```
