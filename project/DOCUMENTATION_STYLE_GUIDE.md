# 📚 Documentation Style Guide

## Purpose

This document defines the documentation standards for the **GnuCash Persian** project.

The goal is to ensure every document follows a consistent structure, writing style, and visual identity.

Documentation should feel like it was written by one team, even if hundreds of contributors participate.

---

## Principles

Documentation should always be:

- Clear
- Accurate
- Beginner Friendly
- Professional
- Maintainable
- Searchable
- Consistent

When in doubt, prefer simplicity over complexity.

---

## Languages

The project supports two primary languages.

| Language | Directory |
|----------|-----------|
| Persian | docs/fa |
| English | docs/en |

Documentation in both languages should follow the same structure whenever possible.

---

## Document Structure

A typical document should follow this structure:

1. Title
2. Introduction
3. Overview
4. Requirements (if applicable)
5. Instructions
6. Examples
7. Notes
8. Related Documents

Not every document requires all sections.

---

## Headings

Only one H1 heading is allowed.

Correct:

```markdown
# Installation

## Requirements

### Linux
```

Incorrect:

```markdown
# Installation

# Requirements

# Linux
```

---

## Table of Contents

Large documents should include a table of contents.

Small documents generally do not require one.

---

## Emoji Usage

Emoji improve readability when used consistently.

| Topic | Emoji |
|--------|--------|
| Overview | 📖 |
| Installation | 🚀 |
| Documentation | 📚 |
| Accounting | 💼 |
| Taxation | 🧾 |
| Plugins | 🔌 |
| Development | 🛠 |
| Community | 🌍 |
| Tips | 💡 |
| Notes | 📝 |
| Warning | ⚠️ |
| Success | ✅ |

Avoid excessive emoji.

---

## Writing Style

Write naturally.

Prefer:

- Short paragraphs
- Active voice
- Simple sentences

Avoid:

- Long paragraphs
- Unnecessary technical jargon
- Repeated explanations

---

## Persian Writing Rules

For Persian documentation:

- Use correct Persian punctuation.
- Avoid Finglish.
- Prefer Persian equivalents when they are commonly understood.
- Keep English technical terms when translation reduces clarity.

Example:

```
Git Commit
```

instead of inventing uncommon translations.

---

## English Writing Rules

English documentation should use:

- US English
- Plain language
- Short sentences

## Code Blocks

Always specify the language.

Example:

```bash
git clone https://github.com/...
```

```python
print("Hello")
```

For directory trees use:

```text
docs/
├── fa/
├── en/
└── assets/
```

---

## Tables

Use Markdown tables whenever comparison improves readability.

Example:

| Item | Description |
|------|-------------|
| Templates | Reusable accounting files |
| Plugins | Community extensions |

Avoid very wide tables.

---

## Images

Images should:

- Be relevant
- Use descriptive file names
- Prefer PNG or SVG
- Include alt text when possible

Store images under:

```text
assets/screenshots/
```

---

## Links

Prefer relative links.

Correct:

```text
../accounting/chart-of-accounts.md
```

Avoid hardcoded GitHub URLs whenever possible.

---

## File Naming

Use lowercase.

Use hyphens.

Good:

```text
opening-entry.md
```

Bad:

```text
OpeningEntry.md
```

---

## Directory Naming

Directories should also use:

- lowercase
- hyphens

Example:

```text
getting-started/
```

---

## Notes

Important notes may use this format:

> **Note**
>
> This feature is available starting from version X.

---

## Warnings

Warnings should be concise.

Example:

> **Warning**
>
> Always create a backup before modifying accounting data.

---

## Tips

Helpful suggestions:

> **Tip**
>
> You can duplicate templates instead of creating them from scratch.

## Examples

Whenever possible, include practical examples.

Examples improve learning more than long explanations.

---

## Versioning

Documentation evolves continuously.

Small improvements are encouraged.

Do not wait for major rewrites before contributing.

---

## Contributions

Every contribution should follow this guide.

If something is missing, improve this guide first.

---

## Related Documents

- architecture.md
- brand-guide.md
- CONTRIBUTING.md

---

## Future Improvements

The following topics may be added in future versions:

- Writing tone guide
- Screenshot standards
- Mermaid diagram standards
- Callout conventions
- Localization rules
- Translation workflow
- MkDocs conventions
- Review checklist

---

<div align="center">

### One Repository • One Style • One Voice

Made with ❤️ by the GnuCash Persian Community

</div>
