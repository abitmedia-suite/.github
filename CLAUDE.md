# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Purpose

Organization-level `.github` repository containing GitHub issue/PR templates and contribution guidelines. There is no executable code — no build system, linters, or tests.

## Repository Structure

- `.github/ISSUE_TEMPLATE/` — GitHub-recognized issue templates (these are what GitHub uses)
- `ISSUE_TEMPLATE/` — Duplicate/working copy of templates (exists at repo root)
- Templates are written in Spanish (user stories with Gherkin acceptance criteria)
- All templates use YAML form syntax (not markdown-based templates)

## Working with Templates

- Validate YAML syntax before committing — GitHub silently ignores malformed templates
- Template naming: lowercase with hyphens (e.g., `user-story.yml`)
- YAML files use 2-space indentation
- Issue title convention: `[HU-XXX]` prefix for user stories (Historia de Usuario)
- Templates use the `user-story` label

## Style Rules (from AGENTS.md)

- Markdown: ATX-style headers, lines under 120 chars, `-` for unordered lists
- YAML frontmatter: 2-space indent, lowercase keys, blank line after closing `---`
- Placeholder text uses brackets: `[description]`
- Test templates in a fork before merging
