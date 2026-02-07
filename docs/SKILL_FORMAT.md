# Skill Format Specification

Every skill in this marketplace follows a consistent format for compatibility with Claude Code, Cursor, and other AI coding agents.

## Folder Structure

```
skills/category/skill-name/
├── SKILL.md          # Required — core skill definition
├── README.md         # Required — documentation and examples
├── examples/         # Recommended — input/output examples
│   ├── example-1.md
│   └── example-2.md
└── references/       # Optional — frameworks, templates, source material
    ├── framework.md
    └── template.md
```

## SKILL.md Format

### YAML Frontmatter (Required)

```yaml
---
name: skill-name              # Lowercase, kebab-case
version: 1.0.0                # Semantic versioning
category: Category Name        # Human-readable category
domain: specific-domain        # Lowercase, kebab-case
author: Your Name
license: MIT
status: production             # production | development | experimental
updated: 2026-02-07           # ISO date
activation_triggers:           # Phrases that should activate this skill
  - "trigger phrase one"
  - "trigger phrase two"
  - "trigger phrase three"
tools: []                      # Python CLI tools if any
---
```

### Body Sections

```markdown
# Skill Name

One-line description of what this skill does.

## Purpose

2-3 sentences explaining the problem this skill solves and who it's for.

## Workflow

### Step 1: Gather Context
What information to collect from the user before starting.

### Step 2: Apply Framework
The core methodology or framework this skill uses.

### Step 3: Generate Output
What the skill produces and in what format.

### Step 4: Refine
How to iterate on the output based on feedback.

## Frameworks

Reference any named frameworks (e.g., PAS, AIDA, Eisenhower Matrix).
Include brief descriptions so the agent understands the framework without external references.

## Output Format

Describe the expected structure of the skill's output.

## Constraints

- What this skill should NOT do
- Boundaries and limitations
- Quality standards
```

## README.md Format

```markdown
# Skill Name

Brief description.

## What It Does

Paragraph explaining the skill's purpose and approach.

## Usage

How to invoke the skill (example prompts).

## Example

### Input
What the user provides.

### Output
What the skill produces (abbreviated).

## Frameworks Used

List of methodologies this skill applies.
```

## Naming Conventions

- **Folder names:** lowercase, kebab-case (`cold-outreach`, not `ColdOutreach`)
- **Category folders:** lowercase, kebab-case (`marketing-growth`)
- **File names:** UPPERCASE for top-level docs (`SKILL.md`, `README.md`)
- **Example files:** lowercase, descriptive (`saas-cold-email.md`)

## Versioning

Use semantic versioning:
- **1.0.0** — Production-ready, tested
- **0.x.x** — Development, may change
- Increment **patch** for fixes, **minor** for additions, **major** for breaking changes
