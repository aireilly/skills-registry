---
title: eval-check
---

<!-- Auto-generated from registry.yaml. Do not edit directly. -->


# eval-check

Full-harness configuration health check. Scans all skills, commands,
CLAUDE.md, and hooks as a single system and produces an informational
report with findings across five categories: content overlap (duplicated
rules between skills), trigger overlap (descriptions that activate for the
same tasks), CLAUDE.md duplication (rules already in CLAUDE.md that are
restated in skills), type misclassification (skills that should be hooks,
commands, or CLAUDE.md rules), and structural issues (missing descriptions,
overly broad triggers). Read-only — does not modify any files. Skips
cross-component analysis for single-skill projects.

**Plugin**: [agent-eval-harness](index.md) | **:material-check: User-invocable**

## Arguments

```bash
/eval-check [--output <path>] [--include-global]
```

| Argument | Required | Default | Description |
|----------|----------|---------|-------------|
| `--output` |  | `harness-report.md` | Where to write the health check report. |
| `--include-global` |  | `false` | Also scan ~/.claude/CLAUDE.md (user-global config). Opt-in for privacy. |

## Usage

```bash
/eval-check
/eval-check --include-global
/eval-check --output eval/health-report.md
```
