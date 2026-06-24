<!-- METADATA -->

```yaml
task: Compact studio and improve form behavior
status: done
priority: 20
dep: ["work/001-refactor-command-center-studio-layout/001-rebuild-project-command-ribbon.md"]
assignee: ""
requiresHumanReview: false
expiresAt: null
```

<!-- DESCRIPTION -->

Reduce unnecessary panel whitespace, move Surprise Me beside or below concept generation, format phone values with an area code, conditionally expose race-car-specific inputs, and preselect mockup views based on wrap type.

<!-- ACCEPTANCE -->

## Acceptance criteria

- [x] Studio columns and panels do not create excessive empty vertical space.
- [x] Surprise Me is grouped with the primary generation controls.
- [x] Phone input expects and displays a ten-digit number including area code.
- [x] Race-car-only controls are hidden unless the selected goal is Race car wrap.
- [x] Required mockup views receive sensible defaults from the project wrap type.
