# Contributing to Product Hunt Launch Skills

Thank you for your interest in contributing to this project! Your help makes this resource better for everyone launching on Product Hunt.

## How to Contribute

### Reporting Issues

- Use GitHub Issues to report bugs or suggest improvements
- Include clear descriptions and examples when possible
- Check existing issues before creating a new one

### Suggesting New Skills

Have an idea for a new skill? Open an issue with:

1. **Skill name**: Following the `ph-*` naming convention
2. **Category**: Where it fits (strategy, content, marketing, etc.)
3. **Description**: What problem it solves
4. **Key content**: What guidance it should include

### Submitting Changes

1. **Fork** the repository
2. **Create a branch** for your changes (`git checkout -b feature/new-skill`)
3. **Make your changes** following the guidelines below
4. **Test** your changes locally
5. **Commit** with clear, descriptive messages
6. **Push** to your fork
7. **Open a Pull Request**

## Skill Format Guidelines

### File Structure

```
skills/[category]/[skill-name]/SKILL.md
```

### SKILL.md Format

```markdown
---
name: ph-skill-name
description: Brief description of the skill. Use this skill when [use case].
---

# Skill Title

[Introduction paragraph]

## When to Use This Skill

- Bullet points of use cases

## Main Content

[Detailed guidance organized in sections]

## Checklists

- [ ] Actionable items

## Output Format

[Template showing expected output]
```

### Writing Style

- **Clear and actionable**: Focus on practical guidance
- **Well-organized**: Use headers, lists, and tables
- **Specific**: Include real examples and templates
- **Up-to-date**: Reference current Product Hunt practices

### Naming Conventions

- Skill names: `ph-[descriptive-name]` (lowercase, hyphens)
- Categories: Lowercase, existing categories preferred
- Files: Always `SKILL.md` (uppercase)

## Code of Conduct

By participating in this project, you agree to maintain a respectful, inclusive environment. See [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) for details.

## Questions?

Feel free to open an issue for any questions about contributing. We're happy to help!

## License

By contributing, you agree that your contributions will be licensed under the MIT License.
