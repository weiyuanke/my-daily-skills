# CONTRIBUTING.md

## How to Contribute

Thank you for your interest in contributing to My Daily Skills!

### Adding a New Skill

1. **Fork the repository** (if you're an external contributor)
2. **Create a new branch** for your skill:
   ```bash
   git checkout -b add/skill-name
   ```

3. **Create your skill directory** under `skills/`:
   ```bash
   mkdir -p skills/your-skill-name
   ```

4. **Add required files**:
   - `SKILL.md` - Skill documentation (required)
   - `scripts/` - Implementation files
   - `references/` - Configuration and reference files
   - `README.md` - Additional documentation

5. **Update the main README.md** to include your skill

6. **Commit and push**:
   ```bash
   git add .
   git commit -m "add: new skill - your-skill-name"
   git push origin add/skill-name
   ```

7. **Create a Pull Request** with a clear description

### Skill Documentation

Each skill must include a `SKILL.md` file. Use this template:

```markdown
---
name: skill-name
description: "Brief description of what the skill does"
---

# Skill Name

## Description
Detailed description of the skill's functionality.

## Usage
How to use the skill.

## Examples
Usage examples.

## Configuration
Any required configuration.

## Dependencies
Required dependencies.
```

### Code Style

- Follow the existing code style in the repository
- Use meaningful variable and function names
- Add comments for complex logic
- Test your code before submitting

### Testing

- Test your skill locally before submitting
- Ensure it works with OpenClaw
- Document any known limitations

### Commit Messages

Use clear, descriptive commit messages:
- `add: new skill - skill-name`
- `fix: issue in skill-name`
- `docs: update skill documentation`
- `refactor: improve skill-name performance`

### Pull Request Process

1. Update README.md with your skill information
2. Ensure all tests pass
3. Provide a clear description of your changes
4. Link any related issues

## Code of Conduct

- Be respectful and inclusive
- Provide constructive feedback
- Help others learn and grow

## Questions?

Open an issue or contact the maintainer.

---

Thank you for contributing! 🎉
