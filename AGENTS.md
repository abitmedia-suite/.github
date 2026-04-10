# AGENTS.md - .github Repository

## Overview

This is the organization's central configuration repository. It contains GitHub templates (issues, pull requests) and contribution guidelines. There is no executable code in this repository.

## Build/Lint/Test Commands

Not applicable - this repository contains only markdown templates and configuration files. No build system, linters, or tests are configured.

If adding new template files:
- Validate YAML/JSON syntax where applicable
- Ensure markdown files have correct syntax

## Repository Structure

```
.github/
├── README.md                 # This file
├── ISSUE_TEMPLATE/           # GitHub issue templates
├── PULL_REQUEST_TEMPLATE/   # PR templates
└── CONTRIBUTING.md          # Contribution guidelines
```

## Code Style Guidelines

### General Principles

- Keep templates simple and clear
- Use consistent formatting within each template type
- Include helpful instructions and examples
- Use placeholder text marked with brackets (e.g., `[description]`)
- Use inclusive, welcoming language
- Avoid assuming technical expertise - err on the side of clarity
- Structure templates with logical sections using headers

### Markdown Guidelines

- Use ATX-style headers (`#`, `##`, `###`)
- Use bullet lists for checklists and options
- Use numbered lists for sequential steps
- Use code blocks with language tags for examples
- Keep lines under 120 characters when practical
- Use bold for emphasis on key terms
- Use horizontal rules (`---`) to separate major sections

### Template Naming

- Use lowercase with hyphens: `bug-report.md`
- Prefix issue templates with category: `bug-`, `feature-`, `question-`
- PR templates: `PULL_REQUEST_TEMPLATE.md` or categorized

### YAML Frontmatter

- Always use 2-space indentation
- Include a blank line after closing `---`
- Use lowercase for all keys
- Validate YAML syntax before committing

### YAML/JSON Files

- Use 2-space indentation
- Include trailing newline on all files
- Validate syntax before committing

### Issue Template Guidelines

- Clear title describing the issue type
- Brief description of the problem or feature
- Steps to reproduce (for bugs)
- Expected behavior vs actual behavior
- Environment information (OS, version, etc.)
- Suggested labels: `bug`, `feature`, `question`, `documentation`, `help wanted`

### PR Template Guidelines

- Description of changes and why they were made
- Related issue numbers (e.g., "Closes #123")
- Testing performed
- Summary section with bullet points

### GitHub-Specific

- Use GitHub Flavored Markdown features
- Reference related issues using `#issue-number`
- Include checklist items for common actions
- Add labels where appropriate

### Formatting Rules

- Use `-` for unordered lists, `1.` for ordered lists
- Indent nested lists with 2 spaces
- Use `-` [ ] for checklist items
- Use triple backticks with language tag for code blocks
- Use descriptive link text, place links nearest to relevant content

### Common Pitfalls to Avoid

- Making templates too complex or lengthy
- Requiring too much information upfront
- Using inconsistent naming conventions
- Not validating YAML/JSON syntax
- Using outdated markdown syntax

### Testing Templates

Before committing new templates:
1. Test in a forked repository or sandbox
2. Verify all links work correctly
3. Validate YAML/JSON frontmatter if present

## Notes for Agents

- This repository is for configuration/templates only
- No development workflow applies here
- When improving templates, consider the user experience
- Changes to templates may require testing in a fork
- Keep templates lightweight and focused
- Back up existing templates before making changes

## Workflow for Changes

1. Make incremental changes
2. Test templates in a sandbox environment
3. Verify syntax is valid
4. Submit changes with clear descriptions
