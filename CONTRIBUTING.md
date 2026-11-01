# Contributing

This repository is public. Write for the intended audience and avoid including private information. Keep the organization profile concise and accurate.

Check Markdown links and review changes as they will appear on GitHub. Use clear, concise commit and pull request titles.

## Issue templates

Shared issue templates live in `.github/ISSUE_TEMPLATE`. Keep them concise and consistent with Ready, Set, Go.

With GitHub CLI, choose a template by name, for example:

```sh
gh issue create --template "Workstream" --editor
```

The CLI does not select Workstream by default; omit `--template` for a blank issue or choose another template by name.

For connected work, use `gh issue create --parent` to create a sub-issue, and `gh issue edit --add-blocked-by` to record an actual blocking dependency. A sub-issue relationship alone does not create a dependency.

## Pull request template

The shared pull request template covers the change, its checks, and related work. Link shipping issues without closing keywords when shipping continues after the pull request is merged.
