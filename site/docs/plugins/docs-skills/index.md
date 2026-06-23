---
title: docs-skills
---

<!-- Auto-generated from registry.yaml. Do not edit directly. -->


# docs-skills

Documentation review, writing, and workflow tools for AsciiDoc and Markdown documentation. Includes an orchestrated multi-step pipeline (requirements, planning, writing, review, quality gates), standalone review skills (style guide, technical, modular docs, security), codebase analysis for onboarding, JIRA and PR/MR integration, IBM Style Guide and Red Hat SSG sub-skills, and Google Docs conversion.

!!! info "Plugin Details"

    - **Version**: 0.3.0
    - **Author**: opendatahub-io
    - **License**: Apache-2.0
    - **Category**: [Documentation](../../categories/documentation.md)
    - **Repository**: [opendatahub-io/docs-skills](https://github.com/opendatahub-io/docs-skills)
    - **Tags**: <span class="tag-pill">documentation</span> <span class="tag-pill">asciidoc</span> <span class="tag-pill">mkdocs</span> <span class="tag-pill">workflow</span> <span class="tag-pill">review</span> <span class="tag-pill">style-guide</span> <span class="tag-pill">jira</span> <span class="tag-pill">onboarding</span> <span class="tag-pill">code-analysis</span>

## Skills

| Skill | Description | Invocable |
|-------|-------------|-----------|
| [`/docs-orchestrator`](docs-orchestrator.md) | Documentation workflow orchestrator — reads step list from YAML, runs steps sequentially with progress tracking, iteration loops, and confirmation gates | :material-check: |
| [`/docs-workflow-start`](docs-workflow-start.md) | Interactive guided setup for the docs workflow with auto-resolved prerequisites and resume support | :material-check: |
| [`/learn-code`](learn-code.md) | Analyze a codebase for engineer onboarding — detects language, maps modules, analyzes in parallel, produces ONBOARDING.md | :material-check: |
| [`/query-code`](query-code.md) | Query an analyzed codebase via the code-questioner agent | :material-check: |
| [`/understand-pull-request`](understand-pull-request.md) | PR/MR impact analysis with module-level code understanding | :material-check: |
| [`/docs-review-style`](docs-review-style.md) | Multi-agent style guide and modular docs review with confidence scoring, PR/MR inline comment posting, and fix mode | :material-check: |
| [`/docs-review-technical`](docs-review-technical.md) | Code-aware technical accuracy review of documentation | :material-check: |
| [`/docs-review-content-quality`](docs-review-content-quality.md) | Content quality assessment for documentation | :material-check: |
| [`/docs-review-modular-docs`](docs-review-modular-docs.md) | Modular documentation structure compliance review | :material-check: |
| [`/docs-review-security`](docs-review-security.md) | Security and PII review for documentation content | :material-check: |
| [`/jira-reader`](jira-reader.md) | Read and analyze JIRA issues — fetch details, search, extract comments, traverse ticket graphs, generate summaries | :material-check: |
| [`/jira-writer`](jira-writer.md) | Create JIRA issues on Red Hat Issue Tracker | :material-check: |
| [`/git-pr-reader`](git-pr-reader.md) | GitHub/GitLab PR/MR interaction and analysis | :material-check: |
| [`/article-extractor`](article-extractor.md) | Extract web content for documentation reference | :material-check: |
| [`/docs-convert-gdoc-md`](docs-convert-gdoc-md.md) | Convert Google Docs to Markdown format | :material-check: |
| [`/redhat-docs-toc`](redhat-docs-toc.md) | Generate Red Hat documentation table of contents | :material-check: |
| [`/action-comments`](action-comments.md) | Post review comments to PR/MR as inline annotations | :material-check: |
| [`/rn-known-issues`](rn-known-issues.md) | Release notes known issues audit | :material-check: |
| [`/docs-redhat-case-search`](docs-redhat-case-search.md) | Search Red Hat support cases for documentation context | :material-check: |
| [`/docs-workflow-requirements`](docs-workflow-requirements.md) | Requirements discovery and analysis step | :material-close: internal |
| [`/docs-workflow-planning`](docs-workflow-planning.md) | Documentation planning step using JTBD framework | :material-close: internal |
| [`/docs-workflow-writing`](docs-workflow-writing.md) | Documentation writing step — dispatches docs-writer agent | :material-close: internal |
| [`/docs-workflow-code-analysis`](docs-workflow-code-analysis.md) | Source code analysis step for technical context | :material-close: internal |
| [`/docs-workflow-pr-analysis`](docs-workflow-pr-analysis.md) | PR/MR change analysis step | :material-close: internal |
| [`/docs-workflow-scope-req-audit`](docs-workflow-scope-req-audit.md) | Scope and requirements audit step | :material-close: internal |
| [`/docs-workflow-style-review`](docs-workflow-style-review.md) | Style review step within the orchestrated pipeline | :material-close: internal |
| [`/docs-workflow-tech-review`](docs-workflow-tech-review.md) | Technical review step with iteration support | :material-close: internal |
| [`/docs-workflow-quality-gate`](docs-workflow-quality-gate.md) | Quality gate step with iteration for intent alignment | :material-close: internal |
| [`/docs-workflow-pipeline-diagnostics`](docs-workflow-pipeline-diagnostics.md) | Pipeline diagnostics and self-introspection step | :material-close: internal |
| [`/docs-workflow-security-review`](docs-workflow-security-review.md) | Security review step within the orchestrated pipeline | :material-close: internal |
| [`/docs-workflow-create-jira`](docs-workflow-create-jira.md) | Create JIRA ticket step (conditional on --create-jira flag) | :material-close: internal |
| [`/docs-workflow-create-merge-request`](docs-workflow-create-merge-request.md) | Create merge request step (conditional on --create-merge-request flag) | :material-close: internal |
| [`/docs-workflow-jira-ready`](docs-workflow-jira-ready.md) | JIRA readiness validation step | :material-close: internal |
| [`/ibm-sg-audience-and-medium`](ibm-sg-audience-and-medium.md) | IBM Style Guide audience and medium review | :material-close: internal |
| [`/ibm-sg-language-and-grammar`](ibm-sg-language-and-grammar.md) | IBM Style Guide language and grammar review | :material-close: internal |
| [`/ibm-sg-legal-information`](ibm-sg-legal-information.md) | IBM Style Guide legal information review | :material-close: internal |
| [`/ibm-sg-numbers-and-measurement`](ibm-sg-numbers-and-measurement.md) | IBM Style Guide numbers and measurement review | :material-close: internal |
| [`/ibm-sg-punctuation`](ibm-sg-punctuation.md) | IBM Style Guide punctuation review | :material-close: internal |
| [`/ibm-sg-references`](ibm-sg-references.md) | IBM Style Guide references review | :material-close: internal |
| [`/ibm-sg-structure-and-format`](ibm-sg-structure-and-format.md) | IBM Style Guide structure and format review | :material-close: internal |
| [`/ibm-sg-technical-elements`](ibm-sg-technical-elements.md) | IBM Style Guide technical elements review | :material-close: internal |
| [`/rh-ssg-accessibility`](rh-ssg-accessibility.md) | Red Hat SSG accessibility review | :material-close: internal |
| [`/rh-ssg-formatting`](rh-ssg-formatting.md) | Red Hat SSG formatting compliance review | :material-close: internal |
| [`/rh-ssg-grammar-and-language`](rh-ssg-grammar-and-language.md) | Red Hat SSG grammar and language review | :material-close: internal |
| [`/rh-ssg-gui-and-links`](rh-ssg-gui-and-links.md) | Red Hat SSG GUI and links review | :material-close: internal |
| [`/rh-ssg-legal-and-support`](rh-ssg-legal-and-support.md) | Red Hat SSG legal and support content review | :material-close: internal |
| [`/rh-ssg-release-notes`](rh-ssg-release-notes.md) | Red Hat SSG release notes review | :material-close: internal |
| [`/rh-ssg-structure`](rh-ssg-structure.md) | Red Hat SSG structure review | :material-close: internal |
| [`/rh-ssg-technical-examples`](rh-ssg-technical-examples.md) | Red Hat SSG technical examples review | :material-close: internal |

## Agents

| Agent | Description |
|-------|-------------|
| docs-planner | Documentation architecture using JTBD framework |
| docs-writer | Content creation for modular documentation modules |
| docs-reviewer | Style and modular docs compliance review |
| technical-reviewer | Technical accuracy review with code-aware validation |
| repo-mapper | Codebase module detection and registry creation |
| module-analyzer | Deep analysis of single codebase module |
| relationship-analyzer | Cross-module coupling and dependency analysis |
| synthesis-writer | Combines module analyses into ONBOARDING.md |
| code-questioner | Answer questions about analyzed codebases |
| requirements-discoverer | Lightweight JIRA/PR/spec requirement enumeration |
| requirements-analyst | Deep per-requirement analysis with acceptance criteria |
| requirement-classifier | Classify requirements by code evidence status |
| pr-repo-summarizer | Quick repository overview for PR context |
| pr-change-analyzer | Analyze PR changes against module registry |
| pr-synthesis-writer | Combine PR data into PR-ANALYSIS.md |

## Installation

```bash
/plugin install docs-skills@opendatahub-skills
```
